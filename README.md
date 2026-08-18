# Indian_Retail_Ecommerce_Sales_Customer_Product_Analysis

> **End-to-End Retail & E-commerce Data Analysis Project | Google Colab + Python + Power BI**

---

## 📊 Project Overview

**Indian_Retail_Ecommerce_Sales_Customer_Product_Analysis** is an **end-to-end data analysis project** focused on analyzing retail and e-commerce sales, customer behavior, product performance, regional performance, sales channels, payment methods and delivery operations.

The project analyzes **100K+ transaction records** covering a three-year period from **2023 to 2025**.

The complete analysis workflow was performed using **Google Colab**, with **Python** used for data preparation, exploratory analysis, visualization and business analysis. **Power BI** is used as the dashboard and reporting layer.

### End-to-End Workflow

```text
Business Problem
       ↓
Raw Retail Data
       ↓
Data Ingestion
       ↓
Data Cleaning
       ↓
Data Validation
       ↓
Exploratory Data Analysis
       ↓
Business Analysis
       ↓
KPI Analysis
       ↓
Power BI Dashboard
       ↓
Business Insights
```

---

## 💼 Business Problem

Retail businesses generate large volumes of transaction data containing information about:

- Customers
- Products
- Categories
- Locations
- Pricing
- Discounts
- Payment methods
- Sales channels
- Customer segments
- Delivery status
- Ratings
- Sales amounts

Raw transaction data does not directly explain which areas are driving sales or where the business should focus.

This project transforms transaction-level data into **structured, validated and business-oriented insights** across:

- Sales performance
- Customer behavior
- Product performance
- Regional performance
- Sales channels
- Payment methods
- Delivery operations
- Business relationships between key variables

---

## 🎯 Project Objectives

### 🔹 Data Preparation

- Import and inspect the raw dataset
- Assess data quality
- Identify and handle missing values
- Detect duplicate records
- Validate duplicate Order IDs
- Validate data types
- Standardize categorical values
- Check data consistency
- Investigate outliers using IQR

### 🔹 Sales Analysis

- Analyze sales by category
- Analyze product-level sales
- Analyze state and city performance
- Compare Online vs Store
- Analyze payment methods
- Analyze monthly and yearly sales trends

### 🔹 Customer Analysis

- Analyze customer segments
- Analyze age groups
- Analyze gender-level performance
- Compare customer segments across sales channels

### 🔹 Product Analysis

- Identify top-performing products
- Identify top products within each category
- Compare category performance
- Analyze product ratings

---

## 📈 Project Statistics

| Metric | Value |
|---|---:|
| 🧾 Records Analyzed | **100,000+** |
| 📑 Original Columns | **19** |
| 👥 Unique Customers | **14,988** |
| 🛒 Unique Orders | **100,000** |
| 💰 Total Sales | **₹2.18B+** |
| 📦 Total Quantity Sold | **180,987** |
| 📦 Product Categories | **5** |
| 🏷️ Products | **25** |
| 📍 States | **15** |
| 🏙️ Cities | **49** |
| 💳 Payment Methods | **6** |
| 🛍️ Sales Channels | **2** |
| 👤 Customer Segments | **3** |
| 📅 Analysis Period | **2023–2025** |

> These figures represent the supplied dataset and project analysis, not the overall Indian retail market.

---

## 🧹 Data Cleaning & Validation

The project performs a structured data-cleaning process in Google Colab.

### Data Cleaning Activities

- Missing-value analysis
- Missing-value treatment
- Duplicate-row analysis
- Duplicate Order ID analysis
- Data-type validation
- Numeric validation
- Categorical standardization
- Formatting cleanup
- Gender standardization
- Payment-method standardization
- Delivery-status standardization
- Data consistency checks
- IQR-based outlier investigation
- Final data-quality validation

### Final Data Quality

```text
Rows:                 100,000
Original Columns:     19
Missing Values:       0
Duplicate Rows:       0
Duplicate Order IDs:  0
```

The cleaned dataset is generated as:

```text
cleaned_sales_data.csv
```

---

## 📊 Key Business KPIs

The project calculates important business KPIs including:

- Total Sales
- Total Orders
- Average Sales Amount
- Total Quantity Sold

### Actual KPI Results

| KPI | Result |
|---|---:|
| Total Sales | **₹2,182,312,374.25** |
| Total Orders | **100,000** |
| Average Sales Amount | **₹21,823.12** |
| Total Quantity Sold | **180,987** |

---

## 🏆 Key Business Results

Based on the analysis performed in the notebook:

