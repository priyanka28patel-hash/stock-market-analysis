# 📈 NIFTY 50 Stock Market Analysis

## 👩‍💻 Priyanka Patel

### Data Analyst | Excel | SQL | Power BI | Python | Tableau

**NIFTY 50 Stock Market Analysis using Python, PostgreSQL, SQL and Power BI**

---

## 📌 Project Overview

This project presents an end-to-end **NIFTY 50 Stock Market Analysis** using historical market data from **2020 to 2025**.

The project demonstrates how raw stock market data can be collected, cleaned, transformed, analyzed and converted into meaningful insights using **Python, PostgreSQL, SQL and Power BI**.

The analysis focuses on:

- NIFTY 50 closing price trends
- Daily market returns
- Market volatility
- Moving averages
- Year-wise market performance
- Major daily market declines
- Long-term market movement
- Market fluctuation patterns

The project follows a complete Data Analytics workflow:

**Raw Data → Data Cleaning → Feature Engineering → Python Analysis → PostgreSQL → SQL Analysis → Power BI Dashboard → Business Insights → GitHub Portfolio**

---

## 🎯 Business Question

### How has the NIFTY 50 market performed between 2020 and 2025, and what patterns can be identified in terms of price trends, returns, moving averages and market volatility?

The project aims to answer:

- How did NIFTY 50 closing prices change over the years?
- Which years recorded higher average closing prices?
- What were the major daily market declines?
- How volatile was the market during different periods?
- How does the 20-day moving average help identify market trends?
- What does daily return analysis reveal about market performance?
- Which periods experienced significant market fluctuations?

---

## 🎯 Project Objectives

1. Analyze historical NIFTY 50 market data from 2020–2025.
2. Clean and standardize the raw datasets using Python.
3. Combine yearly datasets into a single analytical dataset.
4. Calculate important financial and statistical metrics.
5. Store the cleaned analytical data in PostgreSQL.
6. Perform SQL-based market analysis.
7. Identify major daily market declines.
8. Analyze moving averages and market volatility.
9. Build an interactive Power BI dashboard.
10. Present findings through visualizations and KPIs.
11. Demonstrate an end-to-end Data Analyst workflow.
12. Convert raw market data into meaningful analytical insights.

---

## 📊 Dataset Description

The project uses historical **NIFTY 50 market data** covering:

**1 January 2020 to 31 December 2025**

The consolidated dataset contains:

- **1,492 records**
- Six years of historical market data
- Opening price
- Highest price
- Lowest price
- Closing price
- Index name
- Trading date

### Dataset Period

| Year | Dataset |
|---|---|
| 2020 | NIFTY 50 Historical Data |
| 2021 | NIFTY 50 Historical Data |
| 2022 | NIFTY 50 Historical Data |
| 2023 | NIFTY 50 Historical Data |
| 2024 | NIFTY 50 Historical Data |
| 2025 | NIFTY 50 Historical Data |

---

## 📋 Original Dataset Columns

| Column | Description |
|---|---|
| `Index Name` | Name of the market index |
| `Date` | Trading date |
| `Open` | Opening value of NIFTY 50 |
| `High` | Highest value during the trading day |
| `Low` | Lowest value during the trading day |
| `Close` | Closing value of NIFTY 50 |
| `source_file` | Source yearly CSV file |

---

## 🖥️ Dashboard Preview

The final Power BI dashboard provides an interactive overview of NIFTY 50 market performance.

### 📊 Power BI Dashboard

![Power BI Dashboard](./Screenshots/01_PowerBI_Dashboard.png)

---

## 📌 Key Performance Indicators

| KPI | Purpose |
|---|---|
| Average NIFTY 50 Close | Measures the average closing level |
| Highest NIFTY 50 Close | Identifies the highest recorded closing level |
| Lowest NIFTY 50 Close | Identifies the lowest recorded closing level |
| Average Daily Return % | Measures average daily market return |

---

## 🛠️ Tools & Technologies

### Python

Used for:

- Data loading
- Data cleaning
- Data transformation
- Dataset consolidation
- Feature engineering
- Exploratory Data Analysis
- Data visualization

Libraries used:

- Pandas
- NumPy
- Matplotlib

### PostgreSQL

Used for:

- Storing cleaned analytical data
- Creating the market analysis table
- Querying historical market data
- Performing structured database analysis

### SQL

Used for:

- Market performance analysis
- Filtering and sorting
- Aggregation
- Identifying major market declines
- Year-wise analysis
- Historical market analysis

### Power BI

