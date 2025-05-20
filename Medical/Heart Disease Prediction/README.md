# Heart Disease Prediction

## Overview
This project aims to predict the likelihood of heart failure in patients based on clinical and laboratory features. Using machine learning algorithms, we analyze a heart failure dataset to build accurate classification models that can assist medical professionals in early diagnosis and treatment.

## Dataset
The dataset contains clinical features such as age, serum creatinine, platelets count, ejection fraction, and others, along with a target variable `DEATH_EVENT` indicating if the patient died during the follow-up period.

## Features
- **age**: Age of the patient (years)
- **anaemia**: Decrease of red blood cells or hemoglobin (0 = no, 1 = yes)
- **creatinine_phosphokinase**: Level of the CPK enzyme in the blood (mcg/L)
- **diabetes**: If the patient has diabetes (0 = no, 1 = yes)
- **ejection_fraction**: Percentage of blood leaving the heart at each contraction (%)
- **high_blood_pressure**: If the patient has hypertension (0 = no, 1 = yes)
- **platelets**: Platelets count in the blood (kiloplatelets/mL)
- **serum_creatinine**: Level of serum creatinine in the blood (mg/dL)
- **serum_sodium**: Level of serum sodium in the blood (mEq/L)
- **sex**: Gender of the patient (0 = female, 1 = male)
- **smoking**: If the patient smokes (0 = no, 1 = yes)
- **time**: Follow-up period (days)
- **DEATH_EVENT**: Target variable (0 = lived, 1 = died)

## Machine Learning Models Used
- Support Vector Machine (SVM)
- XGBoost Classifier
- Neural Network (Deep Learning)

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction
