# Heart Disease Prediction Using Logistic Regression

This project focuses on predicting the 10-year risk of coronary heart disease (CHD) in patients using logistic regression. The dataset used for this study is sourced from an ongoing cardiovascular study conducted in Framingham, Massachusetts. The project explores data preprocessing, feature selection, model optimization, and performance evaluation.

## Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Methodology](#methodology)  
- [Implementation](#implementation)  
- [Results](#results)  
- [Conclusion](#conclusion)  
- [Future Scope](#future-scope)  

## Overview

The objective of this project is to leverage logistic regression for predicting heart disease risk in patients based on their medical data. This project demonstrates expertise in data preprocessing, hyperparameter tuning, and model evaluation using Python's machine learning libraries.

## Dataset

The dataset is derived from the Framingham Heart Study and includes over 4,000 patient records with 15 attributes. Key attributes include:  
- **Age:** Patient’s age (years).  
- **Gender:** Male/Female.  
- **Cholesterol Levels:** Total cholesterol in mg/dL.  
- **Smoking Status:** Whether the patient is a smoker.  
- **Blood Pressure Levels:** Systolic and diastolic blood pressure (mmHg).  
- **Diabetes:** Indicator of diabetes presence.  
- **BMI:** Body mass index (kg/m²).  
- **Heart Rate:** Resting heart rate (bpm).  
- **CHD Outcome:** Binary target variable indicating 10-year CHD risk (1 = at risk, 0 = not at risk).  

## Methodology

1. **Data Preparation:**  
   - Imported and cleaned the dataset.  
   - Handled missing values and standardized features for logistic regression.  

2. **Exploratory Data Analysis:**  
   - Analyzed the distribution of CHD outcomes.  
   - Explored correlations between features and the target variable.  

3. **Logistic Regression Implementation:**  
   - Built a logistic regression model to predict the 10-year CHD risk.  

4. **Hyperparameter Tuning:**  
   - Used GridSearchCV for tuning hyperparameters like `C` (regularization strength), `penalty` (l1/l2 regularization), and `solver` (liblinear/saga).  

5. **Evaluation:**  
   - Assessed model performance using accuracy, precision, recall, F1-score, and classification reports.  
   - Compared performance across different hyperparameter configurations using 5-fold cross-validation.  

## Results

- **Best Model Hyperparameters:**  
  The optimal values obtained through GridSearchCV were:  
  - `C = 1`  
  - `Penalty = l2`  
  - `Solver = saga`  

- **Model Performance:**  
  - **Accuracy:** 85% on the test set.  
  - **Precision and Recall:** High performance in distinguishing between CHD and non-CHD cases.  
  - **Classification Report:** Highlighted balanced results across different metrics.  

## Conclusion

This project successfully demonstrates the use of logistic regression for heart disease prediction. It showcases the importance of hyperparameter tuning and rigorous model evaluation in achieving reliable predictions.

## Future Scope

- Experiment with advanced algorithms like Random Forest, Gradient Boosting, or Neural Networks.  
- Incorporate additional features like genetic data or lifestyle factors for more robust predictions.  
- Develop a web-based interface for real-time CHD risk prediction for medical practitioners.
  
## Acknowledgments

This project was inspired by the GeeksforGeeks article on [Lung Cancer Detection Using Transfer Learning](https://www.geeksforgeeks.org/ml-heart-disease-prediction-using-logistic-regression/). Additional modifications and experiments were conducted to tailor the project for unique insights and contributions.   