Used for:

- Interactive dashboard development
- KPI cards
- Trend analysis
- Moving-average visualization
- Volatility analysis
- Year-wise comparison
- Interactive filtering

### Excel

Used as an additional data analysis and reference format.

### GitHub

Used for:

- Project version control
- Portfolio presentation
- Documentation
- Sharing project files

---

## 🔄 Project Methodology

### Step 1 — Data Collection

Collected six yearly NIFTY 50 historical datasets covering 2020–2025.

### Step 2 — Data Consolidation

Combined the six yearly datasets into a single analytical dataset.

### Step 3 — Data Cleaning

Cleaned and standardized the raw datasets using Python.

### Step 4 — Feature Engineering

Created financial and analytical metrics to support deeper analysis.

### Step 5 — Python Analysis

Performed exploratory analysis and visualization using Pandas, NumPy and Matplotlib.

### Step 6 — PostgreSQL Database

Loaded the cleaned analytical dataset into PostgreSQL.

### Step 7 — SQL Analysis

Performed structured market analysis using SQL.

### Step 8 — Power BI Dashboard

Connected the analytical data to Power BI and created an interactive dashboard.

### Step 9 — Business Insights

Interpreted trends, returns and volatility to identify important market patterns.

### Step 10 — GitHub Portfolio

Organized the complete project and documentation in GitHub.

---

## 🧹 Data Cleaning & Preparation

The following data preparation steps were performed:

- Imported six yearly CSV files using Pandas.
- Combined the yearly datasets.
- Standardized column names.
- Converted the `Date` field into a proper date format.
- Converted market price columns into numeric data types.
- Checked for missing values.
- Checked data types and dataset structure.
- Sorted records chronologically.
- Prepared the final analytical dataset.

### Final Standardized Columns

`index_name`, `date`, `open`, `high`, `low`, `close`

---

## ⚙️ Feature Engineering & Calculated Metrics

The following analytical metrics were created:

### 1. Daily Range

**Formula:**

`Daily Range = High - Low`

Measures the difference between the highest and lowest market value during a trading day.

### 2. Daily Return %

**Formula:**

`Daily Return % = ((Current Close - Previous Close) / Previous Close) × 100`

Measures the percentage change in closing value compared with the previous trading day.

### 3. 20-Day Moving Average

Calculates the average closing value over a rolling 20-trading-day period.

Used to identify short-term market trends while reducing daily price fluctuations.

### 4. 50-Day Moving Average

Calculates the average closing value over a rolling 50-trading-day period.

Used to understand medium-term market movement.

### 5. 20-Day Rolling Volatility

Measures the fluctuation in daily returns over a rolling 20-day period.

Higher volatility indicates greater market fluctuations and uncertainty.

### 6. Cumulative Return %

Measures the overall change in the index over the analysis period.

---

## 🐍 Python Analysis

Python was used for:

- Data cleaning
- Data consolidation
- Data transformation
- Feature engineering
- Exploratory Data Analysis
- Statistical analysis
- Data visualization

### Python Analysis Screenshot

![Python Analysis](./Screenshots/02_Python_Analysis.png)

The Python visualization shows **20-Day Rolling Volatility** and highlights periods of increased market fluctuations.

---

## 🗄️ PostgreSQL Database

The cleaned and engineered dataset was stored in PostgreSQL for structured querying and analysis.

### Database

`stock_market_db`

### Table

`public.stock_market_data`

### Analytical Fields

- `index_name`
- `date`
- `open`
- `high`
- `low`
- `close`
- `daily_range`
- `daily_return_pct`
- `ma_20`
- `ma_50`
- `volatility_20d`
- `cumulative_return_pct`

---

## 🧮 SQL Analysis

SQL was used to:

- Analyze market performance
- Sort daily returns
- Identify major market declines
- Perform aggregations
- Compare market performance
- Analyze historical price movements

### SQL Analysis Screenshot

![SQL Analysis](./Screenshots/03_SQL_Analysis.png)

---

## 📉 Major Daily Market Declines

SQL analysis was used to identify the days with the largest negative daily returns.

| Date | Closing Value | Daily Return % |
|---|---:|---:|
| 23-Mar-2020 | 7,610.25 | -12.98% |
| 12-Mar-2020 | 9,590.15 | -8.30% |
| 16-Mar-2020 | 9,197.40 | -7.61% |
| 04-Jun-2024 | 21,884.50 | -5.93% |

The largest identified daily decline was approximately **-12.98% on 23 March 2020**.

---

