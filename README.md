# 📊 Customer Churn Analysis and Prediction (Power BI + Python + SQL)

This project showcases a full-fledged **Customer Churn Analysis and Prediction System** that utilizes:

- 🔍 **Exploratory Data Analysis (EDA)** in **Power BI**
- ⚙️ **Predictive Modeling** using **Python (Random Forest Classifier)**
- 🧾 **SQL** for **Data Cleaning & Transformation**
- 📈 **Power BI** for **Interactive Dashboards**

---

## 📁 Dataset

The dataset contains anonymized customer records with demographic information, subscription details, service usage patterns, and churn labels.

📄 **Uploaded as:** `Customer_Data.csv`

---

## 🔧 Technologies Used

| Tool                | Purpose                                  |
|---------------------|------------------------------------------|
| Power BI            | Dashboard creation, transformation       |
| Python (scikit-learn) | Predictive churn model (Random Forest) |
| SQL Server          | Data cleaning, null handling, preprocessing |
| Power Query         | Dimension grouping, KPI creation         |
| Excel               | Data source formatting & joins           |

---

## 🧠 Machine Learning Model

A **Random Forest Classifier** is used to predict customer churn based on encoded categorical and numerical features.

### 🔑 Key Steps:

- Label Encoding for categorical variables  
- Feature selection  
- Train-test split  
- Model training and evaluation  

### 📌 Evaluation Metrics

- ✅ Accuracy Score  
- ✅ Confusion Matrix  
- ✅ Classification Report  
- ✅ Feature Importance Graph  

---

## 🔍 Power BI Insights

The Power BI dashboard highlights:

- 📌 Churn Rate by Age, Tenure, Contract Type, and State  
- 📊 Predicted vs Actual Churn  
- 📉 Revenue contribution of churned customers  
- 📌 KPI cards for Total Customers, Churners, Joiners  
- 🔍 Unpivoted services to track usage trends  


## 🧾 SQL Operations

Performed using a structured pipeline:

- ✅ Data Exploration (null check, group distribution)  
- ✅ Staging Table Cleanup  
- ✅ Final View Creation (`vw_ChurnData`, `vw_JoinData`)  
- ✅ Handling NULLs using `ISNULL()`  
- ✅ Revenue Share by Churners

## 📸 Dashboard Preview


