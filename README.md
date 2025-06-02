# Airline Delay Cause Analysis

This project analyzes the factors contributing to airline delays using historical flight data. By examining delay causes across different carriers and airports, the study aims to provide actionable insights for airline management and operational improvements.

## 📊 Project Overview

Flight delays have significant operational and financial impacts on the aviation industry. Understanding the underlying causes of delays can help airlines optimize scheduling, improve resource allocation, and enhance passenger experience.

This project focuses on:
- Identifying key factors contributing to delays (e.g., carrier delays, weather, NAS issues, security).
- Visualizing delay patterns across time, carriers, and airports.
- Providing data-driven insights for mitigating delays.

## 🔍 Dataset

The dataset used in this project is `Dataset_Airline_Delay_Cause.csv`, sourced from the U.S. Bureau of Transportation Statistics (BTS). It contains records of flight delay causes with features including:

- **Carrier**: Airline identifier.
- **Origin**: Departure airport.
- **Dest**: Arrival airport.
- **Month**: Month of the flight.
- **ArrDelay**: Arrival delay in minutes.
- **CarrierDelay**: Delay due to carrier issues.
- **WeatherDelay**: Delay due to weather.
- **NASDelay**: Delay due to National Aviation System.
- **SecurityDelay**: Delay due to security issues.
- **LateAircraftDelay**: Delay due to late-arriving aircraft.

A detailed data dictionary is available in `Download_Column_Definitions.xlsx`.

## 🧰 Methods and Workflow

1. **Data Cleaning and Preprocessing**
   - Removed rows with missing or invalid entries.
   - Converted relevant columns to appropriate data types.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed delay distributions by month, carrier, and airport.
   - Identified top airports and airlines contributing to delays.
   - Visualized delay trends using bar plots, heatmaps, and time series charts.

3. **Key Insights**
   - Carrier-related delays and weather delays show distinct seasonal patterns.
   - Certain airports exhibit consistently higher delay rates, indicating potential operational bottlenecks.
   - The proportion of delays varies significantly across carriers, suggesting differing levels of operational efficiency.

## 📈 Sample Visualizations

- Bar charts of average delays by carrier.
- Heatmaps of delay distributions by month and airport.
- Pie charts illustrating delay cause breakdowns.
