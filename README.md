# Diabeties_Prediction

### Feature Engineering

#### Problem Statement

A machine learning model is requested to be developed that can predict whether individuals are diabetic or not given their features. You are expected to perform the necessary data analysis and feature engineering steps before developing the model.

#### Data Set

The dataset is part of a large dataset held at the National Institutes of Diabetes and Digestive and Kidney Diseases in the USA. It consists of data used for a diabetes study on Pima Indian women over the age of 21 living in Phoenix, the 5th largest city in the state of Arizona, USA.

The target variable is specified as "outcome"; 1 indicates a positive result of the diabetes test, while 0 indicates a negative result.

- Variables: 9
- Observations: 768
- Size: 24 KB

- Pregnancies: Number of pregnancies
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- Blood Pressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Skin fold thickness
- Insulin: 2-Hour serum insulin (mu U/ml)
- DiabetesPedigreeFunction: Diabetes pedigree function
- BMI: Body mass index
- Age: Age (years)
- Outcome: Presence of disease (1) or not (0)

#### Data Set Story

#### Project Tasks

##### Task 1: Exploratory Data Analysis

1. Examine the general picture.
2. Capture numeric and categorical variables.
3. Analyze numeric and categorical variables.
4. Perform target variable analysis. (Average of target variable according to categorical variables, average of numeric variables according to target variable)
5. Conduct outlier observation analysis.
6. Conduct missing observation analysis.
7. Perform correlation analysis.

##### Task 2: Feature Engineering

1. Perform necessary operations for missing and outlier values. There are no missing observations in the dataset, but observation units containing a 0 value in variables like Glucose, Insulin, etc., might be indicating missing values. Considering this, you can assign zero values as NaN in relevant values and then apply operations for missing values.
2. Create new variables.
3. Perform encoding operations.
4. Standardize numeric variables.
5. Create a model.
