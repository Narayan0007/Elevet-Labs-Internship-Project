# Elevet-Labs-Internship-Project

# 📊 Customer Churn Prediction for Telecom Industry

This project aims to predict customer churn in a telecom company using supervised machine learning techniques. Identifying customers likely to leave helps the business implement proactive retention strategies.

## 🧠 Objective

To develop a machine learning model that accurately predicts whether a customer will churn, based on historical customer data and usage patterns.

---

## 🗂️ Dataset

- **Source:** [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Size:** 7,043 rows × 21 columns
- **Target Variable:** `Churn` (Yes/No)

---

## ⚙️ Project Workflow

1. **Data Preprocessing**
   - Removed irrelevant features (e.g., `customerID`)
   - Handled missing values in `TotalCharges`
   - Converted categorical features using Label Encoding
   - Addressed class imbalance using SMOTE

2. **Exploratory Data Analysis**
   - Analyzed churn patterns by contract type, tenure, monthly charges, etc.
   - Correlation analysis for numerical features
   - SQL queries for business-level insights

3. **Modeling**
   - Trained and evaluated the following models:
     - Decision Tree
     - Random Forest
     - XGBoost
   - Used metrics like accuracy, precision, recall, F1-score

4. **Model Selection**
   - **RandomForestClassifier** showed the best performance across all key metrics and was chosen as the final model.

---

## 📈 Key Findings

- Customers with month-to-month contracts and electronic check payments are more likely to churn.
- Senior citizens and customers with higher monthly charges have higher churn rates.
- Long-tenure customers and those using additional services (tech support, online security) are less likely to churn.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy, Seaborn, Matplotlib**
- **Scikit-learn**
- **XGBoost**
- **RandomForestClassifier**
- **Imbalanced-learn (SMOTE)**
- **SQLite3 for SQL queries**
- **Google Colab for development**

---

## 🚀 Recommendations

- Deploy the XGBoost model into a CRM-integrated production pipeline.
- Trigger customer retention workflows for predicted churners.
- Retrain the model quarterly using new customer data.
- Enhance features using behavioral or customer service interaction data.

---

## 📌 Future Work

- Use SHAP or LIME for explainability of predictions.
- Explore time-series modeling for churn over time.
- Build customer segments for personalized retention offers.

---

## 📂 Files in Repository
