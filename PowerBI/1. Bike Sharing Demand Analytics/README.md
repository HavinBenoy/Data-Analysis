# Bike Sharing Demand Analytics – Power BI

## Project Overview

This project analyzes bike-sharing rental demand using Power BI.

The dashboard explores how bike rental demand varies across:

- Time and date
- Hours of the day
- Seasons
- Weather conditions
- Working and non-working days
- Registered and casual users
- Year-over-year performance

The project demonstrates data cleaning, data modeling, DAX calculations, time intelligence, and interactive dashboard development in Power BI.

---

## Project Objective

The main objective of this project is to analyze bike rental patterns and identify the major factors influencing bike-sharing demand.

### Key Questions

- What is the total number of bike rentals?
- How does rental demand change over time?
- Which hours have the highest rental demand?
- How does demand vary across seasons?
- How does weather affect rentals?
- How do registered and casual users contribute to total rentals?
- How does rental demand compare between years?
- How does cumulative rental performance progress throughout the year?

---

## Dataset

The project uses the **UCI Bike Sharing Dataset**.

The dataset contains hourly bike rental information from the Capital Bikeshare system for the years 2011 and 2012.

### Main attributes

- Date
- Hour
- Season
- Weather
- Working Day
- Holiday
- Temperature
- Humidity
- Wind Speed
- Casual Rentals
- Registered Rentals
- Total Rentals

### Dataset Source

UCI Machine Learning Repository:

https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset

DOI: 10.24432/C5W894

---

## Dashboard

The Power BI dashboard contains:

### KPIs

- Total Rentals
- Total Registered Rentals
- Total Casual Rentals
- Average Daily Rentals
- YoY Growth %

### Visualizations

- Rental Demand Trend
- Rental Demand by Hour
- Monthly Rentals: Current vs Previous Year
- Rental Demand by Season
- Rental Demand by Weather
- Cumulative YTD Rentals

### Filters

- Month
- Season
- Weather
- Working Day

---

## Data Model

The project uses a simple star-schema-based data model consisting of:

- Fact Bike Rentals
- Calendar/Date Dimension
- Supporting dimensions where required

The conceptual and physical data models are available in the **Data models** folder.

---

## DAX Concepts Used

The project demonstrates:

- Aggregation using `SUM`
- Iterators using `AVERAGEX`
- `CALCULATE`
- Filter context
- Evaluation context
- Time intelligence
- `SAMEPERIODLASTYEAR`
- `TOTALYTD`
- `DIVIDE`

---

## Repository Structure

```text
1.Bike-Sharing-Demand-Analytics/
│
├── Raw Dataset/
│   ├── hour.csv
│   ├── bike+sharing+dataset.zip
│   └── bike+sharing+dataset/
│
├── Dashboard Preview/
│   └── dashboard_preview.png
│   
│
├── Data models/
│   ├── 1. conceptual_model.png
│   └── 2. Physical_model.png
│
├── Power BI/
│   └── Bike_Sharing_Demand_Analytics.pbix
│
├── Documentation.pdf
└── README.md
