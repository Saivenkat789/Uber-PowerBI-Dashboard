# 🚕 Uber Ride Analytics Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Project-blue)
![Dashboard](https://img.shields.io/badge/Dashboard-Interactive-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📊 Project Overview

The **Uber Ride Analytics Dashboard** is an interactive **Power BI data analytics project** designed to analyze ride-booking data and generate meaningful business insights.

The dashboard provides a comprehensive view of **ride volume, booking performance, vehicle types, revenue, cancellations, customer behavior, and ratings** through interactive visualizations and KPIs.

The project demonstrates the use of **Power BI, Power Query, data modeling, DAX, interactive dashboards, and business intelligence techniques** to transform raw ride data into actionable insights.

---
## 🖼️ Dashboard Preview

### 🏠 Home Page

<img width="1433" height="809" alt="Homepage" src="https://github.com/user-attachments/assets/2f2c02da-6833-4c03-81d4-9a7f1ca17dfe" />

### 📈 Overall Analysis

<img width="1419" height="729" alt="overall" src="https://github.com/user-attachments/assets/423de5a8-3390-4e8a-87f9-7722f690aec4" />

### 🚘 Vehicle Type Analysis

<img width="1419" height="729" alt="overall" src="https://github.com/user-attachments/assets/eaf613e8-74ad-4a77-a7fa-daf257ff200b" />



### 💰 Revenue Analysis
<img width="1441" height="793" alt="Revenue" src="https://github.com/user-attachments/assets/84a9f8fc-a348-4c4c-aab1-79f84e460bf3" />


### ❌ Cancellation Analysis

<img width="1461" height="794" alt="Cancellation" src="https://github.com/user-attachments/assets/1dc1708b-e580-45a1-ada0-74be602a57c2" />

### ⭐ Ratings Analysis

<img width="1441" height="797" alt="Ratings" src="https://github.com/user-attachments/assets/05123178-8201-4e47-97c4-d4a531036f5f" />

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze overall Uber ride-booking performance.
* Track ride volume and booking trends over time.
* Analyze performance across different vehicle types.
* Understand revenue generated through different payment methods.
* Identify top customers based on booking/revenue metrics.
* Analyze customer and driver cancellations.
* Monitor booking success and cancellation rates.
* Analyze customer and driver ratings.
* Build an interactive and user-friendly Power BI dashboard.

---

## 🛠️ Tools & Technologies

| Tool / Technology    | Purpose                                      |
| -------------------- | -------------------------------------------- |
| **Power BI**         | Dashboard development and data visualization |
| **Power Query**      | Data cleaning and transformation             |
| **DAX**              | Measures and analytical calculations         |
| **Data Modeling**    | Organizing data for analysis                 |
| **Excel / CSV**      | Source data preparation                      |
| **Power BI Visuals** | Interactive business reporting               |

---

# 📌 Dashboard Pages

## 🏠 1. Home Page

The Home Page acts as the navigation interface for the dashboard.

It provides navigation buttons to different analytical sections:

* Overall Analysis
* Vehicle Type Analysis
* Revenue Analysis
* Cancellation Analysis
* Ratings Analysis

---

## 📈 2. Overall Analysis

The Overall page provides a high-level overview of Uber ride performance.

### Key Analysis

* Total bookings
* Ride volume over time
* Booking status distribution
* Date-based analysis
* Overall booking performance

### Visualizations

* 📈 Ride Volume Over Time
* 🥧 Booking Status Breakdown
* 🔢 Total Bookings KPI
* 📅 Date Slicer

This page helps users understand the overall performance and trends in ride bookings.

---

## 🚘 3. Vehicle Type Analysis

This page focuses on analyzing ride performance across different vehicle categories.

### Key Analysis

* Vehicle-wise booking performance
* Vehicle category comparison
* Vehicle-level KPIs
* Date-based filtering

### Visualizations

* Vehicle-wise KPI cards
* Date slicer
* Vehicle comparison metrics

This section helps identify how different vehicle categories contribute to overall ride activity.

---

## 💰 4. Revenue Analysis

The Revenue page focuses on understanding revenue and payment-related patterns.

### Key Analysis

* Revenue by payment method
* Ride distance distribution
* Top customers
* Payment behavior
* Revenue-related performance

### Visualizations

* 📊 Revenue by Payment Method
* 📊 Ride Distance Distribution
* 📋 Top 5 Customers
* 📅 Date Slicer

This page provides insights into revenue generation and customer payment behavior.

---

## ❌ 5. Cancellation Analysis

The Cancellation page analyzes cancelled rides from both customer and driver perspectives.

### Key KPIs

* Total Bookings
* Successful Bookings
* Cancelled Bookings
* Cancellation Rate

### Visualizations

* 🥧 Cancelled Rides by Customers
* 🥧 Cancelled Rides by Drivers
* 🔢 Total Bookings
* 🔢 Successful Bookings
* 🔢 Cancelled Bookings
* 📊 Cancellation Rate

This analysis helps identify cancellation patterns and understand their impact on overall booking performance.

---

## ⭐ 6. Ratings Analysis

The Ratings page focuses on analyzing rating-related metrics.

### Key Analysis

* Customer ratings
* Driver ratings
* Rating-based KPIs
* Performance comparison

The page uses KPI cards and interactive filtering to provide a quick overview of rating performance.

---

# 🔄 Data Analysis Workflow

The project follows a typical Business Intelligence workflow:

```text
Raw Uber Data
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Data Modeling
      ↓
DAX Calculations
      ↓
Data Visualization
      ↓
Interactive Power BI Dashboard
      ↓
Business Insights
```

---

# 🧹 Data Preparation

The data was prepared using **Power Query** before building the dashboard.

Typical data preparation activities included:

* Removing duplicate records
* Handling missing values
* Correcting data types
* Formatting date columns
* Cleaning categorical fields
* Transforming columns
* Creating analysis-ready fields
* Validating data consistency

---

# 🧮 DAX & KPI Analysis

DAX was used to create analytical measures and KPIs for the dashboard.

Examples of commonly used analytical measures include:

```DAX
Total Bookings =
COUNTROWS('Uber Data')
```

```DAX
Successful Bookings =
CALCULATE(
    [Total Bookings],
    'Uber Data'[Booking Status] = "Success"
)
```

```DAX
Cancelled Bookings =
CALCULATE(
    [Total Bookings],
    'Uber Data'[Booking Status] = "Cancelled"
)
```

```DAX
Cancellation Rate =
DIVIDE(
    [Cancelled Bookings],
    [Total Bookings],
    0
)
```

> **Note:** Update the table and column names in these examples if they differ from the names in your Power BI model.

---

# 📊 Key Business Questions

This dashboard can be used to answer questions such as:

1. How many rides were booked?
2. How does ride volume change over time?
3. What is the distribution of booking statuses?
4. Which vehicle types contribute most to ride activity?
5. How is revenue distributed across payment methods?
6. Who are the top customers?
7. How many rides are cancelled by customers?
8. How many rides are cancelled by drivers?
9. What is the overall cancellation rate?
10. How do customer and driver ratings vary?

---

# 💡 Business Insights

The dashboard enables stakeholders to:

* Monitor ride-booking performance.
* Identify changes in ride demand over time.
* Compare vehicle categories.
* Understand payment-method distribution.
* Identify high-value customers.
* Monitor cancellation behavior.
* Track booking success rates.
* Evaluate customer and driver rating patterns.

These insights can support **operational monitoring, customer analysis, service improvement, and business decision-making**.

---

# 🎨 Dashboard Features

### Interactive Filters

The dashboard includes interactive date filtering that allows users to analyze performance across different time periods.

### KPI Cards

Important metrics are presented through KPI cards for quick monitoring.

### Interactive Navigation

Navigation buttons allow users to move between different analytical pages.

### Business-Focused Visualizations

The dashboard uses:

* Cards
* Line charts
* Pie charts
* Column charts
* Tables
* Slicers
* Interactive navigation buttons

---

# 📷 Dashboard Preview

Add screenshots of your Power BI dashboard here.

### Home Page

```text
![Home Page](images/home-page.png)
```

### Overall Analysis

```text
![Overall Dashboard](images/overall-dashboard.png)
```

### Vehicle Type Analysis

```text
![Vehicle Type Dashboard](images/vehicle-type.png)
```

### Revenue Analysis

```text
![Revenue Dashboard](images/revenue.png)
```

### Cancellation Analysis

```text
![Cancellation Dashboard](images/cancellation.png)
```

### Ratings Analysis

```text
![Ratings Dashboard](images/ratings.png)
```

> Create an `images` folder inside your GitHub repository and upload the dashboard screenshots there.
> 



# 📚 Skills Demonstrated

This project demonstrates practical experience in:

* Power BI
* Data Analytics
* Business Intelligence
* Data Cleaning
* Power Query
* DAX
* Data Visualization
* KPI Development
* Data Modeling
* Interactive Dashboard Design
* Business Analysis
* Customer Analysis
* Revenue Analysis
* Trend Analysis

---

# 💼 Resume Description

You can also use this project on your resume:

**Uber Ride Analytics Dashboard | Power BI**

> Developed an interactive Power BI dashboard to analyze Uber ride bookings, vehicle performance, revenue, cancellations, customer behavior, and ratings. Performed data cleaning and transformation using Power Query and created DAX-based KPIs and interactive visualizations for business performance analysis.

---

# 👨‍💻 Author

**Sai Venkatesh**

B.Tech – Computer Science and Engineering

📍 India

🔗 GitHub:
https://github.com/Saivenkat789

---

# ⭐ Project Status

**Completed**

If you found this project useful, consider giving the repository a ⭐.

---

## 📌 Keywords

`Power BI` `Data Analytics` `Business Intelligence` `DAX` `Power Query` `Data Visualization` `Dashboard` `Uber Analytics` `Revenue Analysis` `Customer Analytics` `KPI` `Data Modeling`
