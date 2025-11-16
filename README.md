# 🏦 UPI Transaction Analytics – User Behaviour Insights  

### *Interactive Power BI Dashboard | User Segmentation • Behaviour Analysis • Fintech Insights*

---

## 📘 Project Overview  
This project explores UPI (Unified Payments Interface) transaction behaviour across multiple user dimensions such as city, age group, gender, device type, merchant, and payment purpose.  
A two-page **interactive Power BI dashboard** with **10 synced slicers** enables deep behavioural analysis, helping uncover user patterns similar to real-world fintech product analytics.

---

## 🎯 Objectives  
- Analyse user transaction behaviour across demographics and regions  
- Identify high-engagement user segments and top transacting cities  
- Understand monthly spending and balance trends  
- Enable data-driven insights for fintech and product decisions  

---

## 🛠️ Tools & Technologies  
- **Power BI** – Dashboard & DAX  
- **Microsoft Excel** – Data cleaning  
- **Power Query** – Data transformation  
- **DAX Measures** – Trend calculations  

---

## 📊 Dashboard Features  

### 🔹 1. Ten Synced Slicers  
Filters applied across both pages:  
City • Age Group • Gender • Device • Merchant • Payment Purpose • Payment Method • Bank Sent • Bank Received • Status  

---

### 🔹 2. Monthly Transaction Trends  
Visualised using **line & column charts** to show:  
- Monthly Transaction Amount (2024)  
- Monthly Balance Trend  
- Seasonal highs and lows  

```
![Monthly Transaction Trends](images/transaction_trends.png)
```

---

### 🔹 3. City-wise Performance Matrix  
Compares:  
- Total Transaction Amount  
- Remaining Balance  
- City-level behavioural differences  

```
![City Matrix](images/city_matrix.png)
```

---

### 🔹 4. Merchant, Device & Demographic Insights  
Breakdown of:  
- Top merchants  
- Most active devices  
- Gender-wise transaction behaviour  
- Age-group-based spending patterns  

```
![User Segments](images/user_segments.png)
```

---

## 🧠 Key Insights  
- **Peak usage months:** May & October  
- **Most active age groups:** 18–25, 26–35  
- **Top devices:** Android  
- **High-volume cities:** (From dashboard insights)  
- Clear spikes during festival periods  
- Strong correlation between city, device type & transaction patterns  

---

## 🧩 Data Model (Simplified)

```
+-------------------+        +-----------------------+
| User Info Table   | 1 --- ∞| Transactions Table    |
| (Age, Gender,     |        | (Amount, Balance,     |
|  City, Device)    |        |  Merchant, Purpose)   |
+-------------------+        +-----------------------+

           +------------------------+
           | Bank Table            |
           | (Bank Sent/Received)  |
           +------------------------+
```

---

## 🧪 Workflow  

### **1. Data Cleaning (Excel)**  
- Removed all duplicates  
- Standardised city & merchant names  
- Normalised date/time fields  
- Fixed inconsistent bank naming  

### **2. Data Modelling (Power BI)**  
- Built relationships  
- Created DAX measures:  
  - Total Transaction Amount  
  - Total Balance  
  - Monthly Amount Trend  
  - Monthly Balance Trend  

### **3. Dashboard Development**  
- Designed a clean two-page layout  
- Added 10 synced slicers  
- Applied interactions & drill-throughs  
- Built visual KPIs and matrix views  

---

## 📁 Project Structure  

```
📂 UPI-Analytics-Dashboard
 ├── README.md
 ├── UPI_Dashboard.pbix
 ├── data/
 │    └── upi_data.xlsx
 └── images/
      ├── transaction_trends.png
      ├── city_matrix.png
      ├── user_segments.png
      └── dashboard_page2.png
```

---

## 💡 Conclusion  
This UPI analytics dashboard demonstrates:  
- Strong understanding of **user behaviour**  
- Ability to translate data into **product insights**  
- High-quality dashboard & data modelling skills  
- Fintech-focused analytical thinking  

---

## 🔗 Connect  
**LinkedIn:** *Add your link here*  
**GitHub:** *Repository link here*  

