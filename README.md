# HCAHPS-Hospital-Patient-Experience-Analysis-Using-Excel

![image alt](https://github.com/Cyndi-24/HCAHPS-Hospital-Patient-Experience-Analysis-Using-Excel/blob/main/Portfolio_Images/image.png)

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

3. Is there a relationship between survey response rates and overall patient ratings?

4. Which states demonstrate the highest patient experience ratings?

5. Which states have lower patient experience ratings and may require further attention?

6. How are hospitals distributed across different patient star rating categories?

7.  Which states have the highest number of completed patient surveys?


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

![image alt](https://github.com/Cyndi-24/HCAHPS-Hospital-Patient-Experience-Analysis-Using-Excel/blob/main/Portfolio_Images/data_cleaning.png)

## ANALYSIS & VISUALIZATION

The dashboard consists of two pages.
* Survey Performance Analysis 


* Pattern and Response Analysis

  
### KPI Overview

The dashboard provides an overview of hospital patient experience performance using HCAHPS survey data. The analysis covers **2,302,474 completed surveys** collected across **4,792 healthcare facilities in 56 states** in US, providing a broad view of patient experiences across different locations.

Overall patient experience performance was assessed using key measures, including an **average patient star rating of 3.27** and an **average survey response rate of 22.95%**. The patient star rating provides an indication of overall patient satisfaction, while the response rate provides context on patient participation across healthcare facilities before exploring differences in patient experience areas, states, and facilities.

### 1. Which areas of patient experience receive the highest and lowest ratings across hospitals?

**Finding:**  
Nurse communication recorded the highest patient experience score, followed by doctor communication. Medication communication had the lowest score among the measured experience areas.

**Insight:**  
Patients reported stronger experiences with direct interactions with healthcare staff, while medication-related communication appears to be a weaker area of the overall patient experience. While the analysis identifies this as a weaker area, additional operational data would be needed to determine the specific causes behind this gap.

### 2. What factors contribute most to medication communication gaps?

**Finding:**  
Patients reported the largest communication gap in understanding medication side effects (**30.07%**), followed by general medication explanations (**19.26%**) and medication purpose (**9.54%**).

**Insight:**  
The findings suggest that patients may need clearer information about what to expect from their medications, particularly regarding possible side effects and overall medication guidance.

### 3. Is there a relationship between survey response rates and patient star ratings?

**Finding:**  
The analysis shows that facilities with higher survey response rates do not consistently record higher patient star ratings, suggesting that response participation alone does not determine patient experience performance.

**Insight:**  
Patient satisfaction appears to be influenced by factors beyond survey participation, meaning hospitals should focus on the quality of patient experiences rather than response volume alone.

### 4. How are healthcare facilities distributed across different patient star rating categories?

**Finding:**  
The majority of facilities were concentrated in the middle rating categories. A total of **2,698 facilities** received a **3-star rating**, while **2,420 facilities** received a **4-star rating** and **1,881 facilities** with a **2-star rating**In comparison, fewer facilities received the highest and lowest ratings, with **1,145 facilities** receiving a **5-star rating** and **472 facilities** receiving a **1-star rating**.

**Insight:**  
Most healthcare facilities fall within the moderate-to-high patient experience rating categories, suggesting generally positive patient experiences across the dataset. However, the smaller group of lower-rated facilities may represent opportunities for targeted review and improvement.

### 5. Which states demonstrate the highest patient experience ratings?

**Finding:**  
Wisconsin and South Dakota recorded the highest average patient star ratings among the states analysed, with both achieving ratings close to **4.0**. Other states, including Nebraska, Minnesota, and Idaho, also recorded relatively strong patient experience ratings.

**Insight:**  
Patient experience ratings vary across states, showing differences in reported patient satisfaction levels across locations. However, the dataset does not include additional factors needed to determine the reasons behind these differences.

### 6. Which states recorded the lowest patient experience ratings?

**Finding:**  
The states and regions with the lowest average patient star ratings included **Puerto Rico, District of Columbia, and U.S. Virgin Islands**.

**Insight:**  
The variation in patient ratings across locations highlights differences in reported patient experiences. However, the available data does not provide enough information to determine the operational or demographic factors contributing to these differences.

### 7. Which states recorded the highest number of completed patient surveys?

**Finding:**  
The analysis shows that survey participation varied across states, with some states recording significantly higher numbers of completed HCAHPS surveys compared with others. Larger states such as **California, Texas, and Florida** contributed some of the highest numbers of completed survey responses.

**Insight:**  
The differences in completed survey volumes reflect variation in the number of participating facilities and eligible patients across states. Survey volume provides useful context when comparing patient experience results across different locations.

## RECOMMENDATIONS

Based on the findings from this analysis, healthcare organisations can consider the following actions:

- **Strengthen medication communication:**  
  Since medication-related communication recorded some of the lowest patient experience scores, hospitals can focus on improving how medication information is explained to patients, particularly around medication purpose, usage, and possible side effects.

- **Use patient feedback to target improvement areas:**  
  Facilities with lower patient experience ratings can use HCAHPS results to identify specific areas where patients report challenges and develop targeted improvement efforts.

- **Improve consistency of patient experience across facilities:**  
  Differences in ratings across facilities and states highlight the need for healthcare organisations to share effective practices and promote consistent standards for patient communication and care experiences.

- **Consider response rates when interpreting survey results:**  
  Since survey participation varies across facilities, healthcare organisations should consider response rates alongside patient ratings when evaluating performance and making decisions.

## LIMITATIONS

This analysis is based on HCAHPS survey data, which captures patients’ reported experiences with hospital care but does not measure all aspects of healthcare quality.

While the dataset provides valuable insights into patient experience patterns, it does not include additional factors such as hospital characteristics, patient demographics, staffing levels, or operational processes that may influence differences in performance across facilities and states.

Therefore, the findings highlight areas of strength and potential improvement but should not be interpreted as identifying the specific causes behind patient experience differences.

## CONCLUSION

This analysis used HCAHPS survey data to uncover patterns in patient experience performance across healthcare facilities and states.

The findings highlight areas of strong performance and opportunities for improvement, demonstrating how healthcare data can support better decisions and enhance patient experience.
