<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,50:1e40af,100:3b82f6&height=200&section=header&text=Pranav%20Grover&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Data%20Analyst%20%7C%20Business%20Analytics%20and%20AI&descAlignY=55&descSize=18"/>
</div>

<div align="center">

Data analyst in Dallas, TX. SQL, Python, and Power BI/Tableau, mostly on the messy parts — getting data clean, consolidated, and into a dashboard someone will actually use.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pranav-grover-utd/?isSelfProfile=false)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pranavg0520@outlook.com)
[![Location](https://img.shields.io/badge/Dallas%2C%20TX-Based-4CAF50?style=for-the-badge&logo=google-maps&logoColor=white)](https://www.google.com/maps/place/Dallas,+TX)

</div>

---

## About

I just finished my MS in Business Analytics and AI at UT Dallas (graduated May 2026, GPA 3.65). Before grad school I spent about three years as a data analyst at Elite Marque, and this past fall I interned at Veracyte working on revenue-cycle analytics.

Most of my work falls in the same place: data that lives in too many systems, doesn't agree with itself, and needs to end up in a report leadership can trust. I write a lot of SQL, do the cleanup in Python, and build the dashboards in Power BI and Tableau. I'm currently looking for full-time data analyst roles.

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
    2019-2023 : B.E. Electrical Engineering
              : GPA 3.4
    section Work
    2021-2024 : Data Analyst - Elite Marque
              : Standardized 80K+ records
              : Built automated dashboards
    section Grad school
    2024-2026 : MS Business Analytics & AI
              : UT Dallas - GPA 3.65
    2025 : Data Analyst Intern - Veracyte
         : Built a 2M+ record data mart
         : Worked across 4 teams
    section Now
    2026 : MS completed
         : Looking for data analyst roles
```

---

## Experience

### Veracyte — Data Analyst Intern (Aug 2025 – Nov 2025)

Worked on revenue-cycle analytics for the billing and claims side.

- Built a Snowflake data mart consolidating 2M+ claims and billing records so denial management, reimbursement, and turnaround-time metrics came from one place instead of four separate team spreadsheets.
- Built 5 Power BI and Tableau dashboards (denial rates, payer mix, aging buckets) that cut the weekly manual reporting time by about 20%.
- Wrote SQL validation checks across 3 source systems and cut data mismatches by ~30%.
- Set up 8 automated quality checks with alerting, so bad data got caught before it hit a report.
- Pulled together the weekly revenue-cycle numbers for the ops team to help them decide which payer escalations and resubmissions to chase first.

### Elite Marque — Data Analyst (Jun 2021 – Jun 2024)

Mostly data standardization and getting reporting off of manual spreadsheets.

- Cleaned and standardized 80K+ records across 4 business units in Python and SQL, which dropped reporting errors by about 35%.
- Built Power BI and Excel dashboards (20+ visuals) and automated enough of the reporting to cut the manual effort by roughly 25%.
- Delivered the weekly and monthly performance reports the ops and revenue teams ran on.
- Tracked down and fixed 3 pipeline issues that were quietly corrupting downstream reports, and worked with ops to fix the data-entry problems upstream.

---

## Projects

### Automobile price prediction & customer segmentation

Predicting used-car prices and grouping customers for targeted pricing.
- Trained an ensemble (Random Forest + Gradient Boosting) on ~800K records, landing around 96% accuracy.
- Used K-Means and hierarchical clustering for segmentation and turned the output into a handful of pricing tiers.

Python, SQL, scikit-learn.

### Az National Trucking — fleet safety analytics (big data)

Looking at unsafe-driving events across a 100-driver fleet.
- Loaded 8,000+ geolocation records into HDFS on Cloudera Hadoop, queried with Hive and Impala, and connected Tableau over ODBC.
- Built Tableau dashboards to find geographic hotspots and risk scores by driver and truck model, then turned that into route and coaching recommendations.

Hadoop, Hive, Impala, Tableau.

### Uber trip analysis — Power BI

A dashboard for ride-sharing trip patterns.
- Analyzed booking trends, revenue, and trip/payment/vehicle types.
- Built KPI cards and measure selectors, plus time-series views (10-minute area charts, day-wise trends, hourly heatmaps).

Power BI, DAX, SQL.

### U.S. nursing homes financial analysis (2015–2021)

Financial performance and COVID-19 impact using CMS data.
- Looked at net income, staffing, and penalties across facilities of different sizes.
- Found that larger facilities saw a 1,178% jump in net income during COVID, alongside the penalty trends.

Python, pandas, matplotlib, seaborn.

### F1 data analysis — SQL & Tableau

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
| B.E. Electrical & Electronics | Bharati Vidyapeeth's College of Engineering | 3.4/4.0 | 2019 – 2023 |

</div>

Coursework worth mentioning: machine learning for business, big data analytics, predictive modeling, data mining, and BI.

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
