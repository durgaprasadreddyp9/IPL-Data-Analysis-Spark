# 🏏 IPL Data Analysis with PySpark

## 📌 Overview
This project analyzes **Indian Premier League (IPL) data** using **Apache Spark (PySpark)** to derive **key cricket insights**. The dataset includes **ball-by-ball match details, player statistics, and match outcomes**, enabling deep analysis of **player performances, match trends, and team strategies**.

### 🔹 **Key Insights:**
✅ **Top Scoring Batsmen per Season**  
✅ **Most Economical Bowlers in Powerplay Overs**  
✅ **Impact of Toss on Match Outcomes**  
✅ **Venue-wise Score Distribution**  
✅ **Average Runs in Winning Matches**  

---

## 🏗 **Data Pipeline & Processing**
### **1️⃣ Data Ingestion**
- Loaded structured **CSV datasets** from **AWS S3** into **Spark DataFrames**.

### **2️⃣ Data Cleaning & Transformation**
- **Removed invalid deliveries** (wide/no-balls).
- **Extracted year, month, and day** for time-based analysis.
- **Normalized player names** and handled missing values.

### **3️⃣ Data Aggregation & SQL Queries**
- **Used Spark SQL** to analyze **player statistics, team performances, and match outcomes**.

### **4️⃣ Data Visualization**
- **Matplotlib & Seaborn** used for insights on **economical bowlers, toss impact, and venue-wise scores**.

---

## 📊 **Sample Analyses & Visualizations**

