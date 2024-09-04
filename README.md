# Premature-Mortality

In this project, I studied what factors have a linear relationship with premature mortality. I considered internal and external factors. The report aims to find the “best” linear regression model that tells what internal and external factors are related to premature mortality. 

### Step 1: Clean
Clean the data to select variables I needed and remove NAs. The data is obtained from OpenToronto with 140 observations and 13 variables. 

### Step 2: Training & Testing
Split the data into training and testing dataset. The training dataset consists of 80% of whole dataset, while testing dataset consists of 20% of whole dataset. Then I conducted EDA to have a brief overview of the data

### Step 3: Fit a Model
Fit an original model with all variables related to premature mortality in training dataset and study the assumptions (linearity, constant variance, uncorrelated errors, and normality) that are required in linear regression. I used Box-Cox Transformation to correct the model violations. 

### Step 4: Model Selection
Use backward selection and manual selection to improve the model and decide what variables to include or exclude.

### Step 5: Model Validation
Conduct Model validation with the testing dataset and find the best final model. I compared violations, AIC/BIC, adjusted R square, problematic observations predictors’ coefficients, and significance for models in training with models in testing. Determine the final model. 

### Step 5: Conclusion
Premature Mortality is related to percentage of getting Colorectal Cancer for young age group, number of Food programs, health providers in community, and Percentage of Teen Pregnancy. 
