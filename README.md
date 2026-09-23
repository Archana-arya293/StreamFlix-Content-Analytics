# StreamFlix Content Analytics

## Project Overview

StreamFlix Content Analytics is an end-to-end Data Analytics project focused on understanding subscriber behavior, content performance, engagement, customer churn, and content licensing.

The project covers data cleaning, exploratory data analysis, KPI calculation, and interactive Power BI dashboard development.

## Business Objectives

- Analyze subscriber engagement and churn
- Measure content consumption and completion
- Identify high-performing genres and titles
- Understand subscriber and device behavior
- Analyze customer ratings and review sentiment
- Compare Originals vs. Licensed content
- Evaluate content performance against licensing investment
- Identify upcoming license expiries

## Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- SQL
- Power BI
- DAX
- Power Query
- Excel
- Data Visualization

## Project Workflow

### Phase 1 — Data Cleaning & Quality

- Loaded and profiled the project datasets
- Identified data-quality issues
- Validated data against the issue log
- Cleaned and prepared datasets for analysis

### Phase 2 — Exploratory Data Analysis

Performed exploratory analysis to understand:

- Subscriber behavior
- Viewing patterns
- Content performance
- Ratings and reviews
- Watchlist activity
- Subscription patterns

### Phase 3 — KPI Analysis

Key calculated KPIs include:

| KPI | Result |
|---|---:|
| Total Watch Hours | 3,333,467.73 |
| Active Rate | 74.66% |
| Churn Rate | 25.34% |
| Average Completion Rate | 65.31% |
| Monthly Recurring Revenue | $175,868.51 |
| ARPU | $15.70 |
| Avg. Watch Time per Active Subscriber | 297.66 hours |
| Watchlist Conversion | 46.23% |
| Hit Concentration | 30.99% |
| Originals Share of Hours | 27.17% |

### Phase 4 — Power BI Dashboard

The Power BI dashboard contains five analytical pages:

#### 1. Engagement Overview
- Churn Rate
- Completion Rate
- Total Subscribers
- Watch Hours by Subscription Plan
- Monthly Watch-Hours Trend

#### 2. Content Performance
- Completion Rate by Genre
- Watch Hours by Genre
- Top 10 Titles by Watch Hours

#### 3. Subscriber Insights
- New Subscribers per Month
- Subscribers by Plan Type
- Top 10 Countries by Subscribers

#### 4. Experience
- Device Breakdown
- Rating Distribution
- Review Sentiment Analysis

#### 5. Catalogue & Investment
- Originals vs. Licensed Content
- Watch Hours per $1K Spend by Genre
- Upcoming License Expiries

## Key Findings

- The overall churn rate is 25.34%, while the active rate is 74.66%.
- Average content completion is 65.31%.
- Drama has the highest watch-hour volume among the major genres shown in the dashboard.
- Standard is the largest subscription plan by subscriber count.
- Smart TV represents the highest viewing activity among the devices shown.
- Positive reviews represent the largest sentiment category.
- Licensed content represents the larger share of the catalogue.
- Animation shows the highest watch hours per $1K licensing spend among the genres shown.

## Project Files

```text
StreamFlix-Content-Analytics/
│
├── notebooks/
│   ├── Phase1_Data_Cleaning_StreamFlix_Archana_Arya.ipynb
│   ├── Phase2_EDA_Archana_Arya.ipynb
│   └── Phase3_KPIs_Archana_Arya.ipynb
│
├── dashboard/
│   └── Phase4_Dashboard_Archana_Arya.pbix
│
├── report/
│   └── Phase4_Report_Archana_Arya_Final.pdf
│
└── README.md
Project Outcome

This project demonstrates an end-to-end analytics workflow from raw data quality assessment and exploratory analysis through KPI development and interactive Power BI reporting.

The final dashboard provides a business-focused view of subscriber engagement, content performance, customer experience, and catalogue investment.

Author

Archana Arya

Data Analytics | Power BI | SQL | Python | Excel
