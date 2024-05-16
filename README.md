# Data-Analytics-and-Reporting
## Inpatient-Rehabilitation-Facility-Performance-And-Score-Analysis

### Project Overview 
This data analysis related to CMS data - Inpatient Rehabilitation Facility Nationwide benchmark Analysis, provides insights into the performance of the facility compared to the nation benchmark. By Analyzing this data, we can Identify High-Performing Facilities, 
develop improvement initiatives towards the facilities and areas that lag behind benchmarks, continuous quality improvement as facilities strive to meet or exceed benchmark standards.

This dashboards demonstrates the value in facilitating data-driven decision-making, quality improvement initiatives, and the delivery of high-quality care to patients across the nation.

### Data Sources
These are 5 CSV files extracted from CMS Data - Inpatient Rehabilitation Facility comes with IRF Data Dictionary to understand the values mentioned in the files [Download Here](https://data.cms.gov/provider-data/topics/inpatient-rehabilitation-facilities
)

IRF_Conditions_Mar2023
IRF_General_Information_Mar2023
IRF_National_Data_Mar2023
IRF_Provider_Data_Mar2023
State_Alias

### Tools 
- Excel - Visualizing and Data Cleaning CSV Files
- MySQL - To perform Exploratory Data Analysis
- Tableau - Create Dashboard and Reports - 1 Story – 7 Dashboards tabs – 13 Worksheets

### Data Cleaning / Preparation

In Initial Data Preparation phase 
- Data Load and Analysis 
- Handled missing values - Null Values replaced with Not Available / 999999 
- Data formatting
- Data Value Unification
- Expression Transformation
- Joining 5 different tables to cross-validate Nationwide benchmark status

### Data Analysis
- What is the Aging of Facility (Years Established) ? How many established in recent years ?
- Which Ownership is widely established occupies most of the area ( For-profit, Non-Profit, Government, Others ) ? what is the aging of For-profit ?
- Which CMS Region, State holds highest Revenue, Profit, Loss compared to geographic data ?
- Identifying different score categories for measures ? What are the measures not available for publicly made available data ? what are those facilities ?
- What are facilities performing worse than National rate ?
- What is the condition that is treated widely in the Inpatient Rehabilitation Facilities ? 

### Results and Findings
- Average "For profit" facility seems to be established in recent years [0-4] compared to others average with aging more than 30 years (Most of them are from Texas)
- Texas and California shows High revenue compared to all other states.
- The average non-profit seems to be higher aging with > 20 years, whereas the for profit aging average is higher with <20 years aging
- "Not Available" category - Facility Scores are not available for majority of measures - Clearly idenfity which facility didn't share their details.
- The average facilities / measures performing worse than nationwidewide benchmark status is higher

### Recommendations
- Major concern - Healthcare should be non-profit helping people - Many For-profit Facilities were recently established in Texas
- Texas state Conditions treated were bucketed in "All other Conditions" similar to "Named*" Conditions
- Identify root cause for the approvals
- Detect the Fraudulent claims majorly from these Facilities
- What were the reasons behind establishing new faiclities.

### Limitations
- The understanding related to IRF measures, can be in more detailed
- Most of the measures values seems to be duplicated
- Many Facilities didnot provide scores
