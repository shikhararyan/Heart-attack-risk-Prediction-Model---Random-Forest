# Heart Disease UCI Dataset Analysis and Prediction

This repository contains a Jupyter Notebook that analyzes the Heart Disease UCI dataset using Python libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn. The notebook explores the dataset, visualizes relationships between features, builds a machine learning model using Random Forest Classifier, and evaluates its performance.

## Dataset Overview

The Heart Disease UCI dataset contains information related to heart disease diagnosis. It includes features such as age, sex, chest pain type, resting blood pressure, cholesterol level, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, and more. The target variable indicates the presence or absence of heart disease.

### Features
- **Age**: Age of the patient
- **Sex**: Sex of the patient (0 = male, 1 = female)
- **Chest Pain Type (cp)**: 
  - 0: Typical angina
  - 1: Atypical angina
  - 2: Non-anginal pain
  - 3: Asymptomatic
- **Resting Blood Pressure (trtbps)**: Resting blood pressure (in mm Hg)
- **Cholesterol (chol)**: Cholesterol level (in mg/dl)
- **Fasting Blood Sugar (fbs)**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **Resting Electrocardiographic Results (restecg)**:
  - 0: Normal
  - 1: Abnormality in ST-T wave
  - 2: Probable or definite left ventricular hypertrophy
- **Maximum Heart Rate Achieved (thalachh)**: Maximum heart rate achieved
- **Exercise Induced Angina (exng)**: Exercise-induced angina (1 = yes; 0 = no)
- **ST Depression Induced by Exercise (oldpeak)**
- **Slope of the Peak Exercise ST Segment (slp)**:
  - 0: Upsloping
  - 1: Flat
  - 2: Downsloping
- **Number of Major Vessels (caa)**: Number of major vessels colored by fluoroscopy
- **Thalassemia (thall)**:
  - 1: Fixed defect
  - 2: Normal blood flow
  - 3: Reversible defect
- **Target**: Presence of heart disease (0 = no, 1 = yes)

## Analysis and Model Building Steps

1. **Data Exploration and Visualization**: 
   - Exploratory data analysis (EDA) is performed to understand the distribution of features and their relationships with the target variable.

2. **Feature Engineering and Preprocessing**: 
   - Data preprocessing steps include handling missing values, dropping duplicates, encoding categorical variables, and feature scaling.

3. **Model Building (Random Forest Classifier)**: 
   - The dataset is split into training and testing sets.
   - A Random Forest Classifier is trained on the training data.
   - Predictions are made on the testing data, and the model's accuracy is evaluated.

4. **Performance Evaluation**: 
   - Various performance metrics such as accuracy, precision, recall, F1 score, specificity, false positive rate, and confusion matrix are calculated to assess the model's performance.
   
