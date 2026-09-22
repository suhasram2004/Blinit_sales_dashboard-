# 🛒 BlinkIT Sales  Analysis Dashboard 


## 📊 Project Overview

This project is an interactive **BlinkIT Grocery Sales Analysis Dashboard** developed using **Microsoft Power BI**.

The dashboard analyzes grocery sales data across different product categories, fat-content types, outlet sizes, outlet locations, outlet types, and outlet establishment years.

The objective of the project is to transform raw grocery sales data into an interactive business intelligence dashboard that can be used to understand sales performance and outlet-level trends.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze overall grocery sales performance
* Track key business KPIs
* Analyze sales by item type
* Compare sales based on fat content
* Analyze fat content across different outlets
* Compare outlet sizes
* Analyze outlet location performance
* Analyze outlet establishment trends
* Compare different outlet types
* Provide interactive filtering for business analysis

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Visualization**
* **Data Cleaning**
* **Data Transformation**
* **Business Intelligence**

---

## 📂 Dataset

The dashboard is built using the **BlinkIT Grocery Data** table.

### Main Dataset Columns

| Column                    | Description                       |
| ------------------------- | --------------------------------- |
| Item Identifier           | Unique identifier for each item   |
| Item Fat Content          | Fat-content category of the item  |
| Item Type                 | Category/type of grocery item     |
| Outlet Establishment Year | Year the outlet was established   |
| Outlet Identifier         | Unique outlet identifier          |
| Outlet Location Type      | Location classification of outlet |
| Outlet Size               | Size category of outlet           |
| Outlet Type               | Type/category of outlet           |
| Item Visibility           | Visibility of item in outlet      |
| Item Weight               | Weight of item                    |
| Sales                     | Sales value                       |
| Rating                    | Item/outlet rating                |

---

## 🧹 Data Preparation

Data preparation was performed using **Power Query** and Power BI.

The data preparation process included:

* Reviewing dataset columns
* Checking and preparing data types
* Cleaning categorical data
* Preparing fields for visualization
* Creating an analysis-ready data model
* Creating calculated measures using DAX

---

# 📐 DAX Measures

Four main measures were created for the dashboard.

### Total Sales

```DAX
Total sales =
SUM('BlinkIT Grocery Data'[Sales])
```

### Average Sales

```DAX
Avg sales =
AVERAGE('BlinkIT Grocery Data'[Sales])
```

### Number of Items

```DAX
No of Items =
COUNTROWS('BlinkIT Grocery Data')
```

### Average Rating

```DAX
Avg rating =
AVERAGE('BlinkIT Grocery Data'[Rating])
```

These measures are used in the dashboard KPI section and analytical visuals.

---

# 📈 Dashboard Components

## 1. KPI Cards

The dashboard provides four major KPIs:

* **Total Sales**
* **Average Sales**
* **Number of Items**
* **Average Rating**

These KPIs provide a quick overview of overall business performance.

---

## 2. Fat Content Analysis

A **donut chart** is used to analyze sales based on:

* Low Fat
* Regular

This allows users to compare performance between different fat-content categories.

---

## 3. Fat by Outlet

A **clustered bar chart** analyzes fat-content performance across outlets.

This visualization helps compare how different outlet categories perform for different fat-content types.

---

## 4. Item Type Analysis

A **bar chart** analyzes performance across different grocery item types.

This allows users to compare different product categories and identify variations in their sales contribution.

---

## 5. Outlet Establishment Analysis

A **line chart** analyzes outlet performance based on the **Outlet Establishment Year**.

This provides a view of sales trends across different outlet establishment periods.

---

## 6. Outlet Size Analysis

A **donut chart** analyzes performance based on outlet size.

The dashboard allows comparison between different outlet size categories.

---

## 7. Outlet Location Analysis

A **funnel chart** analyzes performance across different outlet location types.

This provides a visual comparison of sales performance by location classification.

---

## 8. Outlet Type Analysis

A **pivot/table visual** provides a detailed comparison of different outlet types.

This allows users to examine outlet-level performance in a structured format.

---

# 🎛️ Interactive Dashboard Features

The dashboard includes multiple interactive controls.

### Slicers

Users can filter the dashboard using:

* **Item Type**
* **Outlet Size**
* **Outlet Location Type**

### Metrics Selector

A dedicated **Metrics** selector allows users to interact with the available measures and change the metric being analyzed.

### Interactive Visuals

Dashboard visuals are connected so that selections and filters can dynamically affect the analysis.

---

# 📌 Data Model

The main table used in the project is:

```text
BlinkIT Grocery Data
```

A separate **Metrics** table is also used to support the metric-selection functionality.

```text
BlinkIT Grocery Data
        │
        ├── Sales
        ├── Item Type
        ├── Item Fat Content
        ├── Outlet Type
        ├── Outlet Size
        ├── Outlet Location Type
        ├── Outlet Establishment Year
        └── Rating

Metrics
        │
        ├── Metrics
        ├── Metrics Fields
        └── Metrics Order
```

---

# 📊 Dashboard Preview

![BlinkIT Sales Dashboard](snapshot%20of%20the%20dashboard.png)

---

# 💡 Business Analysis Areas

This dashboard can be used to answer questions such as:

* What is the overall sales performance?
* What is the average sales value?
* How many items are present in the dataset?
* What is the average rating?
* Which item types contribute to sales?
* How does sales performance vary by fat content?
* How does outlet size affect sales?
* How do different outlet locations perform?
* How does outlet establishment year relate to sales?
* How do different outlet types compare?

---

# 🚀 Skills Demonstrated

This project demonstrates practical skills in:

* Power BI
* Power Query
* DAX
* Data Cleaning
* Data Transformation
* Data Modeling
* KPI Creation
* Data Visualization
* Slicers and Filters
* Interactive Dashboard Development
* Business Analysis
* Analytical Thinking

---

# 📁 Repository Structure

```text
BlinkIT_sales_dashboard/
│
├── protfolio_project_final.pbit
│
├── snapshot of the dashboard.png
│
└── README.md
```

---

# ▶️ How to Use This Project

1. Download the `.pbit` file from this repository.
2. Open it using **Microsoft Power BI Desktop**.
3. If Power BI asks for the data source, provide the required source.
4. Load or refresh the data.
5. Explore the dashboard.
6. Use the slicers and metric selector to interact with the report.

---

# 💼 Portfolio Project

This project was created as part of my **Data Analyst portfolio** to demonstrate practical experience in Power BI, data analysis, dashboard development, Power Query, and DAX.

### Technologies

**Power BI | Power Query | DAX | Data Analysis | Data Visualization | Business Intelligence**

---

## 👨‍💻 Author

**Suhas**

GitHub: **suhasram2004**

