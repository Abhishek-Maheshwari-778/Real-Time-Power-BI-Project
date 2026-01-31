# Real-Time Power BI Project: Uber Analysis

<div align="center">
  <img src="deshbord_images/1.png" alt="Dashboard Overview" width="100%">
</div>

## Project Overview
This repository hosts a comprehensive **Uber Data Analysis** project built with **Microsoft Power BI**. Designed for data analysts, business intelligence professionals, and urban planners, this dashboard transforms raw trip data into actionable insights.

It solves the challenge of understanding complex trip patterns by visualizing key metrics like pickup/drop-off densities, trip durations, and revenue generation in a sleek, interactive interface.

> **Note**: This project was built for educational purposes following a "Watch and Make" YouTube tutorial. It serves as a practical implementation of real-time data analysis techniques.

## Dashboard Highlights
<div align="center" style="display: flex; justify-content: space-between;">
  <img src="deshbord_images/2.png" alt="Trip Analysis" width="48%">
  <img src="deshbord_images/3.png" alt="Revenue Analysis" width="48%">
</div>

## Key Features
- **Interactive Dashboard**: A fully dynamic `.pbix` report allowing deep-dives into specific timeframes and locations.
- **Geospatial Intelligence**: Visual maps tracking Pick-up and Drop-off hotspots to identify high-demand zones.
- **Revenue Analysis**: Detailed breakdown of fares, dissecting revenue by vehicle type (SUV, Sedan, etc.) and time of day.
- **Operational KPIs**: Real-time tracking of Total Trips, Average Wait Times, Trip Durations, and Earnings per Mile.

## Technical Architecture
The analysis is built on a robust data modeling foundation within Power BI.

```plaintext
├── data/
│   ├── Uber Trip Details.xlsx  # Raw Trip Data (Time, Fare, Distance)
│   └── Location Table.xlsx     # Geospatial Reference Data
├── assets/
│   ├── Images/                 # Icons & Assets
│   └── dashboard_images/       # Screenshots
├── ok.pbix                     # Main Power BI Report File
└── README.md                   # Project Documentation
```

## Whom It Is For
1.  **Data Analysts**: Explore techniques for data cleaning, modeling, and DAX calculations.
2.  **Transport Managers**: Understand peak hours and optimize fleet allocation.
3.  **Students**: A perfect reference for end-to-end Power BI project execution.

## Contributing
Contributions are welcome. If you have suggestions for better visuals or optimized DAX measures:
1.  Fork the repository.
2.  Create a feature branch.
3.  Commit your changes.
4.  Push to the branch.
5.  Open a Pull Request.

## Author
**Abhishek Maheshwari**
Data Scientist | Analyst

## Support
If you find this analysis useful or inspiring, please give it a star.
