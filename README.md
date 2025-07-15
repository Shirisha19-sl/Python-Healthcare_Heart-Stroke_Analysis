# Stroke Risk Prediction Using Machine Learning

## Introduction

This project applies machine learning techniques to predict the risk of stroke in patients using Electronic Health Record (EHR) data. The primary objective is to identify key risk factors such as age, BMI, hypertension, and glucose levels to enable early intervention and improve patient outcomes.

# Project Goals
Identify relationships between risk factors and stroke occurrence
Explore class imbalance and apply oversampling techniques
Use classification models to predict stroke risk
Derive actionable health insights from descriptive and predictive analysis

# Techniques Used

#### Data Cleaning: 
Imputation of missing BMI values, outlier detection (Z-score), encoding of categorical variables

#### EDA:
 Correlation analysis, class distribution visualizations, boxplots, histograms

#### Modeling:
Decision Tree, Logistic Regression, Random Forest, Support Vector Machine (SVM)

#### Evaluation Metrics:
 Accuracy, F1 Score (to evaluate performance on imbalanced dataset)

# Results
While Random Forest and Decision Tree had the highest accuracy, SVM had the best F1 score, showing better sensitivity toward the minority class (stroke cases).

# Key Insights
Stroke risk increases significantly after age 50, with highest risk around age 80
High glucose levels (>200 mg/dL) and BMI between 25–30 are strongly associated with stroke cases
Males and urban residents showed slightly higher heart disease and stroke prevalence
Data imbalance and missing values (especially in smoking status) are crucial challenges in model accuracy

# Business Implications
Better predictive tools can assist healthcare providers in identifying at-risk individuals
Focused wellness campaigns and targeted data collection (e.g., smoking history) can improve model reliability
Cost-effective risk assessments can reduce long-term medical costs and support preventive care

# Conclusion
Machine learning models, especially Random Forest and SVM, show strong potential for early stroke prediction. This project demonstrates the importance of data preprocessing and class balance in healthcare analytics. Future enhancements could integrate imaging data (e.g., CT/MRI scans) to improve diagnostic accuracy.

