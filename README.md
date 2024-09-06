# 📊 Hotel Performance Persual 📊

This repository contains the data, Power BI dashboard, and supporting documentation for the Hotel Performance Analysis Dashboard. The dashboard provides comprehensive insights into hotel performance metrics, including revenue, occupancy, average daily rate, and more, across various properties and timeframes.

## 📋 Table of Contents
- [📊 Data](#data)
- [📂 Data Import](#data-import)
- [🛠️ Data Transformation](#data-transformation)
- [🔍 Data Modeling](#data-modeling)
- [📏 Measure Creation](#measure-creation)
- [📋 Table Creation](#table-creation)
- [🔍 Filters](#filters)
- [📉 Visualizations](#visualizations)
- [💡 Tooltips](#tooltips)
- [📱 Mobile View](#mobile-view)
- [🤝 Contributing](#contributing)
- [📜 License](#license)

## 📊 Data
A total of 1,662,464 data points spread over 4 different datasets have been utilized for this project. The data is connected through Excel or CSV (flat data) files.

## 📂 Data Import
1. Import the folder containing all datasets from the computer into Power BI.
2. After transferring the data, duplicate and convert all binary files (default) to tables by clicking on the binary.

## 🛠️ Data Transformation
1. Use Power Query's Transform Data feature to perform ETL (Extract, Transform, Load), data cleaning, data merging, and data wrangling.

## 🔍 Data Modeling
1. Establish relationships between tables according to the schema.
2. Achieve a star schema for the project, completing the data modeling process.

## 📏 Measure Creation
1. Create columns using DAX (Data Analysis Expressions) such as 'wn' and 'daytype' with specifications provided by the customer.
2. Implement new measures for detailed analysis, including:
   - RevPar (Revenue Per Available Room)
   - ADR (Average Daily Rate)
   - Occupancy
   - DSRN (Daily Sellable Room Nights)
   - Revenue
   - Realization
   - URN (Utilized Room Nights)
   - BRN (Booked Room Nights)
   - Total bookings
   - Successful bookings
   - And many more for level 2 and level 3 analysis

## 📋 Table Creation
1. Create a new table containing property ID, property name, city, revenue, RevPar, occupancy %, ADR, DSRN, DBRN, DURN, Realization %, Cancellation %, and average rating.
2. Implement custom bars (conditional formatting) for better visualization of revenue and average rating.

## 🔍 Filters
1. Create filters by city, room type, and room category, along with month and year filters for specific details for level 2 and level 3 analysis.

## 📉 Visualizations
1. **Field View**:
   - Revenue, RevPar, DSRN, Occupancy %, ADR, Realization
   - Week-on-week changes in data of day type, RevPar, Occupancy %, ADR, Realization %
   - Bar and line chart of Realization % and ADR by booking platform

2. **Pie Chart**:
   - Revenue by each category of room type
   - Trend of key metrics showing total trend of RevPar, ADR, Occupancy %

## 💡 Tooltips
1. Create tooltips showcasing specific trends in revenue, RevPar, DSRN, Occupancy %, ADR, and Realization for each day type, providing key metrics for market analysis.

## 📱 Mobile View
1. Ensure the dashboard is easily accessible from any device by creating a mobile view.

## 🤝 Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.
