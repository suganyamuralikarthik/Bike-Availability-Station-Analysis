# Bike Availability & Station Analysis

**Created by – D SUGANYA**

## Project Overview

The **Bike Availability & Station Analysis Dashboard** is an interactive Business Intelligence solution developed using **Power BI** to analyze the performance of public bike-sharing stations across multiple cities. The dashboard provides insights into bike availability, station capacity, operational status, and geographic distribution, enabling stakeholders to optimize bike allocation and improve operational efficiency.

## Project Objectives

* Monitor bike availability across all stations.
* Analyze station operational status (Open vs Closed).
* Compare available bikes with total bike stand capacity.
* Identify top-performing and low-performing cities.
* Visualize bike station locations using an interactive map.
* Support data-driven decision-making for bike-sharing operations.

## Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Data Visualization

## Dataset Information

The dataset contains detailed information about bike-sharing stations across multiple cities.

### Dataset Columns

* Station Number
* Station Name
* Contract Name (City)
* Address
* Latitude
* Longitude
* Bike Stands
* Available Bikes
* Available Bike Stands
* Station Status
* Bonus

## Data Cleaning & Transformation

The dataset was cleaned and transformed using **Power Query**.

### Data Preparation Steps

* Removed duplicate records.
* Handled missing and null values.
* Corrected data types.
* Standardized column names.
* Removed unnecessary columns.
* Validated station status values.
* Extracted Latitude & Longitude from the Position column.
* Prepared latitude and longitude for map visualization.
* Optimized the dataset for reporting and analysis.

## Data Modeling

A structured Power BI data model was created to improve report performance.

### Measures Created

* Total Bike Stations
* Total Bike Stands
* Total Available Bikes
* Total Available Bike Stands
* Open Stations
* Closed Stations
* Bike Availability %

## Dashboard KPIs

| KPI                   |  Value |
| --------------------- | -----: |
| Total Bike Stations   |  3,078 |
| Total Bike Stands     | 57,203 |
| Available Bikes       | 19,646 |
| Available Bike Stands | 32,157 |
| Open Stations         |  2,872 |
| Closed Stations       |    206 |
| Bike Availability     | 34.34% |

## Dashboard Features

* KPI Cards
* Contract-wise Bike Availability Analysis
* Bike Stands vs Available Bikes Comparison
* Station Status Distribution
* Interactive Geographic Map
* Contract-wise Summary Table
* Dynamic Filters and Slicers

## Key Insights

* The network has **3,078 stations** with **19,646 available bikes**.
* **93.31% of stations are operational**, while **6.69% are closed**.
* Overall bike availability stands at **34.34%**.
* **Bruxelles-Capitale** has the highest bike availability and station capacity.
* **Lyon and Dublin** also show strong bike availability.
* **99.44% of stations are Non-Bonus Stations**, while only **0.56% are Bonus Stations**.
* The interactive map provides a clear view of station distribution across cities.
* The dashboard helps identify low-availability areas for better bike redistribution.

## Business Insights

* The network includes **3,078 stations** with **57,203 bike stands** and **19,646 available bikes**.
* **93.31% of stations are operational**, while **6.69% are closed**, highlighting an opportunity to improve service coverage.
* The overall **Bike Availability Rate is 34.34%**, indicating that bike availability should be monitored during high-demand periods.
* **Bruxelles-Capitale** has the highest station capacity with **8,592 bike stands** and **3,532 available bikes**.
* **Dublin** also shows strong performance with **3,668 bike stands** and **1,241 available bikes**.
* Around **56.22% of bike stands are vacant**, creating opportunities for better bike redistribution.
* Only **0.56% of stations are Bonus Stations**, suggesting potential for expansion in high-traffic locations.
* Regular monitoring and redistribution can help reduce bike shortages and improve operational efficiency.

## Business Recommendations

* Increase bike allocation in high-demand cities such as **Bruxelles-Capitale and Dublin**.
* Reopen or investigate the **206 closed stations**.
* Redistribute bikes from stations with excess capacity to areas with low availability.
* Expand Bonus Stations in high-traffic locations.
* Continuously monitor station utilization and bike availability.

## Business Benefits

* Improves visibility into bike-sharing operations.
* Supports efficient bike redistribution.
* Enhances station performance monitoring.
* Helps reduce bike shortages.
* Enables data-driven operational planning.
* Improves customer satisfaction through better bike availability.

## Future Enhancements

* Integrate real-time bike availability APIs.
* Develop demand forecasting using machine learning.
* Add hourly and daily trend analysis.
* Include weather impact on bike usage.

## Conclusion

The **Bike Availability & Station Analysis Dashboard** transforms raw operational data into meaningful business insights through interactive Power BI visualizations. By analyzing **3,078 stations, 57,203 bike stands, and 19,646 available bikes**, the dashboard provides a clear understanding of station utilization, operational status, and bike distribution.

With a **34.34% bike availability rate** and **93.31% operational stations**, the solution supports informed decision-making, efficient resource allocation, and improved bike-sharing services. It demonstrates practical skills in **Power BI, Power Query, DAX, data modeling, and Business Intelligence**, making it a strong portfolio project for data analytics roles.
