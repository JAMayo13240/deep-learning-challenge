# deep-learning-challenge
# Analysis of the Neural Network

# Overview
The dataset given revolves around a group of organizations receiving financial aid from Alphabet Soup with the status of whether their business venture was a success or not. The purpose of this analysis is to create a machine learning algorithm to predict a successful business venture with the company's financial aid given their various features.

# Results
## Data Preprocessing
  - For this analysis, only the successful column was utilized as a goal for the algorithm
  - All other features was used as features to determine the success of the funding, being:
     - Application Type
     - Affiliation
     - Classification
     - Service Type (Use_Type)
     - Organization Type
     - Status
     - Income Amount
     - Special Considerations
     - and Ask Amount
  - The EIN and name of the company was excluded from the analysis as being unique identifiers, it did not hold any significance to training the model.
## Compiling, Training, and Evaluating the Model
During the development of the algorithm, three distinct changes were made in an attempt to improve the accuracy
  - Adding an additional hidden layer
  - Increasing the units in each hidden layer, exluding the output layer containing the sigmoid activation
  - Increasing epoch count

# Summary
To conclude, the model was able to predict the state of whether a financial was successful or not with 73% accuracy. I would not recommend the model as the accuracy is too low. Further improvements, possibly increasing the accuracy up to 80%, will be needed before implementation of the algorithm in a large scale.
