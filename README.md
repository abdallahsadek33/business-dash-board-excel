# 📊 Sales Analysis Dashboard

**A complete Power BI solution with end-to-end data transformation and business intelligence**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-Enabled-blue)

---

## 🎯 Project Overview

This project delivers a comprehensive sales analytics dashboard built on a foundation of properly cleaned and modeled data. It showcases the complete BI workflow from raw data to actionable insights.

**Total Sales**: $2,184,376 | **Total Profit**: $281,178 | **Discounts**: 1493

---

## 📈 Dashboard Highlights

### KPI Cards
- 💰 **Total Sales**: Real-time revenue tracking
- 💵 **Total Profit**: Net profit calculations
- 🎁 **Discounts Applied**: Discount impact analysis

### Visualizations
1. **Region Profits by Categories** - Multi-series column chart comparing product performance across regions
2. **Top 5 Customers** - Customer ranking by sales contribution
3. **Categories Sales Per Years** - Trend analysis showing category growth over time
4. **Sub Categories Profit** - Waterfall chart displaying profit distribution
5. **Top 50 States by Profit** - Geographic performance map with state-level insights

---

## 🧹 Data Preparation

### Cleaning Process

#### 1️⃣ Power Query Transformations
```
✓ Removed duplicate rows
✓ Handled missing values
✓ Standardized data types
✓ Cleaned column headers
✓ Filtered invalid records
✓ Created calculated columns
```

#### 2️⃣ DAX Enhancements
```dax
-- Custom measures for deeper insights
-- Time intelligence calculations
-- Advanced aggregations
-- Dynamic filtering logic
```

#### 3️⃣ Data Modeling
```
✓ Star schema design
✓ Proper relationships between tables
✓ Optimized for performance
✓ Power Pivot integration
```

### Raw Data Structure
The project includes a **Business Data Set** Excel file with:
- **Orders Table**: Transaction-level sales data
- **Return Table**: Product return tracking
- **People Table**: Sales representative information

**Key Fields**: Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Location, State, Postal Code, Region

---

## 🚀 Quick Start

### Installation
```bash
1. Download Power BI Desktop from Microsoft
2. Clone this repository
3. Open the .pbix file in Power BI Desktop
4. Refresh data connections
```

### Data Refresh
```
Home → Refresh
or
Press F5 to reload all data sources
```

---

## 📊 Technical Stack

| Component | Technology |
|-----------|------------|
| Visualization | Power BI Desktop |
| Data Source | Excel Workbook |
| ETL | Power Query |
| Calculations | DAX |
| Data Model | Power Pivot |

---

## 💡 Key Features

### ✅ What Makes This Dashboard Special?

- **Clean Data Foundation**: Every metric is built on properly transformed data
- **Multi-Dimensional Analysis**: Region, Category, State, Customer perspectives
- **Time Intelligence**: Year-over-year comparisons and trend analysis
- **Geographic Insights**: State-level profit mapping
- **Customer Segmentation**: Top performers and segment analysis
- **Discount Impact**: Understand discount effectiveness

### 🎯 Business Questions Answered

```
Q: Which regions and categories drive the most profit?
A: Region Profits by Categories chart

Q: Who are our most valuable customers?
A: Top 5 Customers visualization

Q: How are sales trending by category over time?
A: Categories Sales Per Years line chart

Q: What's the profit breakdown by subcategory?
A: Sub Categories Profit waterfall

Q: Which states generate the highest profits?
A: Top 50 States map visualization
```

---

## 📁 Project Structure

```
sales-analysis-dashboard/
│
├── Dashboard.pbix              # Main Power BI file
├── Raw Data - Business Data Set.xlsx  # Source data
├── README.md                   # This file
└── screenshots/
    ├── dashboard-main.png
    └── data-view.png
```

---

## 🔧 Customization

### Modify Visuals
1. Open .pbix file in Edit mode
2. Select any visualization
3. Adjust fields, filters, or formatting
4. Save changes

### Update Data Source
1. Transform Data → Data Source Settings
2. Browse to new Excel file location
3. Apply → Close & Apply

### Add New Measures
```dax
// Example: Calculate Average Order Value
Avg Order Value = 
DIVIDE(
    [Total Sales],
    DISTINCTCOUNT(Orders[Order ID]),
    0
)
```

---

## 📚 Learning Resources

**Data Cleaning Techniques**
- Power Query M language basics
- Data transformation best practices
- Handling missing and duplicate data

**DAX Fundamentals**
- Calculated columns vs measures
- Filter context and row context
- Time intelligence functions

**Data Modeling**
- Star schema design
- Relationship management
- Performance optimization

---

## 🤝 Contributing

Found an issue or have a suggestion?
1. Open an issue on GitHub
2. Fork the repo and make changes
3. Submit a pull request

---

## 📝 Changelog

**Version 1.0** (Current)
- Initial dashboard release
- Basic KPIs and visualizations
- Complete data cleaning pipeline

**Planned Updates**
- Predictive analytics
- Real-time data connections
- Mobile layout optimization

---

## 📧 Contact

**Project Owner**: [ِAbdallah Sadek]  

---

## ⭐ Support This Project

If you find this dashboard helpful:
- ⭐ Star the repository
- 🔄 Share with your network
- 📝 Provide feedback

---

## 📄 License

MIT License - Free to use for personal and commercial projects

---

<div align="center">

**Built with Power BI, Excel & DAX**

*From Raw Data to Business Insights*

![Views](https://img.shields.io/badge/Dashboard_Views-Professional-success)
![Data Quality](https://img.shields.io/badge/Data_Quality-Validated-brightgreen)

</div>
