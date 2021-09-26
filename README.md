# Neural_Network_Charity_Analysis
## Overview of the analysis:
The purpose of the analysis is to predict which applicants will be successful if funded by Alphabet soup by analyzing the data from more than 34,000 organizations that received funding from Alphabet Soup over the years.

## Results:

#### Data Preprocessing
- The column Is_successful is the target. It has a value of 1 if the applicant was sucessful or 0 if the applicant was not successful.
- The following columns are used as input features for the neural net model
  NAME
  APPLICATION_TYPE—Alphabet Soup application type
  AFFILIATION—Affiliated sector of industry
  CLASSIFICATION—Government organization classification
  USE_CASE—Use case for funding
  ORGANIZATION—Organization type
  STATUS—Active status
  INCOME_AMT—Income classification
  SPECIAL_CONSIDERATIONS—Special consideration for application
  ASK_AMT—Funding amount requested  
 - The identificatio columns "EIN" is neither target nor features.
#### Compiling, Training, and Evaluating the Model
- The model achieved target performance when the number of hidden layers was increased to 3.
- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?
[!image](https://github.com/vijayabme/Neural_Network_Charity_Analysis/blob/main/Resources/model_params.png)
[!image](https://github.com/vijayabme/Neural_Network_Charity_Analysis/blob/main/Resources/target_accuracy.png)
#### Summary:

