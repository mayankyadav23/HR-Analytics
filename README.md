# ✨ HR Analytics: Employee Attrition & Performance Analysis ✨


## 📍 Objective
Employee attrition refers to the rate at which employees leave a company. The goal of this project is to model employee attrition and identify the most significant factors influencing turnover. This analysis helps HR professionals predict how many employees are likely to leave and which employees are at the highest risk, thus informing retention strategies.


## 😇 Motivation
This project aims to leverage data analytics to improve employee satisfaction, reduce operational costs, and enhance overall organizational performance. Using data-driven insights allows organizations to create a positive work environment and retain talent.

## 📐 System Architecture

![Screenshot 2024-10-11 132131](https://github.com/user-attachments/assets/16fc3dda-91c8-4c25-a624-df4b6f5a0394)

The analysis was performed as follows:

1. **Load the Dataset**: The IBM HR Analytics Attrition Dataset is loaded.
2. **Data Exploration**: Basic information about the dataset is gathered and key attributes identified.
3. **Data Cleaning**: Missing values are handled, and the dataset is cleaned for further analysis.
4. **Data Visualization**: Visualizations are created using `Matplotlib` and `Seaborn` to explore trends in attrition.
5. **Statistical Analysis**: 
   - **ANOVA Test** for numerical feature importance.
   - **Chi-Square Test** for categorical feature importance.
6. **Data Preprocessing**: 
   - The target variable, `Attrition`, is mapped to binary values.
   - Features are selected and encoded using one-hot encoding.
7. **Train-Test Split**: Data is split into training and testing sets using `train_test_split`.
8. **Modeling**: Various machine learning algorithms are implemented, including:
   - Logistic Regression
   - Random Forest
   - Support Vector Machine
   - XGBoost
   - LightGBM
   - CatBoost
   - AdaBoost
9. **Model Evaluation**: Accuracy scores and confusion matrices are computed.
10. **Comparison**: Model performance is compared using ROC curves.

## 📁 Dataset
The dataset used in this project is a hypothetical dataset created by IBM data scientists. It contains **1470 rows** and **35 columns**, including both numeric and categorical features related to employee characteristics.

[Dataset Link](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)

### Dataset Attributes:
- Age
- Attrition
- BusinessTravel
- Department
- DistanceFromHome
- Education
- EducationField
- EnvironmentSatisfaction
- Gender
- JobInvolvement
- JobLevel
- JobSatisfaction
- MaritalStatus
- MonthlyIncome
- OverTime
- TotalWorkingYears
- WorkLifeBalance
- YearsAtCompany
- ... and more.

## 📝 Libraries Used:
- `Pandas`
- `NumPy`
- `Matplotlib`
- `Seaborn`
- `HvPlot`
- `SciPy`
- `Sklearn`
- `XGBoost`
- `LightGBM`
- `CatBoost`
- `Warnings`


## ⚠️ Prerequisites:
- Python Programming
- Data Science
- Data Analysis
- Data Pre-processing
- Data Visualization
- Statistical Analysis
- Machine Learning Algorithms


## ✨ Model Evaluation:

| Algorithm              | Training Data Accuracy | Testing Data Accuracy |
|------------------------|------------------------|-----------------------|
| Logistic Regression     | 0.9271                 | 0.8639                |
| Random Forest           | 0.8902                 | 0.8413                |
| Support Vector Machine  | 0.9349                 | 0.8662                |
| XGBoost                 | 1.0000                 | 0.8526                |
| LightGBM                | 1.0000                 | 0.8390                |
| CatBoost                | 0.9845                 | 0.8503                |
| AdaBoost                | 0.9077                 | 0.8322                |

## 📈 Comparing Model Performance Using ROC Curve:

![Screenshot 2024-10-11 132227](https://github.com/user-attachments/assets/3cec7a69-7ea5-4522-864f-72917d374614)


## 🔑 Conclusion
This project provided a comprehensive analysis of employee attrition using the IBM HR Analytics dataset. By implementing various machine learning models, we identified the most effective predictors of employee turnover. These insights can help HR teams implement targeted retention strategies and optimize workforce performance.

---
## 📩 Feedback
If you have any feedback, please reach out to me on [LinkedIn](https://linkedin.com/in/mayankyadv)

