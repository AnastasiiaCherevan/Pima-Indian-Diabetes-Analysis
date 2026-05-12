# Pima Indians Diabetes Analysis & Prediction
This project explores a dataset from the National Institute of Diabetes and Digestive and Kidney Diseases. 

🎯 Project Objective

The goal of is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.  
This project focuses on analyzing medical data to identify the primary risk factors contributing to diabetes in a specific population. As an aspiring Data Analyst with a background in System Analysis, I have applied a structured approach to data cleaning, visualization, and statistical exploration to derive meaningful health insights.

Dataset Description
The dataset consists of several medical predictor variables and one target variable (Outcome).
Pregnancies: Number of times pregnant.
Glucose: Plasma glucose concentration.
BloodPressure: Diastolic blood pressure (mm Hg).
SkinThickness: Triceps skin fold thickness (mm).
Insulin: 2-hour serum insulin (mu U/ml).
BMI: Body mass index (weight in kg/(height in m^2)).
DiabetesPedigreeFunction: A function that scores the likelihood of diabetes based on family history.
Age: Age in years.

Tech Stack
Language: Python.
Libraries: Pandas (data manipulation), Seaborn & Matplotlib (data visualization), NumPy.

Key Analysis Phases
1. Data Quality Audit - Identified and handled "logical" missing values (e.g., zero values in Blood Pressure or BMI that are physiologically impossible).
2. Exploratory Data Analysis (EDA) - Utilized correlation matrices and distribution plots to understand the relationship between variables.
![Corelation matrice](https://github.com/AnastasiiaCherevan/Pima-Indian-Diabetes-Analysis/blob/main/images/heatMap.png)
![distribution plots](https://github.com/AnastasiiaCherevan/Pima-Indian-Diabetes-Analysis/blob/main/images/mainPropDistr.png)
4. Statistical Insights - Analyzed how glucose levels and age significantly impact the probability of a positive diabetes diagnosis.
5. Statistical Breakpoints - Calculated specific risk thresholds (e.g., at what BMI level the risk of diabetes doubles).
6. Hypothesis Testing - Used p-values to ensure that the identified patterns were not merely results of random chance (avoiding the "Confirmation Bias" discussed in my professional network).

How to Run
Bash
# Clone the repository
git clone https://github.com/AnastasiiaCherevan/Pima-Indian-Diabetes-Analysis.git

# Install dependencies
pip install pandas seaborn matplotlib
