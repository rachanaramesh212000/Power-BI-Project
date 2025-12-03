# 🕵🏻‍♀️Credit Card Fraud Risk Analysis – Power BI Dashboard

## 🔍 Project Overview

**Problem Statment**

Credit card fraud leads to significant financial losses and harms customer trust. The goal of this project is to identify transaction patterns associated with fraudulent behavior, prioritize high‑risk segments (customers, merchants, card types, banks, locations), and provide a dashboard that business and risk teams can use to monitor and respond to fraud in near real‑time.

**Objective**
Build a **clean, well-structured Power BI model** that:


1. Profile fraudulent vs non‑fraudulent transactions and compute key fraud KPIs.

2. Identify top fraud types, high‑risk states, merchants, banks and card types.

3. Build visual dashboards to communicate findings to stakeholders.

4. Suggest operational rules or features useful for a real‑time fraud detection pipeline.

---
## 🧱 Tech Stack

- **Power BI Desktop**
- **Power Query (M)** for cleaning & shaping data  
- **DAX** for measures, indices & time-intelligence  

---

## 📂 Data Dictionary

1. **Transaction ID** : Unique ID given to each transaction. 
2. **Customer Name** : Name of the customer who made the transaction. 
3. **State** : State/Location of the customer. 
4. **Card Type** : Type of card used (Visa, Rupay, Mastercard, Amex). 
5. **Bank** : Name of the bank that issued the credit card. 
6. **Merchant Name**: Business or company where the transaction occurred (e.g., Amazon, Zomato). 
7. **Merchant Location** : City/location of the merchant. 
8. **Transaction Date** : Date on which the transaction happened. 
9. **Transaction Amount** : The amount spent in the transaction. 
10. **Transaction Category** : Category of purchase (Food, Apparel, Electronics, Transportation, etc.). 
11. **Fraud Risk** : Risk level of the transaction (Low, Medium, High, Critical). 
12. **Fraud Type**: Type of fraud detected (Phishing, Card Skimming, Identity Theft, etc.). 
13. **Is Fraud**: Shows whether the transaction is fraud or not. 
14. **Fraud Score**: Fraud score given by the system (0–100).

---
 ## 📊 Dashboard Pages & Key Insights

 <img width="1195" height="665" alt="Image" src="https://github.com/user-attachments/assets/504b4a42-01f6-4785-89b5-a2bb1ec212cf" />

 **Key Features**
  **🧮 KPI cards**

    - Total Transactions
    - Fraud Count (number of transactions labeled fraud)
    - Fraud Rate (%) = Fraud Count / Total Transactions
    - Average Fraud Score
    - Fraudulent Transaction Amount by Fraud Type / Card Type / Bank / State
    - Monthly Fraud Trend

  **📈 Category-Wise Fraud Amount**
 - Highest fraudulent transaction amounts appear in E-commerce, Electronics, and Apparel categories.
 - Fraud types like Card Skimming and Identity Theft also show high transaction amounts.

  **Fraud Risk Distribution**
 - Low-risk transactions account for 42%, but still contain fraud cases.
 - High and Critical risk together form over 30%, showing strong fraud patterns.

  **State-Wise Fraud**
 - Maharashtra, Karnataka, Rajasthan, and West Bengal show the highest number of fraudulent transactions.
 - These states may have higher digital spending and fraud exposure.
  
  **Monthly Fraud Trend**
 -  Fraud peaks during April, June, September, and December.
 - Seasonal trends suggest fraud increases during festive and high-shopping months.

    <img width="1102" height="636" alt="Image" src="https://github.com/user-attachments/assets/6a53996c-f472-4bfa-bc98-e86345fa4ac6" />

    **Bank-Wise Fraud**

    - ICICI Bank, Andhra Bank, and Kotak Bank have the highest fraudulent transaction amounts.
    - Indicates higher exposure or higher online volume among these bank customers.

    **High-Risk Customers**

    - Customers from Telangana, Uttar Pradesh, Tamil Nadu, West Bengal, and Gujarat show high fraud scores.
    - These individuals require closer monitoring and extra verification.

    **Merchant Pattern Insights**

     - Fraud risk is highest in E-commerce, Electronics, Food Delivery, and Groceries.
     - Certain states show high-risk zones when combined with certain merchant types.

    **Card Type Analysis**
     - Visa and Amex cards show the highest fraudulent amounts.
     - Mastercard and Rupay have lower fraud amounts.
     - This indicates Visa/Amex may be used more frequently in online transactions, making them more targeted.
    
       ### 🔮 Future Enhancements

        **Machine Learning model for real-time fraud prediction**
        - Detect suspicious transactions instantly and prevent fraud before it happens.

        **Automated fraud alerts (SMS / Email / App notifications)**
        - Notify customers and banks immediately for high-risk transactions.

        **Geolocation & device-based fraud detection**
        - Track unusual behavior such as transactions from two distant locations in a short time.

        **Customer spending behavior analysis**
        - Identify unusual spending patterns and trigger additional verification.

        **AI-based Fraud Score improvement**
        - Increase accuracy of risk scoring using predictive algorithms.

        **Integration with banking APIs**
        - Enable real-time monitoring instead of batch updates.

        **Investigation dashboard for bank fraud teams**
        - Detailed case tracking & filtering by fraud type, state, merchant, and risk level.

        **Predictive analytics for future fraud trends**
         - Forecast future fraud growth by category, location, and card type.
    
      


