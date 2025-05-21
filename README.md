# Heart-Failure-prediction-project-using Deep_learning
To build an Artificial Neural Network (ANN) using PyTorch to predict heart failure risk from clinical data
## Intoduction
  Heart Failure Prediction Dataset was collected from Kaggle inorder to determine the cause of heart diseases with the foolowing features 
  ## Features 
 * Age	
 * Sex	
 * ChestPainType	
 * RestingBP	
 * Cholesterol	
 * FastingBS	
 * RestingECG	
 * MaxHR	
 * ExerciseAngina	
 * Oldpeak	
 * ST_Slope

## Operations
 ### Exploratory Data Analysis (EDA): To check for duplicates, identify missing values and perform feature distribution

 ### Data Preprocessing : To Handle Missing Values, Encode Categorical Variables by converting categorical features into numerical form
using one-hot encoding, Feature Scaling using StandardScaler inorder  to normalize numerical features for better ANN performance and then Train-Test Split was done by seperating the test data from the train data for proper analysis and testing

## Build, Train & Evaluate the ANN Model using PyTorch
The model was trained with multiple epochs with forward and backward pass in the training loop and BCELoss used for binary classification and Adam optimizer  used for optimizer to minimize the weight

