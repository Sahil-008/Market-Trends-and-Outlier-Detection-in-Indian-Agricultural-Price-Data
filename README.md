# 
---

## 🧠 Dataset Overview

The dataset (`Customer_Data.csv`) contains customer-level information including:

- `Customer_ID`: Unique customer identifier  
- `Gender`, `Value_Deal`: Demographic & subscription plan data  
- `Monthly_Charge`, `Total_Charges`: Financial metrics  
- `Tenure_in_Months`: Subscription duration  
- `Customer_Status`: Target variable (Churned or Active)  
- Additional service interaction features like `Total_Extra_Data_Charges`, `Total_Long_Distance_Charges`, etc.

---

## 📊 Exploratory Data Analysis

Using Python (`pandas`, `seaborn`, `matplotlib`), we:
- Cleaned missing values and irrelevant columns  
- Explored patterns between churn and tenure, billing issues, gender, etc.  
- Identified high-risk churn categories and service patterns

---

## 🤖 Machine Learning Model

- **Algorithm Used:** XGBoost Classifier  
- **Feature Engineering:** One-hot encoding, feature scaling  
- **Target Variable:** Binary churn indicator (`Churn`)  
- **Evaluation Metrics:** Confusion matrix, ROC AUC score, classification report  
- **ROC AUC Score Achieved:** **> 0.85**

Predicted churn probabilities were exported to a CSV for Power BI integration.

---

## 💡 SQL Insights

The SQL queries answer strategic questions such as:
- Who are the top 10 revenue-generating customers?
- Which plan types show the highest churn rate?
- What is the estimated monthly revenue loss due to churn?
- How does gender or long-distance service usage impact churn?

> File: `customer project sql.sql`

---

## 📈 Power BI Dashboard

The dashboard provides interactive visuals and KPIs, including:
- Churn vs Active breakdown  
- Gender-wise churn pie chart  
- Value Deal vs Churn Rate stacked chart  
- Monthly revenue loss KPI  
- Top churned customers with billing issues  
- Churn trend line over time

> Files: `dashboard.pbix`, `Dashboard.pdf`

---

## 📌 Key Findings

- Customers with **lower tenure** and **high extra data charges** have a higher churn probability.
- Certain **Value Deal plans** show increased churn risk.
- **Female customers** exhibit slightly higher churn percentages.
- High **monthly charges** correlate with churn likelihood.

---

## 🛠️ Tech Stack

- **Python**: pandas, scikit-learn, seaborn, XGBoost  
- **SQL**: MySQL for querying customer data  
- **Power BI**: For business intelligence and visual storytelling  
- **Tools**: Jupyter Notebook, VS Code, GitHub

---

## 🔮 Future Improvements

- Deploy the model with Flask or Streamlit for real-time prediction
- Integrate with a customer service platform for alert generation
- Include NLP-based sentiment analysis from customer reviews
- Expand dataset to include more behavioral and interactional features

---

## 🙌 Authors

**Team Grid Crafters** – Lovely Professional University  
> Sahil Kumar Singh, Bidwai Gajanan Arun, Gampala Vijay Kumar, Musunuri Yajna Sri, Prudhvi

---

## 📜 License

This project is for educational and academic use. Feel free to fork or build upon it with attribution.

