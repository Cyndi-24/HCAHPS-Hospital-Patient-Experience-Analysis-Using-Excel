# HCAHPS-Hospital-Patient-Experience-Analysis-Using-Excel

## INTRODUCTION

The Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) is a nationally standardised survey used to measure patients' experiences with hospital care in the United States.

Patient experience data provides valuable insights into areas such as communication, cleanliness, responsiveness, and overall satisfaction with healthcare services. Understanding these insights can help healthcare organisations identify strengths and areas where improvements may be needed.

## PROBLEM STATEMENT

Healthcare organisations collect large amounts of patient experience data, but raw survey results alone may not provide a clear understanding of performance across facilities.

This project focuses on analysing HCAHPS data using Microsoft Excel to identify patterns in patient ratings, survey responses, and hospital performance, helping highlight areas of strength and opportunities for improvement.

## BUSINESS QUESTIONS

This analysis was guided by the following questions:

1. What is the overall patient experience performance across hospitals based on HCAHPS scores?

2. How do patient experience ratings vary across different states and facilities?

3. Which states demonstrate the highest and lowest patient star ratings?

4. How are hospitals distributed across different patient rating categories?

5. Which patient experience areas contribute most to positive or negative patient experiences?

6. Which areas of healthcare communication show the greatest opportunities for improvement?

7. Is there a relationship between patient survey response rates and overall patient ratings?

8. How does survey participation vary across states, and which states record the highest number of completed surveys?

## DATA SOURCE

The dataset used for this analysis was obtained from the Centers for Medicare & Medicaid Services (CMS) Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) survey data.

The HCAHPS survey collects information on patients’ experiences with hospital care, covering areas such as communication, cleanliness, responsiveness, medication information, and overall hospital ratings.

The dataset contains hospital-level patient experience measures used to analyse performance patterns across facilities and states. 

## TOOLS USED

- Microsoft Excel
- Power Query

## SKILLS DEMONSTRATED

- Healthcare data analysis
- Data cleaning and quality validation
- Interactive Excel dashboard development
- Pivot tables and pivot chart creation
- KPI development and performance analysis
- Patient experience trend analysis
- Data storytelling and insight communication

## DATA PREPARATION

The HCAHPS dataset was prepared using Power Query in Excel to improve data quality and ensure it was suitable for analysis.

The preparation process involved:

- Loading the dataset into Power Query and creating a duplicate query before cleaning.
- Cleaning text fields by applying Trim to remove unnecessary spaces.
- Identifying and removing duplicate records.
- Handling non-numeric values such as "Not Available" and "Not Applicable" by replacing them with null values where appropriate.
- Changing numeric fields to whole number format.
- Converting date fields into the correct date format.
- Reviewing blank and null values to ensure data consistency.

The cleaned dataset was then used to create pivot tables, pivot charts, and an interactive Excel dashboard.

## DASHBOARD DEVELOPMENT

After preparing the dataset, an interactive Excel dashboard was created to present key patient experience metrics and performance patterns.

The dashboard was developed using Excel Pivot Tables, Pivot Charts, and interactive filtering features to allow users to explore hospital performance across different measures.

### Key Performance Indicators (KPIs)

The dashboard includes seven key metrics:

- Total Facilities
- Total States
- Average Patient Star Rating
- Average HCAHPS Score
- Average Survey Response Rate
- Total Completed Surveys
- Experience Performance Gap

### Dashboard Components

The dashboard includes:

- KPI summary cards for overall performance tracking.
- Patient experience performance comparison.
- State and facility-level rating analysis.
- Patient experience gap analysis.
- Survey participation and response pattern analysis.
