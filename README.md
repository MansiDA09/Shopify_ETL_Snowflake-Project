# Shopify ETL & Cloud Data Warehouse Analytics

## 📌 Project Overview

An end-to-end cloud data analytics project demonstrating how e-commerce data can be extracted from Shopify, loaded into a cloud data warehouse using Fivetran, transformed using SQL in Snowflake, and analyzed using Power BI.

The project follows a modern data pipeline from **data source → data ingestion → cloud data warehouse → transformation → business intelligence**.

---

## 🔄 Data Pipeline

**Shopify → Fivetran → Snowflake → SQL Transformations → Power BI**

### 1. Shopify
Shopify was used as the source system containing customer, order, and product data.

### 2. Fivetran
Fivetran was used to automatically ingest Shopify data into Snowflake.

### 3. Snowflake
Snowflake was used as the cloud data warehouse to store and manage the ingested Shopify data.

### 4. SQL Transformations
SQL was used in Snowflake to clean, transform, and prepare the raw data for analytics while keeping the original raw data unchanged.

### 5. Power BI
Power BI was used to build an interactive dashboard and communicate business insights through data visualization.

---

## 🛠️ Tools & Technologies

- **Shopify** – Data Source
- **Fivetran** – Data Ingestion / ETL
- **Snowflake** – Cloud Data Warehouse
- **SQL** – Data Cleaning & Transformation
- **Power BI** – Data Visualization & Business Intelligence
- **Microsoft Excel** – Raw Data Export & Validation

---

## 🧹 Data Cleaning & Transformation

The raw Shopify data was transformed in Snowflake to make it suitable for analytics.

Key transformation activities included:

- Removing unnecessary and null columns
- Handling missing values
- Cleaning raw customer, order, and product data
- Renaming columns for better readability
- Creating cleaner analytical tables
- Preparing transformed data for Power BI

The original raw tables were preserved separately to maintain the integrity of the source data.

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an overview of Shopify sales and customer performance.

### Key Metrics

- Total Sales
- Total Orders
- Total Customers
- Average Order Value (AOV)

### Key Analysis

- Sales Trend
- Top Customers by Spending
- Inventory by Product

---

## 📁 Project Structure

```text
Shopify-ETL-Snowflake-Project/
│
├── Screenshots/
│   ├── Shopify/
│   ├── Fivetran/
│   ├── Snowflake/
│   └── PowerBI/
│
├── Shopify_ETL_Demo/
│   └── ETL demonstration videos
│
├── Shopify_Raw_Dataset.xlsx
│
└── shopify_dashboard.pbix
```

---

## 🏗️ Project Architecture

                ┌───────────────┐
                │    Shopify    │
                │  Data Source  │
                └───────┬───────┘
                        │
                        ▼
                ┌───────────────┐
                │    Fivetran   │
                │ Data Ingestion│
                └───────┬───────┘
                        │
                        ▼
                ┌───────────────┐
                │   Snowflake   │
                │ Cloud Data    │
                │   Warehouse   │
                └───────┬───────┘
                        │
                        ▼
                ┌───────────────┐
                │ SQL Cleaning  │
                │ & Transform.  │
                └───────┬───────┘
                        │
                        ▼
                ┌───────────────┐
                │    Power BI   │
                │   Dashboard   │
                └───────────────┘
```

---

## 🎯 Key Learning Outcomes

This project provided practical experience in:

- Building an end-to-end cloud ETL pipeline
- Data ingestion using Fivetran
- Working with a cloud data warehouse using Snowflake
- SQL-based data cleaning and transformation
- Handling raw and transformed datasets
- Preparing data for business intelligence
- Creating interactive Power BI dashboards
- Understanding modern cloud analytics workflows

---

## 🚀 End-to-End Workflow

1. Shopify was used as the source of e-commerce data.
2. Fivetran extracted and loaded the data into Snowflake.
3. Raw Shopify tables were stored in Snowflake.
4. SQL transformations were performed on the raw data.
5. Cleaned data was prepared for analytics.
6. Power BI was connected to the analytical data.
7. Interactive dashboards were created to generate business insights.

---

## 📌 Project Type

**Cloud ETL | Data Warehouse | Data Analytics | Business Intelligence**

---

## 👩‍💻 Conclusion

This project demonstrates a complete modern analytics workflow, starting from an operational e-commerce platform and ending with a business intelligence dashboard.

It showcases practical knowledge of **ETL, cloud data warehousing, SQL transformation, data cleaning, and Power BI visualization**.
