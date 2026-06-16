<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,50:1e40af,100:3b82f6&height=200&section=header&text=Pranav%20Grover&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Data%20and%20Business%20Analyst%20%7C%20Analytics%20and%20AI&descAlignY=55&descSize=18"/>
</div>

<div align="center">

Data & business analyst in San Francisco, CA. SQL, Python, and Power BI/Tableau across operations, marketing, finance, and revenue reporting, mostly on the messy parts, getting data clean, consolidated, and into a dashboard someone will actually use.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pranav-grover-utd/?isSelfProfile=false)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gropranav0520@gmail.com)
[![Location](https://img.shields.io/badge/San%20Francisco%2C%20CA-Based-4CAF50?style=for-the-badge&logo=google-maps&logoColor=white)](https://www.google.com/maps/place/San+Francisco,+CA)

![Open to Work](https://img.shields.io/badge/Open%20to-Data%20%26%20Business%20Analyst%20Roles-2ea44f?style=for-the-badge)
![Profile Views](https://komarev.com/ghpvc/?username=Pranav0520&color=1e40af&style=for-the-badge&label=Profile+Views)

</div>

---

## About

I just finished my MS in Business Analytics and AI at UT Dallas (graduated May 2026, GPA 3.65). Before grad school I spent about three years as a data analyst at Elite Marque; in fall 2025 I did a co-op at Veracyte on revenue-cycle analytics, and this spring I worked as a business analyst co-op at UT Dallas's Davidson Gundy Alumni Center.

Most of my work falls in the same place: data that lives in too many systems, doesn't agree with itself, and needs to end up in a report leadership can trust. I write a lot of SQL, do the cleanup in Python, and build the dashboards in Power BI and Tableau. I'm currently looking for full-time data and business analyst roles.

---

## How I approach a project

```mermaid
graph TB
    A[Understand the question] --> B[Engineering]
    A --> C[Stakeholders]

    B --> D[Pull & consolidate the data]
    B --> E[Modeling & analysis]

    C --> F[Reporting]
    C --> G[Working with the teams]

    D --> H[ETL pipelines]
    D --> I[Quality checks]

    E --> J[Predictive models]
    E --> K[Statistical analysis]

    F --> L[Dashboards]
    G --> M[Day-to-day ops]

    H --> N[A decision someone can act on]
    I --> N
    J --> N
    K --> N
    L --> N
    M --> N

    style A fill:#1e3a8a,stroke:#3b82f6,stroke-width:3px,color:#fff
    style N fill:#15803d,stroke:#22c55e,stroke-width:3px,color:#fff
    style B fill:#1e40af,stroke:#60a5fa,stroke-width:2px,color:#fff
    style C fill:#1e40af,stroke:#60a5fa,stroke-width:2px,color:#fff
```

---

## Timeline

```mermaid
timeline
    title Path so far
    section Foundation
    2019-2023 : B.Tech. Electrical & Electronics
              : GPA 3.4
    section Work
    2021-2024 : Data Analyst - Elite Marque
              : Standardized 90K+ records
              : Built automated dashboards
    section Grad school
    2024-2026 : MS Business Analytics & AI
              : UT Dallas - GPA 3.65
    2025 : Data Analyst Co-op - Veracyte
         : Built a 2M+ record data mart
         : Worked across 4 teams
    section Now
    2026 : Business Analyst Co-op - UT Dallas
         : Python ETL for 10K+ alumni records
         : MS completed
         : Looking for data & business analyst roles
```

---

## Experience

### UT Dallas, Davidson Gundy Alumni Center · Business Analyst Co-op (Jan 2026 – May 2026)

Advancement reporting for the alumni operations team.

- Built Python ETL pipelines to extract, clean, and standardize 10,000+ alumni records from LinkedIn profile exports, improving dataset accuracy by about 30%.
- Found unindexed joins in legacy Microsoft Access databases and rebuilt the query logic, improving query performance by ~40% and speeding up report delivery.

### Veracyte · Data Analyst Co-op (Aug 2025 – Nov 2025)

Worked on revenue-cycle analytics for the billing and claims side.

- Built a Snowflake data mart consolidating 2M+ claims and billing records so denial management, reimbursement, and turnaround-time metrics came from one place instead of four separate team spreadsheets.
- Built 5 Power BI and Tableau dashboards (denial rates, payer mix, aging buckets) with reusable DAX measures that cut manual reporting effort by about 40%.
- Wrote 8 automated SQL validation rules with threshold alerts across 3 source systems, improving data reliability by ~30% so bad data got caught before it hit a report.
- Automated the weekly revenue-cycle summaries by pairing Python with generative AI to turn raw Power BI KPI outputs into narrative leadership briefs, cutting report prep time by ~50%.

### Elite Marque · Data Analyst (Jun 2021 – Jun 2024)

Mostly data standardization and getting reporting off of manual spreadsheets.

- Cleaned and standardized 90K+ customer and sales records across 4 business units in Python and SQL, which dropped reporting errors by about 35%.
- Built Power BI and Excel dashboards (20+ visuals) and automated enough of the reporting to cut the manual effort by roughly 25%.
- Tracked down and fixed 3 pipeline issues that were quietly corrupting downstream reports, and worked with ops to fix the data-entry problems upstream.
- Ran EDA on revenue and churn across the 4 units, flagged pricing and marketing gaps in monthly leadership reviews, and helped drive about 15% revenue growth across client accounts.

---

## Projects

### Automobile price prediction & customer segmentation

Predicting used-car prices and grouping customers for targeted pricing.
- Trained an ensemble (Random Forest + Gradient Boosting) on ~800K records, landing around 96% accuracy.
- Used K-Means and hierarchical clustering for segmentation and turned the output into a handful of pricing tiers.

Python, SQL, scikit-learn.

### Az National Trucking · big data governance pipeline

Centralizing fleet data for a trucking company with no single view across 100+ drivers.
- Loaded 8,000+ GPS records into HDFS on Cloudera Hadoop, queried with Hive and Impala, and connected Tableau over ODBC.
- Built Tableau dashboards for geographic hotspots and per-driver/truck performance, turning that into route recommendations that cut route time by about 12%.

Hadoop, Hive, Impala, Tableau.

### Uber trip analysis · Power BI

A dashboard for ride-sharing trip patterns.
- Analyzed booking trends, revenue, and trip/payment/vehicle types.
- Built KPI cards and measure selectors, plus time-series views (10-minute area charts, day-wise trends, hourly heatmaps).

Power BI, DAX, SQL.

### U.S. nursing homes financial analysis (2015–2021)

Financial performance and COVID-19 impact using CMS data.
- Looked at net income, staffing, and penalties across facilities of different sizes.
- Found that larger facilities saw a 1,178% jump in net income during COVID, alongside the penalty trends.

Python, pandas, matplotlib, seaborn.

### F1 data analysis · SQL & Tableau

Formula 1 race data from 1953–2020.
- Designed a relational schema for race results, drivers, teams, and circuits.
- Wrote queries for driver/team performance and historical trends, and built Tableau dashboards to explore it.

SQL, Tableau.

### Cohort analysis with Python

Retention and lifetime-value analysis.
- Built cohort workflows in pandas to track user groups over time.
- Made retention heatmaps and curves to compare behavior across cohorts.

Python, pandas, Jupyter.

---

## Tech I use

<div align="center">

### Data & analytics

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

### BI & visualization

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)

### Databases & big data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apache-hadoop&logoColor=black)
![Hive](https://img.shields.io/badge/Hive-FDEE21?style=for-the-badge&logo=apache-hive&logoColor=black)

### ML

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

</div>

---

## Education

<div align="center">

| Degree | School | GPA | Years |
|:-------|:-------|:----|:------|
| M.S. Business Analytics & AI | University of Texas at Dallas | 3.65/4.0 | 2024 – 2026 |
| B.Tech. Electrical & Electronics | Bharati Vidyapeeth's College of Engineering | 3.4/4.0 | 2019 – 2023 |

</div>

Coursework worth mentioning: machine learning for business, big data analytics, predictive modeling, data mining, and BI.

---

## GitHub

<div align="center">

![Pranav's GitHub stats](https://github-readme-stats.vercel.app/api?username=Pranav0520&show_icons=true&hide_border=true&title_color=3b82f6&icon_color=3b82f6&text_color=8b949e&bg_color=0d1117)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Pranav0520&layout=compact&hide_border=true&title_color=3b82f6&text_color=8b949e&bg_color=0d1117)

</div>

---

## At a glance

```mermaid
mindmap
  root((Pranav Grover))
    Data work
      ETL pipelines
      Snowflake
      Data modeling
      Quality checks
      SQL
    BI
      Power BI
      Tableau
      DAX
      KPI design
    Programming
      Python
      R
      SQL
      scikit-learn
    Analytics
      A/B testing
      Forecasting
      Cohort analysis
```

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b82f6,50:1e40af,100:1e3a8a&height=120&section=footer"/>

</div>