## 📊 Power BI Dashboard

Power BI was used to transform the analytical dataset into an interactive dashboard.

### Dashboard KPIs

- Average NIFTY 50 Close
- Highest NIFTY 50 Close
- Lowest NIFTY 50 Close
- Average Daily Return %

### Dashboard Visualizations

- NIFTY 50 Close Trend
- 20-Day Moving Average
- Yearly Average Close
- 20-Day Rolling Volatility
- Average Daily Return % by Year
- Year Slicer

### Year Slicer

The dashboard provides filtering by:

**2020 | 2021 | 2022 | 2023 | 2024 | 2025**

---

## 🔍 Dashboard Analysis Areas

### 1. Market Trend Analysis

The NIFTY 50 closing-price trend provides an overview of market movement across the six-year period.

### 2. Moving Average Analysis

The 20-day moving average provides a smoother view of short-term market movement and helps identify trend direction.

### 3. Volatility Analysis

The 20-day rolling volatility highlights periods of increased market uncertainty and larger price fluctuations.

### 4. Return Analysis

Daily return analysis identifies positive and negative market movements and highlights significant daily declines.

### 5. Year-Wise Performance Analysis

Year-wise analysis allows comparison of average closing prices and average daily returns across 2020–2025.

---

## 💡 Key Findings & Insights

- NIFTY 50 showed an overall upward long-term trend between 2020 and 2025.
- 2020 experienced the most prominent volatility spike in the analysis.
- The largest identified daily decline was approximately **-12.98% on 23 March 2020**.
- Later years recorded considerably higher NIFTY 50 closing levels compared with the beginning of the analysis period.
- Daily returns showed significant short-term fluctuations despite the longer-term upward trend.
- The 20-day moving average provides a smoother view of short-term market direction.
- Higher rolling volatility indicates periods of greater market uncertainty and fluctuation.

---

## 📌 Recommendations

- Monitor periods of unusually high market volatility.
- Analyze daily returns together with moving averages.
- Investigate extreme positive and negative market movements.
- Use year-wise comparisons to understand market evolution.
- Use interactive dashboards for faster financial data interpretation.
- Combine multiple analytical indicators rather than relying on a single metric.

---

## 💼 Business Value

This project demonstrates the ability to:

- Work with real-world datasets
- Clean and transform data
- Perform exploratory analysis
- Build analytical metrics
- Query relational databases
- Write SQL queries
- Develop interactive dashboards
- Identify trends and anomalies
- Generate business insights
- Communicate analytical findings

The workflow and analytical techniques demonstrated in this project are applicable to financial analytics, business intelligence and other Data Analyst use cases.

---

## 📁 Project Components

### Data

Six yearly NIFTY 50 CSV files and the consolidated Excel analytical dataset.

### Python

Jupyter Notebook containing data preparation, feature engineering and analysis.

### SQL

PostgreSQL SQL script containing analytical queries.

### Power BI

Interactive Power BI dashboard containing KPIs and market visualizations.

### Screenshots

Screenshots demonstrating the Python, SQL and Power BI analysis.

### README

Complete project documentation explaining the methodology, analysis and findings.

---

## 📂 Project Structure

<pre>
stock-market-analysis/
│
├── Data/
│   ├── NIFTY 50_Historical_PR_01012020to31122020.csv
│   ├── NIFTY 50_Historical_PR_01012021to31122021.csv
│   ├── NIFTY 50_Historical_PR_01012022to31122022.csv
│   ├── NIFTY 50_Historical_PR_01012023to31122023.csv
│   ├── NIFTY 50_Historical_PR_01012024to31122024.csv
│   ├── NIFTY 50_Historical_PR_01012025to31122025.csv
│   └── NIFTY_50_Analysis.xlsx
│
├── Python/
│   └── Stock Market Analysis.ipynb
│
├── SQL/
│   └── Stock Market Analysis.sql
│
├── Power BI/
│   └── Stock Market Analysis.pbix
│
├── Screenshots/
│   ├── 01_PowerBI_Dashboard.png
│   ├── 02_Python_Analysis.png
│   └── 03_SQL_Analysis.png
│
└── README.md
</pre>

---

## 🧠 Skills Demonstrated

### Data Analytics

- Exploratory Data Analysis
- Trend Analysis
- Time-Series Analysis
- KPI Development
- Data Visualization
- Business Insights

### Python

- Pandas
- NumPy
- Matplotlib
- Data Cleaning
- Feature Engineering

### SQL

