# Pima Indians Diabetes Analysis & Prediction
This project explores a dataset from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.  
This project focuses on analyzing medical data to identify the primary risk factors contributing to diabetes in a specific population. As an aspiring Data Analyst with a background in System Analysis, I have applied a structured approach to data cleaning, visualization, and statistical exploration to derive meaningful health insights.

Dataset Description
The dataset consists of several medical predictor variables and one target variable (Outcome).
Pregnancies: Number of times pregnant.
Glucose: Plasma glucose concentration.
BloodPressure: Diastolic blood pressure (mm Hg).
SkinThickness: Triceps skin fold thickness (mm).
Insulin: 2-hour serum insulin (mu U/ml).
BMI: Body mass index (weight in kg/(height in m)^2).
DiabetesPedigreeFunction: A function that scores the likelihood of diabetes based on family history.
Age: Age in years.

Tech Stack
Language: Python.
Libraries: Pandas (data manipulation), Seaborn & Matplotlib (data visualization), NumPy.

Key Analysis Phases
Data Quality Audit: Identified and handled "logical" missing values (e.g., zero values in Blood Pressure or BMI that are physiologically impossible).
Exploratory Data Analysis (EDA): Utilized correlation matrices and distribution plots to understand the relationship between variables.
Statistical Insights: Analyzed how glucose levels and age significantly impact the probability of a positive diabetes diagnosis.

Key Insights
Glucose as a Primary Indicator: A clear correlation exists between high glucose levels and diabetes prevalence.
BMI Influence: Higher BMI values show a strong upward trend in positive outcomes, highlighting metabolic health as a key factor.
Age Factor: Risk factors tend to cluster and intensify within specific age brackets in this dataset.

How to Run
Bash
# Clone the repository
git clone https://github.com/[your-new-username]/Pima-Indian-Diabetes-Analysis.git

# Install dependencies
pip install pandas seaborn matplotlib
