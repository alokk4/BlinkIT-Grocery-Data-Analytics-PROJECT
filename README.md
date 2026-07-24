# 🛒 BlinkIT Grocery Sales Dashboard

An interactive **Power BI dashboard** designed to analyze BlinkIT grocery sales performance, outlet efficiency, product categories, and customer preferences. This project demonstrates data cleaning, DAX calculations, KPI creation, and interactive visualizations to support business decision-making.

---

## 📌 Project Overview

The BlinkIT Grocery Sales Dashboard provides insights into sales performance across different outlet types, outlet sizes, city tiers, and product categories. It enables business users to monitor key performance indicators (KPIs), identify sales trends, and make data-driven decisions through interactive dashboards.

---

## 🎯 Business Objective

The objective of this project is to help management answer key business questions such as:

- Which outlet type generates the highest sales?
- Which city tier contributes the most revenue?
- Which product categories perform the best?
- How do outlet size and establishment year affect sales?
- What are customer preferences for Low Fat and Regular products?

---

## 📂 Dataset Information

- **Dataset:** BlinkIT Grocery Data
- **Records:** 8,523
- **Format:** Microsoft Excel (.xlsx)

### Dataset Features

- Item Identifier
- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Sales
- Rating
- Outlet Identifier
- Outlet Establishment Year
- Outlet Size
- Outlet Location Type
- Outlet Type

---

## 📊 Dashboard Features

### Key Performance Indicators (KPIs)

- 💰 Total Sales
- 💵 Average Sales
- ⭐ Average Rating
- 📦 Total Number of Items

### Visualizations

- KPI Cards
- Area Chart (Outlet Establishment Trend)
- Donut Charts
- Bar Charts
- Matrix/Table
- Interactive Slicers

### Interactive Filters

- Outlet Location Type
- Outlet Size
- Item Type

---

## 📈 Key Insights

- Compare sales across different outlet types.
- Analyze sales by outlet location (Tier 1, Tier 2, Tier 3).
- Identify top-performing product categories.
- Compare customer preference for Low Fat and Regular products.
- Evaluate outlet performance based on size and establishment year.
- Monitor customer ratings and product visibility.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel**

---

## 📐 DAX Measures Used

```DAX
Total Sales = SUM('BlinkIT Grocery Data'[Sales])

Average Sales = AVERAGE('BlinkIT Grocery Data'[Sales])

Average Rating = AVERAGE('BlinkIT Grocery Data'[Rating])

Number of Items = COUNTROWS('BlinkIT Grocery Data')
```

---

## 📷 Dashboard Preview

> Add a screenshot of your dashboard here.

Example:

```
images/dashboard.png
```

---

## 📁 Repository Structure

```
BlinkIT-Grocery-Sales-Dashboard/
│
├── Dashboard/
│   └── BlinkIT Dashboard.pbix
│
├── Dataset/
│   └── BlinkIT Grocery Data.xlsx
│
├── Images/
│   └── Dashboard.png
│
└── README.md
```

---

## 🚀 How to Use

1. Clone this repository.
2. Download the Power BI (.pbix) file.
3. Open the project in **Power BI Desktop**.
4. Use the slicers to explore sales by outlet, product category, and location.

---

## 💼 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Measures
- Power Query
- Dashboard Design
- Business Intelligence
- Data Visualization
- KPI Development
- Business Storytelling

---

## 🔮 Future Improvements

- Dynamic Titles
- Drill-through Pages
- Tooltip Pages
- Time Intelligence Analysis
- Mobile Layout
- Performance Optimization

---

## 👨‍💻 Author

**Alok Kumar**

Aspiring Data Analyst passionate about transforming raw data into actionable business insights using **Power BI, SQL, Excel, and Python**.

- GitHub: https://github.com/your-username
- LinkedIn: https://linkedin.com/in/your-profile
- Email: your-email@example.com

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
