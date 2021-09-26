# Neural_Network_Charity_Analysis
## Overview of the analysis:
The purpose of the analysis is to predict which applicants will be successful if funded by Alphabet soup by analyzing the data from more than 34,000 organizations that received funding from Alphabet Soup over the years.

## Results:

#### Data Preprocessing
- The column Is_successful is the target. It has a value of 1 if the applicant was sucessful or 0 if the applicant was not successful.
- The following columns are used as input features for the neural net model
  1.NAME
  2.APPLICATION_TYPE—Alphabet Soup application type
  3.AFFILIATION—Affiliated sector of industry
  4.CLASSIFICATION—Government organization classification
  5.USE_CASE—Use case for funding
  6.ORGANIZATION—Organization type
  7.STATUS—Active status
  8.INCOME_AMT—Income classification
  9.SPECIAL_CONSIDERATIONS—Special consideration for application
  20.ASK_AMT—Funding amount requested  
 - The identificatio columns "EIN" is neither target nor features.
#### Compiling, Training, and Evaluating the Model
- The model achieved target performance when the number of hidden layers was increased to 3. Below is the screenshot of the model parameters and accuracy.
![image](https://github.com/vijayabme/Neural_Network_Charity_Analysis/blob/main/Resources/model_params.png)
![image](https://github.com/vijayabme/Neural_Network_Charity_Analysis/blob/main/Resources/target_accuracy.png)
- I tried the below methods to imrpove the accuracy
  1. Adding the name column back into the features
  2. Increasing the number of hidden layers   
  3. Increasing the number of neurons in the hidden layers.
  4. Using sigmoid as the activation function for the hidden layers as well as the output.

#### Summary:
- The model significantly improved when we used a activation funcion such as sigmoid as its ideal for binary classification. 
- Increasing the number of hidden layers and changing the number of neurons helped significantly in distinguishing the target variable. 
- using a different classifier such as a Random Forest classifier also reached the target performance. It gave an accuracy of 77.6%.
