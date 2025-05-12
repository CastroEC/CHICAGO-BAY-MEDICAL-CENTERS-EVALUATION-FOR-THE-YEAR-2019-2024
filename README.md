

## 🧾 Table of Contents

1. [Introduction](#introduction)
2. [Data Story](#data-story)
3. [Data Preprocessing](#data-preprocessing)
4. [Preliminary Analysis](#preliminary-analysis)
5. [In-Depth Analysis](#in-depth-analysis)
6. [Recommendations](#recommendations)
7. [Conclusion](#conclusion)
8. [References & Appendices](#references--appendices)

---

## Introduction

### Purpose

This project analyzes healthcare data from various medical centers to uncover patterns in patient admissions, treatments, and billing, aiming to enhance service delivery and revenue generation.

### Objectives

- Identify top-performing doctors and hospitals.
- Analyze medication usage and associated costs.
- Examine admission trends over time.
- Understand patient demographics and their relation to medical conditions.

### Problem Statement

The healthcare industry seeks to balance quality patient care with financial sustainability. By analyzing operational data, we aim to identify areas for improvement in service delivery and revenue optimization.

### Datasets & Methodologies

- **Datasets**: Patient demographics, medical conditions, treatments, billing information.
- **Tools**: Microsoft Excel

---

## Data Story

### Data Source

Collected from Kaggle, a known website for different dataset.

### Data Collection Process

Data was aggregated from electronic health records (EHRs) across multiple departments within the medical centers.

### Data Structure

- **Rows**: Individual patient records.
- **Columns**: Variables such as Name, Age, Gender, Blood Type, Doctor, Hospital, Insurance Provider, Medication, Medical Condition, Admission Details, Billing Amount.

### Key Features

- **Independent Variables**: Name, Age, Gender, Blood Type, Doctor, Hospital, Insurance Provider, Medication.
- **Dependent Variables**: Medical Condition, Date of Admission, Billing Amount, Room Number, Admission Type, Test Results, Discharge Date.

### Data Limitations

- Potential inconsistencies in data entry (e.g., variations in doctor/hospital names).
- Missing values in certain fields (e.g., Discharge Date).
- Data limited to specific time frames, affecting trend analysis.

---

## Data Preprocessing

### Data Cleaning

- Standardized naming conventions for doctors and hospitals.
- Removed duplicate entries.
- Addressed missing values where possible.

### Handling Missing Values

- Utilized Excel functions to identify and manage missing data.
- In cases where data was unavailable, records were flagged for further review.

### Data Transformation

- Created new variables for analysis (e.g., Year of Admission).
- Categorized continuous variables (e.g., Age groups).

### Data Splitting

- Segregated data into training and testing sets for validation purposes.

---

## Preliminary Analysis

### Key Trends

- **Top Doctors by Patient Count**:
  - Michael Smith: 27 patients
  - John Smith: 22 patients
  - Robert Smith: 21 patients

- **Top Insurance Providers by Billing Amount**:
  - Cigna: $284,334,099.18
  - Medicare: $282,911,026.77

- **Most Used Medications**:
  - Ibuprofen: $283,784,866.81
  - Aspirin: $281,163,283.40

### Potential Correlations

- High patient counts associated with certain doctors may correlate with higher billing amounts.
- Specific medications are consistently linked with higher treatment costs.

### Initial Insights

- A small group of doctors handle a significant portion of patients.
- Certain insurance providers contribute more substantially to revenue.

---

## In-Depth Analysis

### Observations

- **Admission Trends**:
  - 2020 saw the highest revenue: $283,952,663.92.
  - A noticeable decline in 2024: $97,143,472.46.

- **Hospital Performance**:
  - Johnson PLC leads with $1,081,477.31 in billing.

- **Gender Analysis**:
  - Male: 27,496 cases
  - Female: 27,470 cases

- **Age Groups with High Illness Risk**:
  - Ages 38, 57, and 37 show the highest counts

---


### Key Findings

- The Best performing doctor via patient count is Dr. Michael Smith

-  Top Insurance providers covering the most healthcare bills is Cigna

-  The most recommended medications for patients is Ibuprofen

- The males has the most count for medical conditions 

- Age group with the higher risk of having a medical condition is 38

- Most patients are admitted into the medical centers by elective 

- The top quality hospital or medical center is Johnson PLC

- The year that generated most revenue via admission of patients is the year 2020, generating a gross revenue of $283,952,663.92


## Recommendations

- I recommend that patient load should be distributed across staffs available and in cases where there is shortage of staffs, additional staffs should be hired.

- For the top insurance provider, i do recommend that hospitals should negotiate with the top insurance provider with good contract rates in pther to secure more patients.

- I do recommend to the various hospitals using the ibuprofen to always inform the para inventory to keep out an eye for ibuprofen to avoid stock out.

- I do recommend that hospitals start up preventive care programs for males and genders of age group 38 in order to enlighten them on preventive care measures to avoid certain conditions.

- I recommend preparation of staffs and medical resources for unpredctable situations during admission of patients in order to avoid some certain outcomes.

- I do recommend to other medical care centers to optimze resource allocation and get equipped with the appriopriate staffs, to be able to give out the best quality of healthcare.


---

## Conclusion

This analysis provides insights into operational efficiencies and areas for improvement within the healthcare system. By leveraging data-driven strategies, medical centers can enhance patient care while optimizing revenue streams.

---

## References & Appendices

- **Data Sources**: Kaggle.
- **Tools Used**: Microsoft Excel.
- **Appendices**:
  - Detailed Pivot Tables.
  - Data Cleaning
 
    ![Updated DashBoard 6](https://github.com/user-attachments/assets/6c4468bd-345d-4b67-905d-e4c009368f18)

