# 👔 Men's Fashion Brand Performance Analysis Dashboard

## 📊 Power BI Dashboard Link : 
[https://app.powerbi.com/groups/c284d658-0531-4cfd-acf4-46b944a81b2e/reports/ccebc58f-5660-4d36-a6ba-12e5c9fbe127/66c6dc4cfb141b395b87?experience=power-bi]

## 📱 Power BI App Link :
 [https://app.powerbi.com/groups/me/apps/b313f09b-8985-4002-807b-fc23827b8ede/reports/ccebc58f-5660-4d36-a6ba-12e5c9fbe127/66c6dc4cfb141b395b87?experience=power-bi]

---

## 📌 Project Overview

The Men's Fashion Brand Performance Analysis project focuses on analyzing men's fashion product data to uncover valuable insights related to brand positioning, discount strategies, pricing trends, product variety, and profitability.

The project follows an end-to-end Business Intelligence workflow where raw data was first loaded into Azure SQL Database for storage and basic data cleaning. The cleaned dataset was then connected to Power BI Desktop for dashboard development, published to Power BI Service for cloud-based reporting, and finally deployed through a Power BI App for secure business-wide distribution.


---

## 🎯 Business Problem

Fashion businesses often struggle to answer critical questions such as:

* Top 5  brands By Average discounts?
* Top 5 Brand By Highest Average Profit % ?
* Top 5 Brands By Highest Number of Varities ?
* Top 5 brands By Average Sales Price ?
* Bottom 5 Brands By Average Profit % ? 

This dashboard addresses these challenges by providing interactive brand-level analytics and performance monitoring.

---

## 🛠 Tools & Technologies

### ☁ Microsoft Azure

* Azure SQL Database
* SQL Queries
* Data Storage

### 📊 Microsoft Power Platform

* Power BI Desktop
* Power BI Service
* Power BI App
* Power Query
* DAX

### 📂 Data Source

* AZURE SQL Server 

### 📌 Dataset Fields

#### Men Tshirt Dataset

* Brand
* Product Title
* Cost Price
* Marked Price
* Discount %
* Sales Price
* Profit %

---

## 📈 Dashboard Highlights

### 1️⃣ Azure SQL Data Processing

* Imported raw CSV dataset into Azure SQL Database.
* Performed basic data cleaning and validation.
* Removed inconsistencies and verified pricing data.
* Prepared dataset for reporting.

### 2️⃣ Power BI Data Modeling

* Connected Azure SQL Database to Power BI.
* Created analytical measures using DAX.

### 3️⃣ KPI Development

Developed KPIs for:

* Top 5  brands By Average discounts?
* Top 5 Brand By Highest Average Profit % ?
* Top 5 Brands By Highest Number of Varities ?
* Top 5 brands By Average Sales Price ?
* Bottom 5 Brands By Average Profit % ? 

### 4️⃣ DAX Measure and Calculated Columns 

*       Cost Price = DIVIDE(100*'Men Tshirt'[Sales Price],100+'Men Tshirt'[Profit %])
*       Discount % = DIVIDE('Men Tshirt'[Marked Price ]-'Men Tshirt'[Sales Price],'Men Tshirt' [Marked Price ])* 100
*       Profit % = RANDBETWEEN(2,17)

### 5️⃣ Cloud Deployment

* Published reports to Power BI Service.
* Configured cloud access and report sharing.
* Created Power BI App for end-user consumption.
* Enabled centralized dashboard distribution.

---

## ☁ Power BI Service & App Deployment

### Power BI Service

The completed dashboard was successfully published to Power BI Service, allowing cloud-based report access and centralized dashboard management.

### Power BI App

A Power BI App was created to provide a streamlined user experience and simplify dashboard sharing across business users.

Benefits of the Power BI App:

* Centralized dashboard access.
* Secure report sharing.
* Improved user experience.
* Enterprise-level deployment.
* Easy scalability for future reports.

---

## 📊 DashBoard Overview 

Azure 
![Image1](https://github.com/ROHIT19K/Men-s-Brand-Clothes-Analysis-Using-AZURE-POWER-BI-/blob/main/Azure%201.png)

![Image2](https://github.com/ROHIT19K/Men-s-Brand-Clothes-Analysis-Using-AZURE-POWER-BI-/blob/main/Azure%202.png)

Reports Creation 
![Image3](https://github.com/ROHIT19K/Men-s-Brand-Clothes-Analysis-Using-AZURE-POWER-BI-/blob/main/Brands%201.png)

![Image4](https://github.com/ROHIT19K/Men-s-Brand-Clothes-Analysis-Using-AZURE-POWER-BI-/blob/main/Analysis%202.png)

Power BI Service Published 
![Image5](https://github.com/ROHIT19K/Men-s-Brand-Clothes-Analysis-Using-AZURE-POWER-BI-/blob/main/Men%20Clothes%20Analysis%20Power%20BI%20Serviced%20Published%20.png)

## 🔍 Key Insights

#### 📌 Brand Selection Overview

* The dashboard provides an interactive catalog of men's fashion brands for detailed performance analysis.

* Users can dynamically filter and analyze individual brands using the brand slicer.

* The landing page serves as a centralized navigation point for exploring brand-level insights.

* The dashboard enables quick access to pricing, discount, and profitability metrics across multiple fashion brands.

* Designed to improve user experience through intuitive brand selection and seamless report navigation.

#### 📌 Brand Performance Analysis

* The Indian Garage Co offers the highest average discount percentage among the analyzed brands.

* CHIMPAAANZEE and Fashion 2 Wear achieve the highest average profit percentages.

* ARMANI EXCHANGE records the highest average sales price, indicating a premium market position.

* The Indian Garage Co has the largest product variety, followed by U.S. Polo Assn. and SNITCH.

* Several premium brands maintain strong profitability despite offering lower discounts.

* Brands with larger product assortments tend to have greater market visibility and customer reach.

* Discount strategies vary significantly across brands, highlighting different competitive positioning approaches.

* The dashboard helps identify high-profit, high-discount, and premium-priced brands for strategic business decision-making.

---

.
# 📈 Business Recommendations

* Focus marketing efforts on high-profit brands to maximize returns.
* Review discount-heavy brands to ensure profitability is maintained.
* Expand successful product lines from brands with strong variety and customer appeal.
* Leverage premium brands for value-based pricing strategies.
* Use brand performance insights to optimize inventory planning and merchandising decisions.

## 🚀 Future Enhancements

* Automated Azure SQL Refresh.
* Incremental Data Loading.
* Azure Data Factory Integration.
* Real-Time Dashboard Refresh.
* Sales & Profit Forecasting.
* AI-Powered Fashion Trend Analysis.
* Customer Behavior Analytics.
* Mobile Optimized Power BI App.

---

## 📊 Project Workflow

1. Data Collection
2. Azure SQL Data Storage
3. SQL Data Cleaning
4. Power BI Connection
5. Data Modeling
6. KPI Development
7. Dashboard Design
8. Power BI Service Publishing
9. Power BI App Creation
10. Business Insight Generation

---

## ✅ Results & Outcomes

* Successfully implemented Azure SQL as the data source.
* Developed an interactive Power BI dashboard.
* Published reports to Power BI Service.
* Created a Power BI App for business users.
* Improved visibility into pricing and discount strategies.
* Enabled brand-level performance monitoring.
* Delivered a scalable Business Intelligence solution.

---

# 📬 Contact

## 👤 Author

Rohit Kumar

LinkedIn: https://linkedin.com/in/yourprofile

GitHub: https://github.com/yourusername

Email: yourmail@gmail.com