| Business Area | Top Result |
|---|---|
| 🏆 Category | **Electronics** |
| 🏆 State | **Odisha** |
| 🏆 City | **Cuttack** |
| 🏆 Sales Channel | **Online** |
| 🏆 Customer Segment | **Consumer** |
| 🏆 Payment Method | **UPI** |
| 🏆 Delivery Status | **Delivered** |

---

## 🔍 Analysis Performed

### 📦 Product & Category Analysis

- Category-wise sales
- Product-wise sales
- Top-performing products
- Top 3 products within each category
- Category performance
- Product-rating analysis

### 📍 Geographic Analysis

- State-wise sales
- Top 10 states
- Bottom 10 states
- City-wise sales
- Top 10 cities
- Bottom 10 cities
- State × Category performance

### 👥 Customer Analysis

- Customer segments
- Orders by customer segment
- Average sales by customer segment
- Customer age groups
- Sales by age group
- Gender-wise sales
- Category × Gender performance

### 🛍️ Sales Channel Analysis

- Online vs Store sales
- Sales by channel
- Orders by channel
- Monthly channel trends
- Customer Segment × Channel
- Delivery Status × Channel

### 💳 Payment Analysis

- Sales by payment method
- Orders by payment method

### 📅 Time-Series Analysis

- Monthly sales
- Yearly sales
- Year-over-year sales growth
- Monthly sales by category
- Monthly sales by sales channel

### 📊 Relationship Analysis

- Discount vs Sales Amount
- Rating vs Sales Amount
- Quantity vs Sales Amount
- Age vs Sales Amount
- Correlation analysis

---

## 📊 Power BI Dashboard

**Power BI** is used as the visualization and reporting layer of the project.

The Power BI dashboard/template is maintained separately inside the `Power Bi` folder.

```text
Power Bi/
└── Indian_Retail_Ecommerce_Sales_Customer_Product_Analysis_Dashboard.pbit
```

The dashboard is used to present:

- Business KPIs
- Sales performance
- Customer analysis
- Product analysis
- Regional performance
- Sales trends
- Business comparisons
- Interactive reporting

### End-to-End Flow

```text
Raw Data
   ↓
Google Colab
   ↓
Data Cleaning
   ↓
EDA
   ↓
Business Analysis
   ↓
KPIs
   ↓
Power BI Dashboard
   ↓
Business Insights
```

---

## 🧰 Technology Stack

### Environment

- **Google Colab**

### Programming & Data Analysis

- **Python**
- **Pandas**
- **NumPy**

### Data Visualization

- **Matplotlib**
- **Seaborn**

### Business Intelligence

- **Microsoft Power BI**

### Version Control

- **Git**
- **GitHub**

> SQL is not listed as part of this specific project because the supplied project code does not contain SQL analysis.

---

## 📂 GitHub Repository Structure

```text
Indian_Retail_Ecommerce_Sales_Customer_Product_Analysis/
│
├── .gitignore
├── README.md
├── Background  img.png
│
├── Data/
│   └── cleaned_sales_data.csv
│
├── Notebook/
│   └── Data_Cleaning.ipynb
│
├── Power Bi/
│   └── Indian_Retail_Ecommerce_Sales_Customer_Product_Analysis_Dashboard.pbit
│
└── docs/
    ├── Indian_Retail_Ecommerce_Sales_Customer_Product_Analysis_Business_Problem_Statement(2).pdf
    └── Indian_Retail_Ecommerce_Sales_Customer_Product_Analysis_Deliverables.pdf
```

### Folder Description

| Folder/File | Purpose |
|---|---|
| `Data/` | Processed/cleaned dataset |
| `Notebook/` | Google Colab/Jupyter analysis notebook |
| `Power Bi/` | Power BI dashboard/template |
| `docs/` | Business documentation |
| `Background img.png` | Dashboard background image |
| `.gitignore` | Files excluded from Git |
| `README.md` | Project documentation |

> **The raw dataset is excluded from GitHub using `.gitignore`.**

> **No `outputs/` folder is included in the project structure.**

---

## ▶️ How to Run the Project

### Step 1 — Open Google Colab

Open the notebook:

```text
Notebook/Data_Cleaning.ipynb
```

in Google Colab.

### Step 2 — Upload the Raw Dataset

The raw dataset is intentionally excluded from GitHub.

Upload the raw CSV to Google Colab before running the notebook.

The notebook uses a path similar to:

```python
df = pd.read_csv(
    '/content/Indian_Retail_Ecommerce_Raw_100K(1).csv'
)
```

### Step 3 — Run the Notebook

