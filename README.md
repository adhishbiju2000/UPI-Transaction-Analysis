# 🏦 UPI Transaction Analytics – User Behaviour Insights  

### *Interactive Power BI Dashboard | User Segmentation • Behaviour Analysis • Fintech Insights*

---
<img width="878" height="484" alt="Dashbord" src="https://github.com/user-attachments/assets/3270e532-0ad2-4b0a-b495-87c2302ab92d" />

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

<img width="1366" height="725" alt="Dashboard full screen" src="https://github.com/user-attachments/assets/27077111-d74d-4e71-8fc6-a64cbb248b73" />

---

### 🔹 2. Monthly Transaction Trends  
Visualised using **line & column charts** to show:  
- Monthly Transaction Amount (2024)  
- Monthly Balance Trend  
- Seasonal high
-
- <img width="1366" height="726" alt="5" src="https://github.com/user-attachments/assets/1dfef965-1857-4980-9d5a-0fdd8bc96c12" />
s and lows  

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
<img width="1366" height="726" alt="5" src="https://github.com/user-attachments/assets/82958384-b08c-49eb-bc45-a03155fab824" />

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
<img width="1366" height="730" alt="7" src="https://github.com/user-attachments/assets/d02ee9ab-f3bb-43fc-97f6-6bbf962bbf66" />


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
<img width="1366" height="727" alt="Last" src="https://github.com/user-attachments/assets/b4390f74-f6b1-4a65-b945-44d16ba2cb5b" />

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
**LinkedIn:** *[Add your link here](https://www.linkedin.com/in/adhishbiju/)*  

