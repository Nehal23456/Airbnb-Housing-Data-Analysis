# 🏠 Airbnb Data Analysis & Visualization Project

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Cleaning-150458?logo=pandas" />
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi" />
  <img src="https://img.shields.io/badge/NumPy-Analytics-013243?logo=numpy" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange" />
</p>

## 📌 Project Overview

This project focuses on analyzing Airbnb listing data and building an interactive Power BI dashboard to uncover insights related to pricing trends, room availability, neighbourhood performance, customer preferences, and geographic distribution.

The analysis combines **Python-based data processing** with **Power BI visualizations** to help identify:

* High-performing listings
* Premium neighbourhoods
* Revenue-generating room types
* Customer booking patterns
* Geographic concentration of properties

The project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Intelligence Reporting
* Dashboard Development

---

# 📂 Dataset Description

The dataset contains Airbnb listing information including:

| Column Name   | Description                     |
| ------------- | ------------------------------- |
| id            | Unique listing identifier       |
| host_id       | Unique host identifier          |
| host_name     | Name of the host                |
| name          | Listing/property title          |
| neighbourhood | Property location/neighbourhood |
| latitude      | Geographic latitude             |
| longitude     | Geographic longitude            |
| room_type     | Type of accommodation           |
| price         | Price per night                 |

### 🏡 Room Types Included

* Entire Home/Apartment
* Private Room
* Hotel Room
* Shared Room

---

# 🛠️ Technologies Used

## Python Libraries

* 🐍 Pandas
* 🔢 NumPy
* 📊 Matplotlib
* 📓 Jupyter Notebook

## Visualization Tool

* 📈 Power BI

---

# 🧹 Data Cleaning & Preparation

Before visualization, several preprocessing steps were performed:

✅ Removed missing/null values

✅ Standardized column names

✅ Sorted listings by price

✅ Filtered premium listings

✅ Grouped data by neighbourhood and room type

✅ Created calculated columns using:

```python
groupby()
transform()
```

### Key Transformations

* Maximum price by neighbourhood
* Average price by room type
* Total review counts
* Room type distribution
* Luxury vs Non-Luxury categorization

---

# 📊 Python Data Analysis

## 1️⃣ Neighbourhood Price Analysis

### Objective

Identify neighbourhoods containing the most expensive Airbnb listings.

### Key Insights

* Neighbourhood **28806** contained several premium listings.
* Luxury properties featured:

  * Hot Tubs
  * Saunas
  * Mountain Views
  * Premium Amenities

### Outcome

Properties with luxury amenities commanded significantly higher prices.

---

## 2️⃣ Room Type Distribution

### Objective

Determine market dominance among room categories.

### Findings

🥇 Entire Home/Apartment

🥈 Private Room

🥉 Hotel Room

🏅 Shared Room

### Insight

Entire homes dominate the Airbnb market and represent the majority of listings.

---

## 3️⃣ Price Analysis

### Objective

Analyze pricing behavior across room types.

### Findings

| Room Type   | Observation                        |
| ----------- | ---------------------------------- |
| Hotel Room  | Highest average price              |
| Shared Room | Lowest average price               |
| Entire Home | Highest total revenue contribution |

---

## 4️⃣ Review Analysis

### Objective

Identify highly engaging listings through customer reviews.

### Findings

* Downtown properties received the highest review counts.
* Luxury cabins attracted significant customer engagement.
* Tourist-centric locations generally had more reviews.

---

## 5️⃣ Geographic Analysis

### Objective

Visualize Airbnb listings geographically.

### Findings

* Most listings were concentrated around Asheville regions.
* Several high-density Airbnb clusters were identified.

---

# 📈 Power BI Dashboard

The Power BI dashboard provides interactive visual analytics using:

* KPI Cards
* Maps
* Charts
* Graphs
* Slicers
* Filters

---

## 🎯 Dashboard KPIs

The dashboard highlights:

* Total Listings
* Total Hosts
* Maximum Minimum Nights
* Average Minimum Nights
* Count of Room Types

These metrics provide an overall snapshot of the Airbnb market.

---

# 📊 Dashboard Visualizations

## 1. Sum of Reviews by Listing Name

### Visualization Type

📊 Horizontal Bar Chart

### Insight

Listings with higher review counts indicate strong customer engagement and popularity.

---

## 2. Sum of Price by Comfort Type

### Visualization Type

📈 Area / Line Chart

### Categories

* Luxurious
* Non-Luxurious

### Insight

Non-luxurious properties contributed higher overall revenue due to greater listing volume.

---

## 3. Room Type Count by Nights Defined

### Visualization Type

📊 Stacked Column Chart

### Insight

Most bookings were concentrated in the **1–2 night stay category**.

---

## 4. Geographic Property Mapping

### Visualization Type

🗺️ Map Visualization

### Insight

Properties were densely clustered in popular tourist neighbourhoods.

---

## 5. Average Price by Room Type

### Visualization Type

📊 Bar Chart

### Findings

* Hotel Rooms → Highest Average Price
* Shared Rooms → Lowest Average Price

---

## 6. Sum of Price by Neighbourhood

### Visualization Type

📈 Line Chart

### Insight

Certain neighbourhoods generated substantially higher revenue than others.

---

## 7. Room Type Distribution

### Visualization Type

🥧 Pie Chart

### Insight

Entire Home/Apartment listings accounted for nearly **90% of total listings**.

---

# ⭐ Advanced Analysis Features

## Luxury Property Detection

Listings were segmented into:

* 💎 Luxurious
* 🏠 Non-Luxurious

based on:

* Price
* Amenities
* Property Features

### Benefits

* Premium market identification
* Revenue analysis
* Customer demand assessment
* Pricing strategy evaluation

---

# 💡 Business Insights Generated

## Market Dominance

Entire homes dominate both inventory and revenue generation.

---

## Premium Listings

Luxury properties containing:

* Hot Tubs
* Saunas
* Mountain Views
* Game Rooms

showed significantly higher pricing.

---

## Geographic Trends

Airbnb properties were concentrated in high-tourism regions.

---

## Customer Preferences

Short stays of **1–2 nights** represented the most common booking behavior.

---

## Revenue Insights

Neighbourhood-level analysis identified premium revenue-generating zones.

---

# 🎯 Project Use Cases

This project can be applied to:

* Airbnb Market Analysis
* Pricing Strategy Optimization
* Tourism Trend Analysis
* Real Estate Investment Decisions
* Customer Behavior Analysis
* Business Intelligence Reporting

---

# 🚀 Skills Demonstrated

### Data Analytics

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis

### Python

* Pandas
* NumPy
* Matplotlib

### Power BI

* Dashboard Design
* DAX Measures
* KPI Reporting
* Interactive Visualizations

### Business Intelligence

* Revenue Analysis
* Customer Insights
* Market Segmentation
* Geographic Analytics

---

# 📌 Conclusion

The Airbnb Data Analysis Project successfully combines **Python-based data processing** and **Power BI dashboard development** to uncover meaningful business insights from Airbnb listing data.

The project demonstrates end-to-end analytical capabilities, from raw data preparation to interactive dashboard creation, enabling users to explore:

* Pricing Patterns
* Room Type Distribution
* Customer Engagement
* Neighbourhood Performance
* Geographic Trends

through a visually interactive and business-focused reporting solution.

---

## 👨‍💻 Author

**Nehal Gudage**

Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization
