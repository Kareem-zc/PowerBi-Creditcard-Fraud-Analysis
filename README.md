# 🛡️ Online Payment Fraud Detection – Power BI Dashboard

This project presents an end-to-end **fraud risk analysis dashboard** built using **Power BI** to evaluate online payment fraud across banks, card types, locations, and fraud categories.

Using a dataset representing **1,000 Indian credit card transactions**, the dashboard helps fraud analysts and financial institutions:

- Detect **fraud patterns early**  
- Identify **high-risk customers, banks, states, and transaction types**  
- Measure **financial impact**  
- Support **data-driven fraud prevention decisions**

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `Credit_Fraud_Finals.pbix` | Final Power BI dashboard (complete visuals, DAX, data model) |
| `Credit Card Fraud Risk Analysis.csv` | Raw online payment transaction dataset |
| `Credit_Card_Fraud_Risk_Analysis_Cleaned.csv` | Cleaned dataset after Power Query transformations |
| `Fraud Detection DEPI Project.pdf` | Full project documentation & business insights |
| `Project_presentation.pptx` | Final presentation slides |
| `/screenshots` | Contains dashboard screenshots used below |

---

## 📸 Dashboard Pages (Screenshots)

### ▶️ **Start Page**
Shows entry screen for the interactive dashboard  
![Start](https://raw.githubusercontent.com/Kareem-zc/PowerBi-Creditcard-Fraud-Analysis/main/screenshots/start.png)

### 📊 **Overview Page**
![Overview](https://raw.githubusercontent.com/Kareem-zc/PowerBi-Creditcard-Fraud-Analysis/main/screenshots/overview.png)

### 🧪 **Fraud Types Analysis**
![Fraud Types](https://raw.githubusercontent.com/Kareem-zc/PowerBi-Creditcard-Fraud-Analysis/main/screenshots/fraudtypes.png)

### 🗺️ **Location-Based Risk**
![Location](https://raw.githubusercontent.com/Kareem-zc/PowerBi-Creditcard-Fraud-Analysis/main/screenshots/location.png)

### 📋 **Detailed Bank–Card Breakdown**
![Detailed](https://raw.githubusercontent.com/Kareem-zc/PowerBi-Creditcard-Fraud-Analysis/main/screenshots/detailed.png)

---

## 🔍 Key Insights from the Analysis

These findings come from the full analysis documented in the PDF report and the dashboard:

### **1️⃣ Overall Fraud Statistics**
- **Total Transactions:** 1,000  
- **Frauds Detected:** 286  
- **Fraud Rate:** ~28.6%  
- **Total Transaction Amount:** ₹12.23M  
- **Fraud Amount:** ₹3.31M  
- **Fraud Amount Share:** ~27%  

➡ **Fraud is significant both in count and in total value.**

---

### **2️⃣ Fraud Type Breakdown**
Most frequent frauds:
- **Card Not Present**  
- **Identity Theft**  
- **Card Skimming**  
- **Phishing**  
- **Account Takeover**  

Insights:
- Identity-based frauds show the **highest severity**.  
- Online/digital commerce categories contribute the most fraud.

---

### **3️⃣ High-Loss Fraud Categories**
Top fraud types by amount:
- **Identity Theft** – ~₹94K  
- **Card Not Present** – ~₹92K  
- **Account Takeover** – ~₹81K  

➡ These three represent a **majority of total fraud losses**.

---

### **4️⃣ Location-Based Findings**
States with highest fraud amount:
- Karnataka  
- Rajasthan  
- West Bengal  
- Uttar Pradesh  
- Maharashtra  

States with highest fraud rate:
- Karnataka (~35%)  
- Maharashtra (~33%)  

➡ High-fraud states correlate with high digital activity.

---

### **5️⃣ Risk by Banks & Card Types**
Banks with highest exposure:
- ICICI Bank  
- Federal Bank  
- Andhra Bank  
- Axis Bank  
- HDFC Bank  

Card Types:
- **Visa has the highest fraud rate (~33.7%)**.  
- Rupay shows the **lowest** fraud exposure.

➡ Visa transactions warrant extra monitoring in this dataset.

---

## 🛠️ Data Preparation (Power Query)

The dataset was cleaned and standardized using Power Query:

- Removed duplicates  
- Fixed data types (Date, Numeric, Categorical)  
- Created date hierarchies (Year, Month, Year-Month)  
- Standardized text categories  
- Added fraud classification fields & score buckets  
- Prepared table relationships for Power BI modeling

---

## 🧮 Power BI Modeling & DAX Measures

A single-table model was used with reusable DAX measures including:

- **Total Transactions**  
- **Total Fraud Transactions**  
- **Fraud Rate %**  
- **Total Fraud Amount**  
- **Fraud Amount %**  
- **Avg Fraud Score**  
- **Avg Fraud Transaction Amount**  

These measures drive insights across **card type, bank, merchant, state, fraud type**, and more.

---

## 🎨 Dashboard Design

Report pages include:

### **1. Overview Page**
- Key KPI cards  
- Fraud trend over time  
- Fraud by card type, bank, category  

### **2. Fraud Types Analysis**
- Fraud count & amount by fraud type  
- Fraud score behavior  
- Risk-tier distribution  

### **3. Location-Based Analysis**
- Geographic map  
- Top fraud states  
- State-wise fraud rate  

### **4. Detailed View**
- Bank & card type matrix  
- Fraud amount by merchant  
- Drill-down investigation table  

---

## 📘 Conclusion & Future Work

### ✔ Project Achievements
- Built a multi-page **fraud monitoring dashboard**  
- Identified **high-risk fraud types, states, and banks**  
- Quantified both **fraud amount** and **fraud rate**  
- Created a clear foundation for **fraud detection workflows**

### 🚀 Future Improvements
- Integrate **real-time fraud alerts**  
- Build **ML-based fraud prediction**  
- Add **merchant risk scoring**  
- Include **customer segmentation analytics**  
- Automate anomaly detection using score thresholds
  
