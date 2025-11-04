# 🧠 Predictive Employee Attrition Analysis  

### 📊 Overview  
This project aims to **predict employee attrition** using machine learning techniques on HR analytics data.  
By analyzing factors such as job satisfaction, income, and overtime, the model identifies key predictors of turnover and helps organizations design better retention strategies.  

---

### 🎯 Objectives  
- Build a predictive model to classify employees likely to leave.  
- Perform **Exploratory Data Analysis (EDA)** to identify HR insights.  
- Determine the most significant factors affecting employee attrition.  
- Visualize and interpret model results effectively.  

---

### ⚙️ Tools & Technologies  
- **Languages:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Environment:** Jupyter Notebook   
- **Dataset:** [IBM HR Analytics Employee Attrition Dataset – Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

### 🧩 Project Workflow  

1. **Data Preprocessing**  
   - Cleaned the dataset and dropped redundant columns.  
   - Encoded categorical features and normalized numerical values.  

2. **Exploratory Data Analysis (EDA)**  
   - Explored relationships between employee satisfaction, salary, and attrition.  
   - Created visualizations for department-wise and age-wise attrition.  

3. **Model Building**  
   - Trained a **Random Forest Classifier** to predict employee turnover.  
   - Evaluated using accuracy, confusion matrix, and classification report.  

4. **Feature Importance**  
   - Identified top influential factors:  
     `OverTime`, `MonthlyIncome`, `JobSatisfaction`, `YearsAtCompany`, and `Age`.  

---

### 📈 Results  
| Metric | Value |
|---------|--------|
| **Model Accuracy** | ~85% |
| **Algorithm Used** | Random Forest Classifier |
| **Evaluation Metrics** | Accuracy, Precision, Recall, F1-Score |

---

### 📊 Visual Insights  
- Employees with **low job satisfaction** and **high overtime hours** are more likely to leave.  
- **Lower salaries** and **fewer promotions** lead to higher attrition.  
- Feature importance visualizations show that **OverTime** and **Income** are key drivers.  

