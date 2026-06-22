Airbnb Data Analysis & Visualization Project – Detailed Description
Project Overview

This project focuses on analyzing Airbnb listing data and building an interactive dashboard to understand pricing trends, room availability, neighbourhood performance, and customer preferences. The analysis was performed using Python (Pandas) for data processing and Power BI for interactive visualizations.

The dashboard provides insights into Airbnb properties based on room types, neighbourhoods, pricing, reviews, and geographical distribution. It helps identify high-performing listings, expensive neighbourhoods, and market patterns useful for business intelligence and decision-making.

Dataset Description

The dataset contains Airbnb listing information with important attributes such as:

Column Name	Description
id	Unique listing identifier
host_id	Unique host identifier
host_name	Name of the host
name	Listing/property title
neighbourhood	Area or locality of the property
latitude	Geographic latitude
longitude	Geographic longitude
room_type	Type of room offered
price	Price per night

The dataset includes different room categories such as:

Entire home/apartment
Private room
Hotel room
Shared room
Technologies Used
Python Libraries
Pandas
NumPy
Matplotlib
Jupyter Notebook
Visualization Tool
Power BI
Data Cleaning & Preparation

Several preprocessing steps were performed before visualization:

Removed missing/null values
Standardized column names
Sorted listings by price
Filtered premium listings
Grouped data by neighbourhood and room type
Created calculated columns using Pandas groupby() and transform()

Example operations included:

Maximum price by neighbourhood
Average price by room type
Total review counts
Room type distribution
Price segmentation into luxurious and non-luxurious categories
Python Data Analysis Performed
1. Neighbourhood Price Analysis

The project analyzed which neighbourhoods contain the most expensive listings.

Key Insight
Neighbourhood 28806 contained several high-priced luxury Airbnb properties.
Listings with hot tubs, saunas, mountain views, and premium amenities had significantly higher prices.
2. Room Type Distribution

The dataset was grouped by room_type to identify market dominance.

Findings
Entire home/apartment listings dominated the market.
Private rooms were the second-largest category.
Shared rooms and hotel rooms represented a very small portion of listings.
3. Price Analysis

Average and total prices were calculated for each room type.

Observations
Hotel rooms had the highest average price.
Shared rooms were the cheapest accommodation type.
Entire homes generated the largest total revenue contribution.
4. Review Analysis

The project analyzed review counts to identify highly engaging listings.

Findings
Downtown and luxury cabin properties received the highest review counts.
Popular listings were generally located near tourist areas and city centers.
5. Geographic Analysis

Latitude and longitude coordinates were used to map Airbnb properties geographically.

Outcome
Most properties were concentrated around Asheville city regions.
Clustering showed high-density Airbnb zones.
Power BI Dashboard Description

The Power BI dashboard provides interactive visual analytics using charts, KPI cards, slicers, maps, and graphs.

Dashboard Components
KPI Cards

The top section contains summary metrics including:

Total Listings
Total Hosts
Maximum Minimum Nights
Average Minimum Nights
Count of Room Types

These KPIs provide a quick overview of the Airbnb market.

Visualizations Included
1. Sum of Reviews by Listing Name
Visualization Type

Horizontal Bar Chart

Purpose

Shows listings with the highest review counts.

Insight

Highly reviewed properties indicate customer popularity and strong engagement.

2. Sum of Price by Comfort Type
Visualization Type

Area/Line Chart

Categories
Luxurious
Non-luxurious
Insight

Non-luxurious properties generated a larger total price contribution because of higher listing volume.

3. Room Type Count by Nights Defined
Visualization Type

Stacked Column Chart

Purpose

Compares room type frequencies based on stay duration categories.

Insight

Most bookings were concentrated in the 1–2 night category.

4. Geographic Property Mapping
Visualization Type

Map Visualization

Purpose

Displays Airbnb listing locations using latitude and longitude.

Insight

Properties were densely clustered in popular neighbourhoods.

5. Average Price by Room Type
Visualization Type

Bar Chart

Insight
Hotel rooms had the highest average prices.
Shared rooms had the lowest average prices.
6. Sum of Price by Neighbourhood
Visualization Type

Line Chart

Purpose

Compares neighbourhood revenue contribution.

Insight

Certain neighbourhoods generated significantly higher total revenue.

7. Room Type Distribution
Visualization Type

Pie Chart

Insight

Entire home/apartment listings accounted for nearly 90% of the total listings.

Advanced Analysis Features
Luxury Property Detection

Listings were categorized into:

Luxurious
Non-luxurious

based on pricing and amenities.

This segmentation helped analyze:

Premium market trends
Revenue contribution
Customer demand patterns
Business Insights Generated
Key Findings
Market Dominance

Entire homes dominate Airbnb inventory and revenue generation.

Premium Listings

Luxury properties with amenities like:

Hot tubs
Saunas
Mountain views
Game rooms

were priced significantly higher.

Geographic Trends

Listings were concentrated in highly populated tourist regions.

Customer Preferences

Short stays (1–2 nights) were the most common booking pattern.

Revenue Insights

Neighbourhood-specific analysis identified premium revenue zones.

Use Cases of the Project

This project can be useful for:

Airbnb market analysis
Pricing strategy optimization
Tourism trend analysis
Real estate investment decisions
Customer behavior analysis
Business intelligence reporting
Conclusion

The Airbnb Data Analysis project successfully combines Python-based data processing with Power BI interactive visualization to uncover meaningful insights from Airbnb listings. The project demonstrates strong skills in:

Data cleaning
Exploratory data analysis
Data visualization
Dashboard creation
Business insight generation

The dashboard enables users to easily explore Airbnb pricing patterns, room distribution, customer engagement, and neighbourhood performance through visually interactive reports.
