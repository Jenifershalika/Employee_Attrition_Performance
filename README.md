# Employee_Attrition_Performance
Employee attrition means employees leaving the company voluntarily or involuntarily
# Employee Attrition Prediction

## Project Overview
This project aims to predict employee attrition using IBM HR Analytics dataset. The goal is to identify employees who are likely to leave the company so that HR can take proactive measures to retain talent. This project demonstrates skills in **data cleaning, exploratory data analysis (EDA), feature engineering, machine learning modeling, and evaluation**.

---

## Dataset
- Source: IBM HR Analytics Employee Attrition dataset
- Type: CSV (`IBM.csv`)
- Features include employee demographics, job satisfaction, work-life balance, salary, tenure, and more.
- Target variable: `Attrition` (Yes = 1, No = 0)

---

---

## Steps Performed
1. **Data Understanding**
   - Loaded dataset and checked data types, missing values, and statistical summary.
2. **Exploratory Data Analysis (EDA)**
   - Visualized target distribution and feature relationships.
   - Plotted correlations for numeric features.
3. **Data Cleaning & Feature Engineering**
   - Handled missing values (if any).
   - Converted categorical features using one-hot encoding.
   - Encoded target variable (`Attrition`).
4. **Train-Test Split**
   - Split data into 80% training and 20% testing.
5. **Model Training**
   - Built a **Logistic Regression** model.
6. **Model Evaluation**
   - Evaluated using accuracy, confusion matrix, and classification report.
7. **Insights**
   - Top features influencing attrition: `JobSatisfaction`, `OverTime`, `MonthlyIncome`.
   - Model accuracy: ~85% (example, depends on dataset version).

---

## Tools & Libraries Used
- Python 3.x
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## How to Run
1. Clone or download the repository.
2. Open the Jupyter Notebook: `notebooks/employee_attrition.ipynb`.
3. Ensure the dataset is located in `dataset/IBM.csv`.
4. Run all notebook cells sequentially.

---

## Outcome
- Predicts employee attrition effectively.
- Highlights key factors affecting attrition.
- Can help HR teams take proactive decisions.
