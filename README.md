# Loan Eligibility Prediction

![Python](https://img.shields.io/badge/Python-3.14-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Internship](https://img.shields.io/badge/Hex%20Softwares-Internship-blueviolet)

## Overview

This project was completed as part of the **Hex Softwares Data Science Internship**.

The objective of this project is to build a machine learning model capable of predicting whether a loan application will be approved based on an applicant's demographic and financial information.

The project follows a complete data science pipeline, including data preprocessing, exploratory data analysis, feature engineering, model development, and performance evaluation.

---

## Dataset

The dataset contains information about loan applicants, including:

* Gender
* Marital Status
* Dependents
* Education
* Employment Status
* Applicant Income
* Co-applicant Income
* Loan Amount
* Loan Amount Term
* Credit History
* Property Area
* Loan Status (Target Variable)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas.
* Examined the structure and data types.

### 2. Data Cleaning

* Handled missing values.
* Removed unnecessary features.
* Checked for duplicate records.

### 3. Exploratory Data Analysis (EDA)

* Distribution plots
* Count plots
* Correlation heatmap
* Pair plots
* Box plots

### 4. Feature Engineering

* Label Encoding
* Feature Scaling
* Train-Test Split

### 5. Machine Learning Models

The following classification algorithms were implemented:

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)

---

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | **80%**  |
| KNN                 | 76%      |
| Random Forest       | 75%      |
| Decision Tree       | 69%      |

### Best Performing Model

**Logistic Regression** achieved the highest accuracy of **80%** and was selected as the final model.

---

## Results

The model successfully predicts loan approval based on applicant information.

Key observations include:

* Credit history strongly influences loan approval.
* Applicant income contributes to prediction performance.
* Logistic Regression performed best on this dataset.
* Proper preprocessing significantly improved model performance.

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Machine Learning
* Model Evaluation
* Classification Algorithms
* Python Programming

---

## Future Improvements

Possible enhancements include:

* Hyperparameter tuning using GridSearchCV.
* Cross-validation.
* Feature selection techniques.
* Ensemble learning methods such as XGBoost or LightGBM.
* Deployment as a web application using Flask or Streamlit.

---

## Author

**Kabelo Motshabi Makgae**

Data Science Intern

Hex Softwares Internship

---

## Acknowledgements

Special thanks to **Hex Softwares Pvt. Ltd.** for providing this internship opportunity and project guidance.

This project was completed for educational purposes as part of the Data Science Internship Program.
