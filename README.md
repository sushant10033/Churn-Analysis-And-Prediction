# Churn-Analysis-And-Prediction
# End-to-End Customer Churn Analysis 🚀

This project is an end-to-end customer churn analysis pipeline that uncovers key insights, builds predictive models, and delivers business-driven recommendations. 

## 📌 Project Objective

To analyze and predict customer churn using a real-world telecommunications dataset. The goal is to:
- Identify major drivers of customer churn.
- Build and evaluate machine learning models to predict churn.
- Provide actionable business insights to reduce churn.

---

## 📊 Dataset

The dataset used in this project includes details on:
- Customer demographics
- Subscription details
- Internet and phone service usage
- Billing and payment methods
- Churn status


---

## 🧠 Tools & Technologies

| Category        | Tools / Frameworks Used                          |
|----------------|--------------------------------------------------|
| Data Analysis   | Python (Pandas, NumPy), Jupyter Notebooks       |
| Visualization   | Seaborn, Matplotlib, Plotly                     |
| Machine Learning| Scikit-learn, XGBoost, Logistic Regression      |
| Evaluation      | Confusion Matrix, ROC-AUC, Precision/Recall     |
| Dashboarding    | Power BI                                        |


---

## 🧪 Key Steps & Workflow

### 1. **Data Cleaning & Exploration**
- Handle missing values
- Perform EDA to understand trends and correlations
- Visualize distributions of churn vs. key variables

### 2. **Feature Engineering**
- Convert categorical columns using Label/One-Hot Encoding
- Engineer new features (e.g., tenure groups, total services)
- Scale numerical features

### 3. **Model Building**
- Baseline models: Logistic Regression, Decision Tree
- Advanced models: Random Forest, XGBoost
- Model comparison using accuracy, ROC-AUC, F1-score

### 4. **Model Interpretation**
- Feature importance analysis
- SHAP values for explainability

### 5. **Business Insights**
- Segment high-risk customers
- Recommend strategies for customer retention

---

## 📈 Model Performance Summary

| Model             | Accuracy | ROC-AUC | F1-Score |
|------------------|----------|---------|----------|
| Logistic Regression | 80.2%   | 84.5%   | 0.68     |
| Random Forest       | 83.1%   | 87.2%   | 0.71     |
| XGBoost             | 84.3%   | 89.1%   | 0.73     |

> 📍 *Metrics may vary depending on tuning and validation splits.*

---

## 💡 Insights & Recommendations

- Customers with fiber optic internet and high monthly charges are more likely to churn.
- Long-tenure customers and those on yearly contracts have lower churn probability.
- Streamlining payment methods and promoting bundle services can reduce churn.

---




