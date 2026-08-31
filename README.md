
# HCAHPS-Hospital-Patient-Experience-Analysis-Using-Excel

## INTRODUCTION

The Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) is a nationally standardised survey used to measure patients' experiences with hospital care in the United States.

Patient experience data provides valuable insights into areas such as communication, cleanliness, responsiveness, and overall satisfaction with healthcare services. Understanding these insights can help healthcare organisations identify strengths and areas where improvements may be needed.

## PROBLEM STATEMENT

Healthcare organisations collect large amounts of patient experience data, but raw survey results alone may not provide a clear understanding of performance across facilities.

This project focuses on analysing HCAHPS data using Microsoft Excel to identify patterns in patient ratings, survey responses, and hospital performance, helping highlight areas of strength and opportunities for improvement.


## BUSINESS QUESTIONS

This analysis was guided by the following questions:

1. Which areas of patient experience receive the highest and lowest ratings across hospitals?

2. What factors contribute to lower medication communication performance?

3. Which patient experience areas have the highest negative response rates?

4. Is there a relationship between survey response rates and overall patient ratings?

5. Which states demonstrate the highest patient experience ratings?

6. Which states have lower patient experience ratings and may require further attention?

7. How are hospitals distributed across different patient star rating categories?

8. Which states have the highest number of completed patient surveys?


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

## ANALYSIS & VISUALIZATION

The dashboard consists of two pages.
 Survey Performance Analysis 


* Pattern and Response Analysis

  
### KPI Overview

The dashboard provides an overview of hospital patient experience performance using HCAHPS survey data. The analysis covers **2,302,474 completed surveys** collected across **4,792 healthcare facilities in 56 states** in US, providing a broad view of patient experiences across different locations.

Overall patient experience performance was assessed using key measures, including an **average patient star rating of 3.27** and an **average survey response rate of 22.95%**. The patient star rating provides an indication of overall patient satisfaction, while the response rate provides context on patient participation across healthcare facilities before exploring differences in patient experience areas, states, and facilities.

### 1. Which areas of patient experience receive the highest and lowest ratings across hospitals?

**Finding:**  
Nurse communication recorded the highest patient experience score, followed by doctor communication. Medication communication had the lowest score among the measured experience areas.

**Insight:**  
Patients reported stronger experiences with direct interactions with healthcare staff, while medication-related communication appears to be a weaker area of the overall patient experience.

