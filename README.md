# Pima Indians Diabetes Analysis & Prediction
This project explores a dataset from the National Institute of Diabetes and Digestive and Kidney Diseases. 

## 🎯 Project Objective

The goal of is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.  
This project focuses on analyzing medical data to identify the primary risk factors contributing to diabetes in a specific population. As an aspiring Data Analyst with a background in System Analysis, I have applied a structured approach to data cleaning, visualization, and statistical exploration to derive meaningful health insights.

## Dataset Description

### Dataset
[Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/jamaltariqcheema/pima-indians-diabetes-dataset)

### Viriables description
The dataset consists of several medical predictor variables and one target variable (Outcome).
Original column names were refactored into a more concise and descriptive format to facilitate easier programmatic access and reduce syntax errors during the modeling phase.
- Pregnancies > preg: Number of times pregnant.
- Glucose > gluco: Plasma glucose concentration.
- BloodPreasure > bp: Diastolic blood pressure (mm Hg).
- SkinThickness > skin: Triceps skin fold thickness (mm).
- Insulin > insul: 2-hour serum insulin (mu U/ml).
- BMI > bmi: Body mass index (kg/m²).
- DiabetesPedigreeFunction > pedig: A function that scores the likelihood of diabetes based on family history.
- Age > age: Age in years.
- Outcome > target: Target variable (0 or 1) Where "1" is diabetic person and "0" - non diabetic.


### Tech Stack
Language: Python.
Libraries: Pandas (data manipulation), Seaborn & Matplotlib (data visualization), NumPy.

### Key Analysis Phases
1. Data Quality Audit
   Identified and handled "logical" missing values (e.g., zero values in Blood Pressure or BMI that are physiologically impossible).
2. Exploratory Data Analysis (EDA)
   Utilized correlation matrices and distribution plots to understand the relationship between variables.
![Corelation matrice](https://github.com/AnastasiiaCherevan/Pima-Indian-Diabetes-Analysis/blob/main/images/heatMap.png)
![distribution plots](https://github.com/AnastasiiaCherevan/Pima-Indian-Diabetes-Analysis/blob/main/images/mainPropDistr.png)
3. Statistical Insights
   Analyzed how glucose levels and age significantly impact the probability of a positive diabetes diagnosis.
4. Statistical Breakpoints
   Calculated specific risk thresholds (e.g., at what BMI level the risk of diabetes doubles).
5. Hypothesis Testing
   Used p-values to ensure that the identified patterns were not merely results of random chance (avoiding the "Confirmation Bias" discussed in my professional network).

## How to Run

Bash
### Clone the repository
git clone https://github.com/AnastasiiaCherevan/Pima-Indian-Diabetes-Analysis.git

### Install dependencies
pip install pandas seaborn matplotlib
