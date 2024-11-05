# Insurance-Provider-and-Billing-Amount-Analysis

## Overview
The **Insurance Provider and Billing Amount Analysis** project aims to investigate the variations in billing amounts across different insurance providers, medical conditions, and admission types within a healthcare dataset. The project utilizes data analysis and machine learning techniques to provide insights into billing practices and predict billing amounts.

## Table of Contents

- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Data Sources](#data-sources)
- [Results](#results)

## Project Description

This analysis involves several key steps:

1. **Data Preparation**: Loading and cleaning the dataset, including handling missing values, duplicates, and standardizing text formats.
2. **Exploratory Data Analysis (EDA)**: Visualizing billing amounts by insurance provider and examining the distribution of billing amounts.
3. **Feature Engineering**: Transforming categorical variables into a suitable format for machine learning models.
4. **Model Training and Evaluation**: Employing various regression models to predict billing amounts and evaluating their performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Data Sources

The dataset used for this project was taken from the Kaggle website. Each column provides specific information about the patient, their admission, and the healthcare services provided. A brief explanation of features in the dataset:
  - Name: name of the patient associated with the healthcare record
  - Age: age of the patient at the time of admission
  - Gender
  - Blood Type
  - Medical Condition: specifies the primary medical condition or diagnosis associated with the patient, such as "Diabetes," "Hypertension," "Asthma," and more.
  - Date of Admission
  - Doctor: Name of the doctor responsible for the patient's care
  - Hospital: Name of the hospital where the patient was admitted
  - Insurance Provider: patient's insurance provider
  - Billing Amount: amount of money billed for the patient's healthcare services during their admission
  - Room Number: where the patient was accommodated during their admission
  - Admission Type: specifies the type of admission, which can be "Emergency," "Elective," or "Urgent"
  - Discharge Date
  - Medication: medication prescribed or administered to the patient during their admission
  - Test Results: results of a medical test conducted during the patient's admission - "Normal," "Abnormal," or "Inconclusive"

## Results

The analysis revealed that billing amounts are relatively consistent across different insurance providers. The Random Forest Regressor performed best in predicting billing amounts, with the following performance metrics:

Mean Absolute Error (MAE): 11,610.45
Root Mean Squared Error (RMSE): 13,710.82
For more detailed results and visualizations, refer to the analysis section of the code.

