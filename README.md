# HR Analytics and Attrition Dashboard

This repository contains an interactive **HR Analytics** project analyzing employee attrition using the IBM HR Analytics dataset. The project includes **data preprocessing, exploratory data analysis (EDA), feature importance analysis**, and an **interactive Gradio dashboard** for visual exploration.

---

## 📂 Dataset

The dataset used is the **IBM HR Analytics Employee Attrition & Performance** dataset.  

- CSV File: `WA_Fn-UseC_-HR-Employee-Attrition.csv`
- Columns include:
  - Employee demographics (Age, Gender, MaritalStatus, etc.)
  - Job-related features (JobRole, Department, OverTime, JobLevel, etc.)
  - Compensation (MonthlyIncome, StockOptionLevel, etc.)
  - Attrition (target variable: Yes/No)

> **Note:** If the dataset is not included, you can download it from [Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset).

---

## 🛠 Project Overview

1. **Data Preprocessing**
   - Removed constant or irrelevant columns (`EmployeeCount`, `Over18`, `StandardHours`)
   - Encoded categorical features using LabelEncoder
   - Checked for missing values and duplicates

2. **Exploratory Data Analysis (EDA)**
   - Distribution of numerical and categorical features
   - Boxplots and barplots vs Attrition
   - Correlation heatmap
   - Insights on high-risk job roles, departments, and overtime patterns

3. **Feature Importance**
   - Trained a Random Forest classifier
   - Visualized feature importance for predicting employee attrition

4. **Interactive Gradio Dashboard**
   - Explore numeric feature distributions
   - Boxplots vs Attrition
   - Categorical feature barplots
   - Correlation heatmap
   - Feature importance visualization
   - Question-based insights:
     - How many employees are leaving?
     - Which features affect attrition the most?
     - High-risk roles, departments, and profiles

---

## 🚀 How to Use

1. Open the notebook in **[Google Colab](https://colab.research.google.com/)**.  
2. Ensure the dataset CSV is in the path `/content/` or update the path in the notebook.  
3. Run all cells sequentially.  
4. The **Gradio dashboard** will launch automatically.  
5. Use the tabs or select questions from the dropdown to explore HR insights interactively.

---

## 📊 Key Insights from Analysis

- Employees working **overtime** or in certain **JobRoles** (e.g., Sales) have higher attrition.  
- **Younger employees** and those with **lower job satisfaction** are more likely to leave.  
- Important features affecting attrition:
  - Overtime
  - JobLevel
  - StockOptionLevel
  - JobSatisfaction
  - TotalWorkingYears  

---

## 🛠 Tools & Libraries

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Gradio (for interactive dashboard)

---

## 📁 Repository Structure