- PostgreSQL
- Data Filtering
- Sorting
- Aggregation
- Analytical Queries

### Power BI

- KPI Cards
- Line Charts
- Column Charts
- Slicers
- Dashboard Design
- Interactive Reporting

---

## 🔄 End-to-End Workflow

**Raw Data → Python Cleaning → Feature Engineering → Python Analysis → PostgreSQL → SQL Analysis → Power BI Dashboard → Insights → GitHub Portfolio**

---

## 🏁 Project Outcome

The project successfully transformed six years of historical NIFTY 50 data into a complete analytical solution consisting of:

- Cleaned market data
- Engineered financial metrics
- Python analysis
- PostgreSQL database
- SQL analysis
- Market decline analysis
- Power BI dashboard
- Business insights
- GitHub documentation

---

## ⭐ Project Highlights

### 1,492 Market Records

The consolidated dataset contains **1,492 historical NIFTY 50 observations**.

### Six Years of Data

The project covers:

**2020 – 2025**

### Six Analytical Metrics

- Daily Range
- Daily Return %
- 20-Day Moving Average
- 50-Day Moving Average
- 20-Day Rolling Volatility
- Cumulative Return %

### Multiple Analytics Technologies

The project integrates:

**Python + PostgreSQL + SQL + Power BI + Excel**

### Complete Analytics Workflow

The project demonstrates the complete journey from raw market data to analytical insights and dashboard reporting.

---

## 🎓 Portfolio Relevance

This project is designed as a practical **Data Analyst portfolio project** and demonstrates experience across multiple stages of a real-world analytics workflow.

The project demonstrates:

**Data Collection → Data Cleaning → Data Transformation → Feature Engineering → Exploratory Analysis → SQL Analysis → Dashboard Development → Insight Generation → Business Communication**

The combination of Python, SQL, PostgreSQL and Power BI demonstrates practical analytical and business intelligence capabilities.

---

## ⚠️ Data Interpretation & Limitations

- The analysis is based on historical market data.
- Historical performance does not guarantee future performance.
- The analysis focuses on the NIFTY 50 index rather than individual stocks.
- The project primarily focuses on price, returns, moving averages and volatility.
- Economic events, news sentiment and fundamental company data are not included.
- The project does not attempt to predict future market prices.
- This project is intended for analytical and portfolio purposes and not as investment advice.

---

## 📌 Project Summary

The **NIFTY 50 Stock Market Analysis** project demonstrates a complete end-to-end Data Analytics workflow using six years of historical market data.

Python was used for data cleaning, transformation, feature engineering and visualization.

PostgreSQL was used to store the analytical dataset, while SQL was used to identify market patterns and major daily declines.

Power BI was then used to transform the processed data into an interactive dashboard containing KPIs, market trends, moving averages, volatility analysis and year-wise comparisons.

The analysis identified significant market fluctuations, major daily declines and an overall upward long-term movement in NIFTY 50 closing levels.

Overall, the project demonstrates how raw financial data can be transformed into structured information, analytical insights and an interactive business intelligence dashboard.

---

## 🏁 Final Summary

This project successfully demonstrates:

- Data Collection
- Data Cleaning
- Data Transformation
- Feature Engineering
- Exploratory Data Analysis
- Python Visualization
- PostgreSQL Database Management
- SQL Analysis
- Financial Trend Analysis
- Volatility Analysis
- KPI Development
- Power BI Dashboard Development
- Business Insight Generation
- Data Storytelling
- GitHub Portfolio Development

The project provides a practical demonstration of using **Python + SQL + PostgreSQL + Power BI** together to solve a real-world analytical problem.

---

## 👩‍💻 Author

### Priyanka Patel

**Data Analyst | Excel | SQL | Power BI | Python | Tableau**

Passionate about transforming raw data into meaningful insights through data cleaning, analytics, visualization and business intelligence.

---

## 🎯 Final Project Objective

The objective of this project was to build a complete, professional and portfolio-ready **NIFTY 50 Stock Market Analytics solution** demonstrating practical Data Analyst capabilities from raw data collection to final dashboard and business insights.

**Python + PostgreSQL + SQL + Power BI + Excel + GitHub**

---

## 🙏 Thank You

Thank you for reviewing my **NIFTY 50 Stock Market Analysis** project.

This project demonstrates my practical application of:

**Python | SQL | PostgreSQL | Power BI | Excel | Data Analytics | Data Visualization**

I hope this project demonstrates my ability to transform raw data into meaningful insights and build complete, business-focused analytical solutions.

### ⭐ Thank You!
