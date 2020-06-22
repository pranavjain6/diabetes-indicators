# Predicting Diabetes
## Problem Description
The objective is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset and to find out the factors which largely cause the condition.

All patients in the dataset are female.

Diabetes is caused due to various factors such as pregnancies, glucose, blood pressure, skin thickness, insulin, BMI and age.
## Features in data set
Pregnancies: Number of times pregnant

Glucose: Plasma glucose concentration over 2 hours in an oral glucose tolerance test

BloodPressure: Diastolic blood pressure (mm Hg)

SkinThickness: Triceps skin fold thickness (mm)

Insulin: 2-Hour serum insulin (mu U/ml)

BMI: Body mass index (weight in kg/(height in m)2)

DiabetesPedigreeFunction: Diabetes pedigree function (a function which scores likelihood of diabetes based on family history)

Age: Age (years)
## Target Variable 
Outcome: Class variable (0 if non-diabetic, 1 if diabetic)
## Model Description
Numpy, Pandas, Matplotlib, Seaborn libraries have been used for Data Cleaning, Exploratory Data Analysis, and Data Visualization.

Feature Scaling and Feature Selection Techniques have been performed.

Logistic Regression, K-Nearest Neighbors, Decision Trees and Random Forests models have been used.

Accuracy score: 87.44 using Random Forest model. 
## Inference
For a patient to be diabetic, the insulin reading is the biggest determining factor followed by the glucose reading. 
