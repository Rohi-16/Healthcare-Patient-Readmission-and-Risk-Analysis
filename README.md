# Healthcare Patient Readmission & Risk Analysis

![Healthcare Dashboard](Hospital%20Dashboard.png)

## Project Overview

An end-to-end healthcare analytics project analyzing hospital encounters to identify patterns associated with 30-day patient readmissions.

The project uses SQL for data analysis and Power BI to turn the findings into an interactive dashboard.

## Tech Stack

- SQL
- DuckDB
- Python / Pandas
- Power BI
- Kaggle Notebook

## Data Source

**Diabetes 130-US Hospitals for Years 1999–2008**

[Kaggle Dataset](https://www.kaggle.com/datasets/brandao/diabetes)

The dataset contains approximately 101,766 hospital encounters from 130 US hospitals.

## Business Problem

Hospital readmissions are an important healthcare performance metric. The goal of this project was to understand:

- Which patient/encounter characteristics are associated with higher 30-day readmission rates?
- How does previous healthcare utilization relate to readmissions?
- How do factors such as age, length of stay, and number of diagnoses relate to readmission?

## Key Analysis

Using SQL, I analyzed:

- 30-day readmission rate
- Age-wise readmission patterns
- Prior inpatient utilization
- Emergency and outpatient visits
- Length of hospital stay
- Number of diagnoses
- Medical specialty
- HbA1c results
- Medication changes
- Healthcare utilization segments

## Key Insights

- **101,766** total hospital encounters were analyzed.
- **11,357** encounters resulted in readmission within 30 days.
- The overall observed 30-day readmission rate was **11.16%**.
- Higher healthcare utilization segments showed higher observed 30-day readmission rates.
- Encounters with more prior inpatient visits generally showed higher observed readmission rates.

## Dashboard

The Power BI dashboard provides a single-page view of the key KPIs, readmission patterns, utilization segments, and diagnostic breakdowns.

> The analysis is descriptive and shows associations in the dataset; it is not a clinical prediction model.

## Project Workflow

**Dataset → SQL Analysis → Derived Metrics → Power BI Dashboard**
