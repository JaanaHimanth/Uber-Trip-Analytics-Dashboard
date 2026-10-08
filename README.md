# Uber Trip Analysis | Power BI Dashboard

## Executive Summary

An interactive Power BI dashboard analyzing **103.73K Uber bookings** across booking performance, revenue metrics, ride timings, location distribution, payment methods, and vehicle performance.

The objective of this project is to analyze Uber trip data and generate meaningful insights into booking trends, revenue generation, trip efficiency, and customer travel patterns to support data-driven decision-making.

## Key Metrics & Insights

- **Total Bookings:** 103.73K rides generating **$1.6M** in total booking value.
- **Average Trip Metrics:** Average booking value of **$15.0**, average trip distance of **3 miles**, and average trip duration of **16 minutes**.
- **Payment Distribution:** **Uber Pay** accounts for **67.03%** of bookings, followed by **Cash at 32.23%**.
- **Day vs. Night Rides:** Daytime rides account for **72.8%** of bookings, compared with **27.2%** during nighttime.
- **Vehicle Performance:** **UberX** leads demand with **38,744 bookings** and **$583,880** in total booking value, followed by Uber Comfort with **$253,995**.
- **Peak Demand:** Weekend days, particularly **Saturday and Sunday**, show high booking activity, with significant pickup activity concentrated around mid-day to late afternoon.

## Dashboard Screenshots

### 1. Overview Analysis
![Overview Analysis](overview-analysis.png.png)

### 2. Time Analysis
![Time Analysis](time-analysis.png.png)

### 3. Detailed Records
![Details Analysis](details-analysis.png.png)

## Technical Features

### DAX Measures
- KPI calculations
- Total bookings
- Total booking value
- Average booking value
- Average trip distance
- Average trip duration
- Custom time-based calculations

### Interactive Slicers
- Date filters
- City/location filters
- Dynamic data exploration

### Dashboard Navigation
- Overview Analysis
- Time Analysis
- Detailed Records

### Data Analysis
- Vehicle type comparison
- Payment type analysis
- Day vs. night analysis
- Booking trends
- Location analysis
- Trip distance and duration analysis

## Dashboard Pages

### Overview Analysis

Provides a high-level view of booking performance, revenue, trip distance, trip duration, payment methods, and vehicle performance.

### Time Analysis

Analyzes booking activity across different time periods to identify peak and off-peak demand patterns.

### Details

Provides detailed booking-level records and allows users to explore the underlying data.

## Tools & Technologies

- **Power BI**
- **DAX**
- **Power Query**
- **Data Cleaning & Transformation**
- **Data Visualization**
- **Business Data Analysis**

## Project Structure

```text
Uber-Trip-Analysis-PowerBI/
│
├── README.md
│
├── PowerBI/
│   └── Uber_Trip_Analysis_Dashboard.pbix
│
├── Screenshots/
│   ├── overview-analysis.png
│   ├── time-analysis.png
│   └── details-analysis.png
│
└── Dataset/
    └── uber_trip_data.csv
```

## How to View

1. Download the [Uber_Data.pbix](Uber_Data.pbix) file.
2. Open using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Interact with the dashboard using the available slicers, filters, and navigation controls.

## Author

**Jaana Himanth**

