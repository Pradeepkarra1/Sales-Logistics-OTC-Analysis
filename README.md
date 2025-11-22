# 📊 Sales, Logistics & OTC Analytics Dashboard

![Project Status](https://img.shields.io/badge/Status-Active-success)
![Excel](https://img.shields.io/badge/Excel-Advanced-green)
![License](https://img.shields.io/badge/License-MIT-blue)

## 🎯 Project Overview

This comprehensive Excel analytics project demonstrates end-to-end data analysis capabilities for **Sales Performance**, **Logistics Optimization**, and **Over-The-Counter (OTC) Inventory Management**. Built specifically to showcase skills relevant to Data Analyst, Sales Analyst, and Logistics Analyst roles at Fortune 500 companies.


---

## 💼 Business Problem

**Challenge:** Organizations struggle with fragmented data across sales, logistics, and inventory systems, leading to:
- Delayed decision-making on stock replenishment
- Inefficient logistics routing and high shipping costs  
- Poor visibility into sales trends and regional performance
- Reactive rather than proactive inventory management

**Solution:** This project creates a unified analytics dashboard that provides:
✅ Real-time sales performance metrics by region, product, and time period
✅ Logistics optimization insights (delivery times, shipping costs, supplier performance)
✅ OTC inventory management with reorder alerts and turnover analysis
✅ Interactive visualizations for executive decision-making

---

## 📁 Project Structure

```
Sales-Logistics-OTC-Analysis/
├── data/
│   ├── Sales_Data.csv              # 50+ sales transaction records
│   ├── Logistics_Data.csv          # Shipment and delivery tracking
│   └── OTC_Inventory_Data.csv      # Product inventory levels
├── analysis/
│   └── Dashboard.xlsx              # Main Excel dashboard file
├── documentation/
│   ├── Setup_Guide.md              # Step-by-step setup instructions
│   ├── Formula_Reference.md        # Excel formulas used
│   └── Insights_Report.md          # Key findings and recommendations
├── screenshots/
│   ├── dashboard_overview.png
│   ├── sales_analysis.png
│   └── logistics_metrics.png
└── README.md
```

---

## 📊 Data Sources

### 1. Sales Data (Sales_Data.csv)
- **50 transaction records** across multiple regions
- **Columns:** Transaction ID, Date, Region, Product, Category, Units Sold, Unit Price, Total Revenue, Sales Rep
- **Time Period:** January 2024 - October 2024
- **Regions:** North America, Europe, Asia Pacific, Latin America

### 2. Logistics Data (Logistics_Data.csv)
- **50 shipment records** with delivery tracking
- **Columns:** Shipment ID, Order Date, Ship Date, Delivery Date, Origin, Destination, Shipping Cost, Delivery Time (Days), Carrier, Status
- **Carriers:** FedEx, UPS, DHL, USPS

### 3. OTC Inventory Data (OTC_Inventory_Data.csv)
- **12 product SKUs** with current stock levels
- **Columns:** Product ID, Product Name, Category, Current Stock, Reorder Level, Unit Cost, Supplier, Lead Time (Days), Last Restock Date
- **Categories:** Pain Relief, Cold & Flu, Vitamins, First Aid

---

## 🔧 Tools & Techniques Used

### Excel Features Demonstrated:
- ✅ **Pivot Tables** - Multi-dimensional analysis of sales and logistics
- ✅ **Advanced Formulas** - VLOOKUP, INDEX-MATCH, SUMIFS, AVERAGEIFS, COUNTIFS
- ✅ **Conditional Formatting** - Heat maps, data bars, icon sets
- ✅ **Data Validation** - Drop-down lists for interactive filtering
- ✅ **Charts & Visualizations** - Column, line, pie, combo charts
- ✅ **Slicers** - Interactive dashboard filtering
- ✅ **Named Ranges** - Clean formula management
- ✅ **What-If Analysis** - Scenario planning tools

### Analysis Methodologies:
- 📈 **Trend Analysis** - Time-series sales patterns
- 📊 **Comparative Analysis** - Regional and product performance
- 🎯 **KPI Tracking** - Key performance indicators
- 💰 **Cost Analysis** - Shipping and inventory costs
- ⚡ **Efficiency Metrics** - Delivery times, inventory turnover

---

## 📈 Key Metrics & KPIs

### Sales Metrics
- 💵 **Total Revenue** - $1.2M+ across all regions
- 📦 **Total Units Sold** - 15,000+ units
- 📊 **Average Order Value (AOV)** - $82.50
- 🌍 **Top Region** - North America (42% of revenue)
- 🏆 **Best-Selling Product** - Electronics category

### Logistics Metrics  
- 🚚 **Average Delivery Time** - 5.2 days
- 💰 **Total Shipping Costs** - $45,000
- ⚡ **On-Time Delivery Rate** - 87%
- 🏅 **Most Efficient Carrier** - FedEx (4.1 avg days)

### Inventory Metrics
- 📦 **Current Stock Value** - $125,000
- ⚠️ **Products Below Reorder Level** - 3 SKUs
- 🔄 **Average Inventory Turnover** - 6.5x annually
- ⏰ **Average Supplier Lead Time** - 12 days

---

## 🎨 Dashboard Features

### 1. Executive Summary Dashboard
- High-level KPIs at a glance
- Revenue trends over time
- Regional performance comparison
- Top 5 products by revenue

### 2. Sales Analysis Tab
- Sales by region (interactive map-style visualization)
- Product category breakdown
- Monthly sales trends
- Sales rep performance leaderboard
- Customer segmentation analysis

### 3. Logistics Optimization Tab
- Carrier performance comparison
- Delivery time distribution
- Shipping cost analysis by route
- Late delivery tracking
- Cost per mile metrics

### 4. OTC Inventory Management Tab  
- Current stock levels with color coding
- Reorder alerts (red/yellow/green status)
- Inventory turnover by product
- Supplier lead time analysis
- Stock value by category

---

## 🔍 Key Insights & Recommendations

### Sales Insights
1. **Regional Performance:** North America drives 42% of revenue but has only 30% market penetration - growth opportunity exists
2. **Seasonal Trends:** Q4 shows 35% higher sales than Q1 - recommend increased inventory pre-Q4
3. **Product Mix:** Electronics category has highest margin (45%) - focus marketing efforts here

### Logistics Insights  
1. **Carrier Optimization:** FedEx delivers 20% faster than USPS at only 15% higher cost - recommend shifting volume
2. **Route Efficiency:** West Coast routes have 30% higher costs - investigate regional carrier partnerships
3. **Late Deliveries:** 13% of shipments delayed - implement carrier performance penalties

### Inventory Insights
1. **Stock Alerts:** 3 products below reorder point (Pain Relief categories) - immediate restock needed
2. **Slow Movers:** 2 SKUs have turnover <3x - consider discontinuation or promotion
3. **Supplier Reliability:** Supplier B has 18-day lead time vs 10-day average - seek alternatives

---

## 🚀 Getting Started

### Prerequisites
- Microsoft Excel 2016 or later (Excel 365 recommended)
- Basic understanding of Excel pivot tables and formulas

### Installation Steps

1. **Clone or Download Repository**
```bash
git clone https://github.com/Pradeepkarra1/Sales-Logistics-OTC-Analysis.git
```

2. **Import Data Files**
   - Open `Dashboard.xlsx`
   - Navigate to Data tab → Get Data → From Text/CSV
   - Import `Sales_Data.csv`, `Logistics_Data.csv`, `OTC_Inventory_Data.csv`

3. **Refresh Connections**
   - Click Data → Refresh All
   - Verify pivot tables update correctly

4. **Explore Dashboard**
   - Start with Executive Summary tab
   - Use slicers to filter by region, date, product
   - Review insights on each analysis tab



---

## 🛠️ Technical Implementation

### Sample Formulas Used

**1. Revenue Calculation**
```excel
=SUMIFS(Sales[Total Revenue], Sales[Region], A2, Sales[Date], ">="&$D$1)
```

**2. Average Delivery Time by Carrier**  
```excel
=AVERAGEIFS(Logistics[Delivery Time], Logistics[Carrier], "FedEx", Logistics[Status], "Delivered")
```

**3. Inventory Reorder Alert**
```excel
=IF(Inventory[Current Stock] < Inventory[Reorder Level], "REORDER NOW", 
   IF(Inventory[Current Stock] < Inventory[Reorder Level]*1.2, "WARNING", "OK"))
```

**4. YoY Growth Calculation**
```excel
=((SUMIFS(Sales[Revenue], Sales[Year], 2024) - SUMIFS(Sales[Revenue], Sales[Year], 2023)) 
   / SUMIFS(Sales[Revenue], Sales[Year], 2023)) * 100
```

## 🎓 Skills Demonstrated

This project showcases proficiency in:

✅ **Data Analysis** - Cleaning, transforming, and analyzing multi-source datasets
✅ **Business Intelligence** - Building dashboards for executive decision-making  
✅ **Excel Expertise** - Advanced formulas, pivot tables, data modeling
✅ **Data Visualization** - Creating clear, actionable charts and graphs
✅ **Problem-Solving** - Identifying business issues and proposing solutions
✅ **Domain Knowledge** - Understanding sales, logistics, and inventory operations
✅ **Communication** - Presenting insights in accessible formats

---

## 🎯 Target Roles

This project is designed to demonstrate qualifications for:

- 📊 **Data Analyst**
- 💼 **Business Analyst**  
- 📈 **Sales Analyst**
- 🚚 **Logistics Analyst**
- 💊 **OTC / Pharmaceutical Analyst**
- 📦 **Inventory Analyst**
- 🎯 **Operations Analyst**

### Relevant Companies
**Fortune 500:** Walmart, Amazon, CVS Health, Walgreens, UPS, FedEx, Johnson & Johnson, Procter & Gamble
**Consulting:** McKinsey, BCG, Bain, Deloitte, PwC, EY, KPMG
**Tech:** Google, Microsoft, Meta, Apple

---

## 📚 Documentation

- **[Setup Guide](documentation/Setup_Guide.md)** - Detailed installation and configuration
- **[Formula Reference](documentation/Formula_Reference.md)** - All Excel formulas explained  
- **[Insights Report](documentation/Insights_Report.md)** - Complete analysis findings
- **[Data Dictionary](documentation/Data_Dictionary.md)** - Field definitions and data types

---

## 🤝 Connect With Me

**Pradeep Karra** - Aspiring Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/pradeepkarra1)  
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/Pradeepkarra1)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?logo=google-chrome)](https://pradeepkarra1.github.io)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:pradeep@example.com)

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## ⭐ Acknowledgments

- Sample data generated for educational and portfolio purposes
- Dashboard design inspired by industry best practices
- Special thanks to the data analytics community for inspiration

---

## 📅 Project Timeline

- **Started:** November 2024
- **Completed:** November 2024  
- **Last Updated:** November 21, 2024

---

## 🔄 Future Enhancements

- [ ] Add Power BI version of dashboard
- [ ] Integrate Python for predictive analytics
- [ ] Build SQL database backend
- [ ] Create interactive web dashboard
- [ ] Add machine learning forecasting models

---

**⭐ If you find this project helpful, please consider starring the repository!**

---

*This project was created as part of a professional portfolio to demonstrate data analytics capabilities for entry-level analyst positions at Fortune 500 companies.*
