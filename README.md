# 📊 Zomato Restaurant Analytics Dashboard | Power BI

## 📌 Project Overview

This project presents an interactive **Zomato Restaurant Analytics Dashboard** built using **Power BI**.  
The dashboard analyzes restaurant data to uncover insights about ratings, votes, cuisines, city distribution, delivery availability, and cost patterns.

The goal of this project is to demonstrate strong data visualization, DAX, and business intelligence skills.

---

## 🎯 Business Objectives

- Analyze restaurant distribution across cities
- Understand rating performance categories (Excellent, Good, Average, Poor)
- Identify relationship between votes and ratings
- Evaluate online delivery trends
- Compare cost patterns across locations
- Discover popular cuisines

---

## 📊 Key KPIs

- ✅ Total Restaurants  
- ⭐ Average Rating  
- 💰 Average Cost for Two  
- 🗳 Total Votes  
- 🚚 Online Delivery Percentage  

---

## 📈 Dashboard Features

- 📍 City-wise Restaurant Distribution (Clustered Bar Chart)
- 🍽 Cuisine Analysis
- ⭐ Rating Distribution (Donut Chart)
- 📊 Votes vs Rating Scatter Plot
- 🌍 Map Visualization
- 🎛 Interactive Filters (City, Cuisine, Rating, Delivery)

---

## 🛠 Tools & Technologies Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (Data Cleaning & Transformation)
- Data Modeling
- Interactive Data Visualization

---

## 🧮 Important DAX Measures Used

```DAX
Total Restaurants = COUNT('zomato'[Restaurant Name])

Average Rating = AVERAGE('zomato'[Aggregate rating])

Total Votes = SUM('zomato'[Votes])

Avg Cost for Two = AVERAGE('zomato'[Average Cost for two])
Author
S Harini