Run the notebook sequentially:

```text
Data Import
    ↓
Data Inspection
    ↓
Data Cleaning
    ↓
Data Validation
    ↓
EDA
    ↓
Business Analysis
    ↓
KPI Analysis
    ↓
Business Insights
```

### Step 4 — Generate Cleaned Dataset

The notebook generates:

```text
cleaned_sales_data.csv
```

### Step 5 — Open Power BI

Open:

```text
Power Bi/
└── Indian_Retail_Ecommerce_Sales_Customer_Product_Analysis_Dashboard.pbit
```

Connect it to the required data source if prompted.

---

## 📤 Project Output

The primary data output generated by the analysis is:

```text
cleaned_sales_data.csv
```

### Cleaned Dataset

```text
Rows:                 100,000
Original Columns:     19
Missing Values:       0
Duplicate Rows:       0
Duplicate Order IDs:  0
```

The analysis also creates derived analytical fields such as:

```text
Month
Year
Age_Group
```

---

## 🧠 End-to-End Data Analysis Architecture

```text
                    BUSINESS PROBLEM
                           │
                           ▼
                       RAW DATA
                           │
                           ▼
                    GOOGLE COLAB
                           │
                           ▼
                DATA QUALITY ASSESSMENT
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
         Missing       Duplicates     Outliers
          Values         Checks        Analysis
             │             │             │
             └─────────────┼─────────────┘
                           ▼
                    DATA CLEANING
                           │
                           ▼
                   FEATURE CREATION
                           │
                           ▼
                          EDA
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
           SALES        CUSTOMER       PRODUCT
             │             │             │
             └─────────────┼─────────────┘
                           ▼
                  BUSINESS ANALYSIS
                           │
                           ▼
                         KPIs
                           │
                           ▼
                  POWER BI DASHBOARD
                           │
                           ▼
                   BUSINESS INSIGHTS
```

---

## 💡 Business Value

This project demonstrates how raw retail transaction data can be transformed into business-ready insights that can support:

- Sales performance monitoring
- Product strategy
- Category strategy
- Customer segmentation
- Regional performance analysis
- Sales-channel comparison
- Payment-method analysis
- Delivery-status monitoring
- Discount analysis
- Product-rating analysis
- Data-driven decision making

---

## 🎓 Skills Demonstrated

### Technical Skills

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook
- Power BI
- Data Cleaning
- Data Validation
- Exploratory Data Analysis
- KPI Analysis
- Data Visualization

### Business & Analytical Skills

- Business problem identification
- Business question formulation
- Data quality assessment
- Sales analysis
- Customer analysis
- Product analysis
- Regional analysis
- Trend analysis
- Relationship analysis
- KPI development
- Insight generation
- Business storytelling

---

## 📌 Project Scope

| Attribute | Details |
|---|---|
| **Project Name** | Indian_Retail_Ecommerce_Sales_Customer_Product_Analysis |
| **Domain** | Indian Retail / E-commerce |
| **Project Type** | End-to-End Data Analysis |
| **Environment** | Google Colab |
| **Visualization** | Power BI |
| **Primary Language** | Python |
| **Dataset Scale** | 100K+ records |
| **Original Features** | 19 |
| **Analysis Period** | 2023–2025 |
| **Main Data Output** | `cleaned_sales_data.csv` |

---

## ⭐ Portfolio Summary

> **Indian_Retail_Ecommerce_Sales_Customer_Product_Analysis** is an end-to-end Indian retail/e-commerce data analysis project developed using **Google Colab and Power BI**, analyzing **100K+ transaction records across a three-year period**. The project covers **14,988 customers, 25 products, 5 categories, 15 states and 49 cities** and follows the complete analytical lifecycle from business problem identification and raw data ingestion to data cleaning, validation, exploratory analysis, business analysis, KPI development, Power BI dashboard reporting and business insight generation. The analysis identified **₹2.18B+ in total sales and 180,987 units sold**, providing a structured view of sales, customer, product, regional, channel and operational performance.

---

## ⚠️ Data Privacy

The raw dataset is intentionally excluded from the GitHub repository.

Do not commit:

- Confidential customer information
- Passwords
- API keys
- Credentials
- Sensitive production data

The `.gitignore` file is configured to prevent the raw dataset from being uploaded.

---

## 👨‍💻 Author

**Alavala Srinivas**

- GitHub: https://github.com/Rayyanbabasyed
- LinkedIn:https://www.linkedin.com/in/syed-rayyanbaba

---

## ⭐ If you find this project useful, consider starring the repository!
