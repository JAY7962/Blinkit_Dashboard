# 🛒 BlinkIT Sales Dashboard (Power BI)

## 📘 Project Overview
This project presents an **interactive Power BI dashboard** that visualizes key business insights from **BlinkIT (formerly Grofers)** sales data.  
The dashboard enables users to analyze **sales performance**, **item distribution**, and **outlet characteristics** based on various parameters like outlet size, location, and item type.

The goal of this analysis is to help stakeholders make data-driven decisions regarding **product strategy**, **store operations**, and **sales optimization**.

<p align="center">
  <img src="<p align="center">
  <img src="https://github.com/JAY7962/Blinkit_Dashboard/blob/dff8329154365c7ed693ecef7cdecd67e9278831/Images/logo.png?raw=true" width="100%" alt="BlinkIT Dashboard Banner"/>
</p>

## 📊 Dataset Description

**Dataset:** `BlinkIT Grocery Data.xlsx`  
The dataset includes grocery item-level data collected from multiple BlinkIT outlets.  

| Column Name | Description |
|--------------|-------------|
| Item_Identifier | Unique ID for each item |
| Item_Weight | Weight of the product |
| Item_Fat_Content | Indicates whether the item is low-fat or regular |
| Item_Visibility | The percentage of total display area allocated to this item |
| Item_Type | Category of the grocery item (e.g., Dairy, Snacks, Beverages) |
| Item_MRP | Maximum retail price of the item |
| Outlet_Identifier | Unique ID for each outlet |
| Outlet_Establishment_Year | Year when the outlet was established |
| Outlet_Size | Size of the store (Small / Medium / High) |
| Outlet_Location_Type | Tier of the outlet’s location (Tier 1, Tier 2, Tier 3) |
| Outlet_Type | Type of store (Grocery Store, Supermarket Type1, Type2, Type3) |
| Item_Outlet_Sales | Sales of the item in a specific outlet |
| Rating | Customer rating for the item |

---

## ⚙️ Dashboard Features

![image alt](https://github.com/JAY7962/Blinkit_Dashboard/blob/d74e697467e8509b79d430065c56f6a3dee2d6a1/Images/Blinkit_Dashboard.png)

### 1️⃣ Key Performance Indicators (KPIs)
- **Total Sales:** `$1.2M`
- **Average Sales per Item:** `141`
- **Number of Items:** `8523`
- **Average Rating:** `3.92`

### 2️⃣ Filters / Slicers
- **Item Type**
- **Outlet Size**
- **Outlet Location Type**

### 3️⃣ Visual Insights
#### 🧈 Fat Content Analysis
- Pie chart showing distribution of **Low Fat vs Regular Fat** items.
- Tier-wise comparison of total sales by fat content.

#### 🏪 Outlet Analysis
- **Outlet Establishment Trend (2010–2022)**  
  → Shows how outlet age impacts sales.
- **Outlet Count by Tier**  
  → Tier 3 contributes the largest share of total sales (≈71%).
- **Outlet Size Contribution**  
  → Large outlets drive the highest sales (~42.3%).

#### 🍞 Item Type Insights
- Bar chart comparing total sales across various item types.
- Top-selling categories: Fruits, Snack Foods, and Household Items.

#### 📋 Tabular Summary
| Outlet Type | No. of Items | Total Sales | Avg Sales | Avg Rating | Item Visibility |
|--------------|--------------|--------------|------------|-------------|-----------------|
| Supermarket Type2 | 928 | $131.5K | 141.7 | 3.9 | 0.06 |
| Grocery Store | 308 | $151.9K | 140.3 | 3.9 | 0.10 |
| Supermarket Type1 | 5577 | $787.5K | 141.2 | 3.9 | 0.09 |
| Supermarket Type3 | 935 | $130.7K | 139.8 | 3.9 | 0.06 |

---

## 🧠 Insights & Recommendations
- **Tier 3 outlets** generate the majority of total sales — potential for further expansion.  
- **Regular fat products** slightly outperform low-fat ones in total sales.  
- **Large outlet sizes** correlate strongly with higher sales volume.  
- **Snack Foods and Fruits** are consistently top-selling categories — ideal for promotions or cross-selling.  
- Sales peaked around **2018**, suggesting a period of strong operational growth.

---

## 🧩 Tools & Technologies Used

| Category | Tools / Technologies |
|-----------|----------------------|
| Dashboarding | Power BI |
| Data Cleaning / Processing | Power BI |
| Data Source | BlinkIT Grocery Dataset |
| Visualization | Charts, Pie Charts, Bar Graphs, Cards, Slicers |
| Analytics | DAX Measures, Filters, Aggregations |

