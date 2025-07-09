![alt text](https://github.com/denisgaribovic/customer-churn-prediction/blob/main/Banner.png)

# 🏦 Customer Churn Prediction

A production-ready machine learning pipeline that predicts customer churn using structured banking data and interpretable models. This project simulates how financial institutions can **proactively identify at-risk customers**, reduce churn, and improve retention strategies — all through a modular, scalable, and explainable ML approach.

---

## ✨ Highlights

- 📊 Built on a simulated customer dataset with ~10,000 records  
- 🔍 Visualized churn drivers using interactive Plotly dashboards  
- ⚙️ Engineered features via dummy encoding, scaling, and derived attributes  
- 🤖 Trained and compared Logistic Regression, Random Forest, and XGBoost models  
- 📈 Evaluated with Accuracy, Precision, Recall, F1 Score, and ROC AUC  
- 🧪 Demonstrated live predictions on new customer inputs  
- 🔄 Fully modular and reproducible — ready for integration or scaling  

---

## 🎯 Business Context

Customer churn is one of the most costly challenges for subscription-based and financial businesses. Proactively identifying at-risk customers helps organizations:

- 📉 Reduce acquisition and retention costs  
- 📊 Personalize marketing and outreach campaigns  
- 🔍 Gain insights into customer behavior patterns  
- 💡 Improve customer experience and satisfaction  

This project demonstrates a realistic, end-to-end churn prediction solution that can be integrated into CRM systems, dashboards, or customer success workflows.

---

## 🔐 Real-World Applications

This churn prediction system can be used to power:

- 🔔 Retention alerts for account managers or marketing teams  
- 🧠 Churn dashboards for customer insights and segmentation  
- 📬 Targeted offers and win-back campaigns  
- 🛠️ Risk scoring in CRM or support platforms  

---

## 📚 Dataset Overview

We use a simulated bank customer dataset containing key demographic and account-related fields:

| Feature | Description |
|--------|-------------|
| `CreditScore` | Customer credit score (numeric) |
| `Geography` | Country of residence (categorical) |
| `Gender` | Gender identity (categorical) |
| `Age` | Age of the customer |
| `Tenure` | Years as a customer |
| `Balance` | Account balance |
| `NumOfProducts` | Number of bank products used |
| `HasCrCard` | Whether the customer has a credit card |
| `IsActiveMember` | Engagement level |
| `EstimatedSalary` | Reported income |
| `Exited` | Churn flag (target variable) |

---

## 🛠️ Project Workflow

### 1. 📁 Data Loading & Preparation

- Loaded and cleaned a synthetic banking dataset (~10k rows)  
- Handled missing values and ensured data consistency  

### 2. 🔍 Exploratory Data Analysis (EDA)

- Created interactive dashboards using Plotly  
- Analyzed feature distributions, churn ratios, and relationships  
- Exported visuals for stakeholder reporting  

### 3. 🧱 Feature Engineering

- Applied dummy encoding for categorical variables  
- Scaled numerical features (MinMax or Standard Scaler)  
- Derived new features (e.g., balance-to-salary ratio, age bands)  

### 4. 🤖 Modeling & Comparison

- Trained and compared three models:
  - Logistic Regression (baseline, interpretable)  
  - Random Forest (robust to noise and nonlinear patterns)  
  - XGBoost (high-performance gradient boosting)

### 5. 📈 Model Evaluation

- Evaluated models using:  
  - ✅ Accuracy  
  - 📊 Precision, Recall, and F1 Score  
  - 🔍 ROC AUC Curve  
- Analyzed confusion matrix and ROC curves for each model  

### 6. 🧪 Prediction Demonstration

- Demonstrated predictions on new customer records  
- Explained prediction outputs for transparency  
- Simulated how a customer success team might act on predictions  

---

## 💡 Key Takeaways

- 🔍 Churn prediction is a powerful tool for retention and loyalty  
- 🤖 Even simple models can be highly effective with clean features  
- 📈 Evaluation metrics must balance precision and recall depending on business goals  
- 🧩 This pipeline is modular, interpretable, and ready for deployment into real-world systems  
