<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Uber%20Analytics%20Dashboard&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32" width="100%"/>

<img src="deshbord_images/1.png" alt="Dashboard Preview" width="95%" style="border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);"/>

<br/>

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/excel)
[![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://dax.guide/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<h3>🚖 Real-Time Data Analysis | 📊 Interactive Visualizations | 💰 Revenue Insights</h3>

**[📂 View Project](#-project-overview) • [🎯 Features](#-what-makes-this-special) • [🚀 Get Started](#-quick-start) • [📸 Gallery](#-dashboard-gallery)**

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 📌 Project Overview

<img align="right" alt="Analytics" width="400" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif">

This repository showcases a **comprehensive Uber trip data analysis** built entirely in **Microsoft Power BI**. The project transforms raw transportation data into stunning, actionable insights through interactive dashboards and advanced DAX calculations.

### 🎓 Learning Journey

> **Note**: This project was built for educational purposes. I learned and developed this dashboard by following a "Watch and Make" YouTube tutorial on real-time data analysis, applying best practices in business intelligence and data visualization.

### 🎯 Problem Statement

Urban mobility companies generate massive amounts of data daily. This project addresses:
- Understanding trip patterns and peak demand hours
- Identifying high-revenue zones and vehicle performance
- Optimizing fleet allocation based on geospatial insights
- Tracking operational KPIs in real-time

<br clear="right"/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## ✨ What Makes This Special?

<div align="center">

| 🗺️ **Geospatial Analysis** | 💰 **Revenue Intelligence** | ⚡ **Real-Time KPIs** | 📈 **Trend Analysis** |
|:---:|:---:|:---:|:---:|
| Interactive maps showing pickup/dropoff hotspots | Revenue breakdown by vehicle type & time | Live tracking of trips, fares & distances | Historical patterns & forecasting |

</div>

### 🔥 Key Features

```diff
+ Interactive Dashboard with drill-down capabilities
+ Geospatial Intelligence for demand zone identification
+ Revenue Analysis by vehicle type (SUV, Sedan, etc.)
+ Operational KPIs: Total Trips, Wait Times, Trip Duration
+ Time-based Analysis: Peak hours, daily/weekly trends
+ Location Performance: Top pickup/dropoff locations
+ Professional UI/UX with custom visuals and icons
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 📸 Dashboard Gallery

<div align="center">

<table>
<tr>
<td width="50%">
<img src="deshbord_images/2.png" alt="Trip Analysis" width="100%" style="border-radius: 10px;"/>
<h4>📊 Trip Analysis View</h4>
<p>Comprehensive breakdown of trip metrics, distances, and durations with interactive filters</p>
</td>
<td width="50%">
<img src="deshbord_images/3.png" alt="Revenue Dashboard" width="100%" style="border-radius: 10px;"/>
<h4>💵 Revenue Dashboard</h4>
<p>Financial insights with fare analysis, earnings per mile, and payment method distribution</p>
</td>
</tr>
<tr>
<td colspan="2">
<img src="deshbord_images/4.png" alt="Geospatial View" width="100%" style="border-radius: 10px;"/>
<h4>🗺️ Geospatial Intelligence</h4>
<p>Map-based visualization showing demand hotspots and route optimization opportunities</p>
</td>
</tr>
</table>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🛠️ Technical Architecture

<div align="center">

```mermaid
graph LR
    A[Raw Data] --> B[Power Query ETL]
    B --> C[Data Model]
    C --> D[DAX Measures]
    D --> E[Visualizations]
    E --> F[Interactive Dashboard]
    
    style A fill:#ff6b6b
    style B fill:#4ecdc4
    style C fill:#45b7d1
    style D fill:#96ceb4
    style E fill:#ffeaa7
    style F fill:#74b9ff
```

</div>

### 📁 Repository Structure

```plaintext
Real-Time-Power-BI-Project/
│
├── 📊 ok.pbix                          # Main Power BI Report
├── 📂 data/
│   ├── Uber Trip Details.xlsx         # Trip transactions data
│   └── Location Table.xlsx            # Geospatial reference
├── 🎨 Images/                          # Dashboard icons & assets
├── 📸 deshbord_images/                 # Screenshots for docs
├── 📄 documentation/
│   ├── Problem Statement.docx
│   └── Real Time Power BI Project.docx
├── 📝 README.md
└── 📜 LICENSE
```

### 🧮 DAX Measures Implemented

<details>
<summary>Click to expand DAX examples</summary>

- **Total Trips**: `COUNTROWS(Trips)`
- **Total Revenue**: `SUM(Trips[Fare_Amount])`
- **Average Trip Distance**: `AVERAGE(Trips[Trip_Distance])`
- **Revenue per Mile**: `[Total Revenue] / [Total Distance]`
- **Peak Hour Analysis**: Time intelligence functions
- **YoY Growth**: `CALCULATE([Total Trips], SAMEPERIODLASTYEAR(Calendar[Date]))`

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🚀 Quick Start

### Prerequisites

<div align="center">

![Power BI Desktop](https://img.shields.io/badge/Power%20BI%20Desktop-Required-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white)

</div>

### Installation

```bash
# Clone this repository
git clone https://github.com/Abhishek-Maheshwari-778/Real-Time-Power-BI-Project.git

# Navigate to project directory
cd Real-Time-Power-BI-Project

# Open the Power BI file
start ok.pbix
```

### 🎮 Usage

1. **Open Dashboard**: Double-click `ok.pbix` in Power BI Desktop
2. **Explore Visuals**: Use slicers and filters to interact with data
3. **Refresh Data**: Update data sources if paths have changed
4. **Customize**: Modify visuals and DAX measures as needed

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 👥 Who Is This For?

<div align="center">

<table>
<tr>
<td align="center" width="25%">
<img src="https://img.icons8.com/color/96/000000/business-analyst.png" width="80px"/><br/>
<b>Data Analysts</b><br/>
<sub>Learn Power BI best practices</sub>
</td>
<td align="center" width="25%">
<img src="https://img.icons8.com/color/96/000000/manager.png" width="80px"/><br/>
<b>Business Managers</b><br/>
<sub>Make data-driven decisions</sub>
</td>
<td align="center" width="25%">
<img src="https://img.icons8.com/color/96/000000/student-male.png" width="80px"/><br/>
<b>Students</b><br/>
<sub>Portfolio project reference</sub>
</td>
<td align="center" width="25%">
<img src="https://img.icons8.com/color/96/000000/developer.png" width="80px"/><br/>
<b>BI Developers</b><br/>
<sub>Explore DAX techniques</sub>
</td>
</tr>
</table>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 📚 Learning Resources

<div align="center">

[![Power BI Docs](https://img.shields.io/badge/Power%20BI-Documentation-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://docs.microsoft.com/power-bi/)
[![DAX Guide](https://img.shields.io/badge/DAX-Guide-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://dax.guide/)
[![Community](https://img.shields.io/badge/Power%20BI-Community-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://community.powerbi.com/)

</div>

### 📺 Tutorial Credits

This project was built following a comprehensive YouTube tutorial series on real-time Power BI analytics. Special thanks to the creator for the excellent educational content!

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

<div align="center">

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)
[![Contributors](https://img.shields.io/github/contributors/Abhishek-Maheshwari-778/Real-Time-Power-BI-Project?style=for-the-badge)](https://github.com/Abhishek-Maheshwari-778/Real-Time-Power-BI-Project/graphs/contributors)

</div>

### How to Contribute

1. 🍴 Fork the repository
2. 🔨 Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🎉 Open a Pull Request

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

## 👨‍💻 Author

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=F75C7E&center=true&vCenter=true&width=940&lines=Abhishek+Maheshwari;Data+Scientist+%7C+Analyst;Building+Beautiful+Data+Solutions" alt="Typing SVG" />

<br/>

**Abhishek Maheshwari**  
*Data Scientist | Analyst*

A passionate developer focused on creating tools that help the community build better, more beautiful software.

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Abhishek-Maheshwari-778)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://abhishek-maheshwari-778.github.io/Ultimate_GitHub_Profile_Collection_website/)

<br/>

### ⭐ Support This Project

If you find this analysis useful or inspiring, please give it a **star**!  
It helps me create more open-source content.

[![Star This Repo](https://img.shields.io/github/stars/Abhishek-Maheshwari-778/Real-Time-Power-BI-Project?style=social)](https://github.com/Abhishek-Maheshwari-778/Real-Time-Power-BI-Project)

<br/>

**Made with 💜 by Abhishek Maheshwari**

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
