# 🍽 Food App Data Exploration & Analysis (SQL Server)

## 📌 Project Overview
This project involves **exploring and analyzing a Food Delivery App dataset** using **SQL Server**.  
The dataset contains **9000+ restaurant records** with details such as `Restaurant_ID`, `Restaurant_Name`, `City`, `Location`, `Cuisines`, and more.

The objective:
- Understand restaurant distribution across countries & cities.
- Analyze ratings, votes, cuisines, and service offerings.
- Identify trends & provide actionable insights.

---

## 🛠 Technologies Used
- SQL Server
- Windows Functions
- Joins, Aggregations, Filtering
- Data Cleaning & Transformation

---

## 🔍 Data Exploration Tasks
- Checked table details (columns, data types, constraints).
- Identified & removed duplicates in `Restaurant_ID`.
- Removed unnecessary columns.
- Merged two tables & added `Country_Name` column using `CountryCode`.
- Corrected misspelled city names.
- Used rolling/moving counts with window functions.
- Calculated `MIN`, `MAX`, and `AVG` for votes, ratings & currency.
- Created a **rating category** column.

---

## 📊 Key Insights
- **Country distribution:**
  - 90.67% of listings from **India**, 4.45% from USA.
- **Online delivery availability:**
  - Only 2 countries offer it.
  - India (28.01%), UAE (46.67%).
- **City-level insights (India):**
  - Connaught Place, New Delhi – most restaurants (122).
  - Popular cuisine: **North Indian**.
  - Only 54/122 offer table booking.
  - Table booking avg rating: **3.9**, without booking: **3.7**.
- **Best moderately priced restaurant:**
  - Cost for two < ₹1000, Rating > 4, Votes > 4, Indian Cuisine, both table booking & delivery.
  - **"India Restaurant" in Kolkata** (ID: 20747).

---
