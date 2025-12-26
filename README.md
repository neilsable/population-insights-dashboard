# population-insights-dashboard
Synthetic UK population &amp; financial analytics dataset with an Excel dashboard built from scratch.

# Population & Financial Insights Dashboard (Excel)

## Overview

This project is a fully self‑designed analytics solution built entirely from scratch — including all **raw data**, **calculations**, and **dashboard design**. I manually created a synthetic dataset representing:

- Demographics (gender, age, education, kids)
- Income and debt levels
- Net worth and investments
- Car and house asset values
- Professions and sectors (Health, Construction, Technology, Agriculture, Social Service, Education)
- UK counties/territories

The goal of this project is to demonstrate my ability to:

- Design realistic, structured datasets from zero
- Define meaningful KPIs and analytical questions
- Build an end‑to‑end Excel dashboard for insights
- Present complex information in a clear, stakeholder‑friendly way

---

## Key questions this dashboard answers

- **How many men vs women are in the population?**
- **What is the average age and income across the dataset?**
- **How does income differ by sector (Health, Construction, Technology, etc.)?**
- **How does average income vary by county/territory?**
- **What is the average value of a car per person?**
- **What percentage of people have debts greater than their annual income?**
- **What is the average age of people whose net worth is higher than their annual income?**
- **How many people have debts greater than a given threshold (X)?**
- **How many people have less than a certain percentage of their mortgage left to pay?**

These questions mirror real‑world use cases in financial analysis, public policy, risk assessment, and market research.

---

## Skills demonstrated

### 1. Data creation and modelling

- **Manual dataset design:** I created all the data myself, simulating realistic distributions for age, income, assets, counties, professions, and education.
- **Structured modelling:** Separated and organised data into logical dimensions:
  - Counties / territories
  - Field of work / sector
  - Demographics (gender, age, education, kids)
  - Financials (income, debts, assets, net worth)
- **Analysis‑ready structure:** Designed the layout so it can be easily used for pivot tables, charts, and KPI calculations.

### 2. Analytical thinking and KPI design

- **Men vs Women:** Count of individuals by gender.
- **Average Age & Income:** Overall and segmented.
- **Average Car Value:** Per person and/or per household.
- **Debt analysis:**
  - Percentage of people with **debts greater than their annual income**
  - Number of people with **debts greater than a configurable X value**
  - Number of people with **less than X% of their mortgage left to pay**
- **Net worth insights:**
  - Average age of people whose **net worth exceeds their income**
  - Value of debts vs value of assets
- **Territory & sector analytics:**
  - Average income per county
  - Average income per sector/field of work

These KPIs are designed to tell a story about financial health, risk, and distribution across regions and professions.

### 3. Excel dashboard design

- **Dedicated dashboard sheet** summarising:
  - Number of men vs women
  - Average age
  - Number of people in each profession
  - Average income
  - Average car value
  - Debt‑related metrics
  - Average income per sector
  - Average income per territory
  - Net worth vs income insights
- **Charts and visuals** to highlight:
  - Sector distribution
  - Territorial income differences
  - Debt and risk indicators

The layout is focused on clarity and quick interpretation for business or policy stakeholders.

### 4. Excel / BI techniques used

- **Formulas** for:
  - Averages (e.g. `AVERAGE`, `AVERAGEIF`, `AVERAGEIFS`)
  - Counts and conditions (e.g. `COUNTIF`, `COUNTIFS`)
  - Percentage calculations (debt vs income, mortgage left to pay)
  - Net worth vs income comparisons
- **Pivot tables** (where used) to aggregate:
  - Income by sector
  - Income by county
  - Gender distributions
- **Formatting and layout**:
  - Clear separation of raw data, calculations, and dashboard
  - Consistent number formats (currency, percentages)
  - Headings and grouping for readability

> Note: Exact formulas and structure can be explored directly in the Excel file.

---

## File structure

population-insights-dashboard/
│
├── Population Analysis.xlsx      # Main Excel model and dashboard
└── screenshots/
    ├── dashboard-overview.png    # Main dashboard view
    ├── raw-data.png              # Raw data sheet preview
    ├── sector-income.png         # Income by field of work
    └── territory-income.png      # Income by county/territory


## How to use this project
Download the Excel file

- Click on Population Analysis.xlsx in this repository
- Click Download
- Open in Excel
- Use Microsoft Excel (desktop recommended for best performance)
- Explore the dashboard
- Go to the Dashboard sheet to see the key metrics and charts.
- Use any slicers or filters (if present) to explore segments.
- Explore the raw data
- Open the Raw Data or equivalent data sheet.

## Review fields such as:

- County
- Gender
- Age
- Education
- Income
- Debts
- Assets
- Field of work
- Adapt or extend

## The dataset is ideal for practising:

- New KPIs
- Additional charts
- Power Query / Power Pivot integration
- Migration into tools like Power BI or SAP Analytics Cloud
- Potential future enhancements
- Build a Power BI or SAP Analytics Cloud version of this dashboard using the same dataset.
- Add time‑based elements (e.g. yearly changes in income or debt).
- Introduce scenarios (e.g. interest rate changes, economic shocks).
- Add more demographic variables (marital status, employment status, etc.).
- Deploy a web‑based demo using Python or Streamlit for interactive exploration.

## About me:
- ** I created this project to demonstrate end‑to‑end analytics capability:

- Designing and modelling a dataset from scratch
- Translating real‑world questions into metrics and KPIs
- Building a clear and insightful Excel dashboard
- Thinking like a business stakeholder, not just a technical analyst

If you’d like to discuss this project or similar work, feel free to connect with me.
