# Hospital Analytics - Excel Dashboard

## Project Overview

The Hospital Analytics project is an Excel-based data analysis and dashboard project focused on analyzing patient encounters, hospital stay patterns, medical procedures, patient demographics, and readmission-related information.

The project uses Microsoft Excel to organize, analyze, and visualize hospital data through structured tables, calculations, pivot-based analysis, and dashboard reporting.

The analysis provides an overview of patient characteristics, hospital utilization, medical specialties, procedures, medication usage, diagnoses, and readmission patterns.

## Objective

The main objectives of this project are to:

- Analyze hospital patient and encounter data.
- Understand patient demographic characteristics.
- Analyze gender and race distribution.
- Examine patient age groups.
- Analyze the average duration of hospital stays.
- Understand medical specialty distribution.
- Analyze laboratory procedures and other procedures.
- Examine medication usage patterns.
- Analyze outpatient, emergency, and inpatient visits.
- Understand diagnosis-related information.
- Analyze diabetes medication usage.
- Examine patient readmission patterns.
- Present important hospital metrics through an Excel dashboard.
- Generate meaningful insights from the available hospital data.

## Dataset Description

The project uses a hospital patient encounter dataset containing information about patient demographics, hospital visits, medical procedures, diagnoses, medications, and readmission status.

The main dataset is stored in the `Table1` worksheet.

The dataset contains approximately **48,911 records** and includes 23 columns.

### Important Columns

| Column | Description |
|---|---|
| `encounter_id` | Unique identifier for the hospital encounter |
| `patient_id` | Unique identifier for the patient |
| `race` | Race of the patient |
| `gender` | Gender of the patient |
| `age` | Age group of the patient |
| `time_in_hospital` | Number of days spent in the hospital |
| `medical_specialty` | Medical specialty associated with the encounter |
| `num_lab_procedures` | Number of laboratory procedures performed |
| `num_procedures` | Number of procedures performed |
| `num_medications` | Number of medications used |
| `number_outpatient` | Number of outpatient visits |
| `number_emergency` | Number of emergency visits |
| `number_inpatient` | Number of inpatient visits |
| `diag_1` | Primary diagnosis |
| `diag_2` | Secondary diagnosis |
| `diag_3` | Additional diagnosis |
| `diag_4` | Additional diagnosis |
| `diag_5` | Additional diagnosis |
| `number_diagnoses` | Number of diagnoses recorded |
| `change` | Change in medication |
| `diabetesMed` | Indicates diabetes medication usage |
| `readmitted` | Patient readmission status |

## Tools & Technologies Used

- Microsoft Excel
- Excel Tables
- Pivot Tables
- Pivot Charts
- Excel Formulas
- Data Analysis
- Data Visualization
- Interactive Dashboard Design

## Approach / Methodology

The project was completed through the following stages.

### 1. Data Collection

The hospital patient encounter dataset was loaded into Microsoft Excel for analysis.

### 2. Data Understanding

The dataset was examined to understand:

- Number of records
- Number of columns
- Patient identifiers
- Demographic variables
- Hospital stay information
- Medical specialties
- Procedure-related variables
- Medication-related variables
- Diagnosis-related variables
- Readmission information

### 3. Data Preparation

The dataset was reviewed and prepared for analysis by examining:

- Missing values
- Unknown values
- Invalid values
- Categorical variables
- Numerical variables
- Patient age groups
- Medical specialty information
- Readmission information

### 4. Data Analysis

The hospital data was analyzed to understand:

- Patient demographics
- Gender distribution
- Race distribution
- Age-group distribution
- Hospital stay duration
- Medical specialty distribution
- Procedure activity
- Medication usage
- Hospital visit patterns
- Diagnosis information
- Diabetes medication usage
- Readmission patterns

### 5. Pivot Table Analysis

Pivot tables were used to summarize important hospital metrics and compare patient groups.

The analysis includes summaries related to:

- Patient count
- Average hospital stay
- Gender distribution
- Medical specialties
- Age groups
- Race distribution
- Diabetes medication
- Readmission-related information

### 6. Dashboard Development

The analyzed data was used to create an Excel dashboard for presenting important hospital metrics and analytical findings.

The dashboard provides a summarized view of the hospital dataset and allows users to understand major patient and hospital utilization patterns.

## Analysis & Key Findings

### Patient Demographics

The dataset contains patient demographic information including:

- Gender
- Race
- Age group

The analysis provides an overview of the demographic composition of the patient encounters.

### Gender Analysis

The dataset contains both male and female patient encounters.

The available analysis shows:

- Female encounters: 26,378
- Male encounters: 22,531
- Unknown/Invalid: 2

This provides an overview of gender distribution within the analyzed hospital encounters.

### Race Analysis

Race distribution was analyzed to understand the demographic composition of the dataset.

The available data includes:

- Caucasian
- AfricanAmerican
- Hispanic
- Asian
- Other
- Unknown values

Caucasian is the largest recorded race group in the dataset.

### Hospital Stay Analysis

The average hospital stay in the analyzed dataset is approximately **4.40 days**.

Hospital stay duration can be examined across different patient characteristics and medical specialties to understand variations in hospital utilization.

### Medical Specialty Analysis

The dataset contains encounters associated with multiple medical specialties.

The analysis includes specialties such as:

- Internal Medicine
- Emergency/Trauma
- Family/General Practice
- Cardiology
- Nephrology
- Orthopedics
- Surgery-General
- Radiology
- Orthopedics-Reconstructive

The dataset also contains encounters where the medical specialty is recorded as Unknown.

### Procedure Analysis

The project analyzes:

- Laboratory procedures
- Other medical procedures
- Number of diagnoses

These metrics provide an understanding of the medical services associated with patient encounters.

### Medication Analysis

Medication-related variables were analyzed to understand medication usage patterns.

The dataset includes:

- Number of medications
- Diabetes medication
- Medication changes

### Hospital Visit Analysis

The dataset includes information about:

- Outpatient visits
- Emergency visits
- Inpatient visits

These variables help understand patient utilization of different types of healthcare services.

### Readmission Analysis

The `readmitted` field is used to analyze patient readmission patterns.

Readmission information can help identify differences in patient outcomes and hospital utilization patterns.

## Analysis & Key Insights

Based on the analysis performed in the Excel workbook, the following key insights were identified:

- The dataset contains approximately 48,911 hospital patient encounters.
- Female encounters account for 26,378 records, while male encounters account for 22,531 records.
- The average hospital stay is approximately 4.40 days.
- Caucasian is the largest recorded race group in the dataset.
- The dataset contains encounters across multiple medical specialties.
- Internal Medicine has a substantial number of recorded encounters among the listed specialties.
- Emergency/Trauma and Family/General Practice also account for a considerable number of encounters.
- The dataset contains a significant number of records where medical specialty information is recorded as Unknown.
- Patient encounters vary in the number of laboratory procedures, procedures, medications, and diagnoses.
- Outpatient, emergency, and inpatient visit counts provide additional information about healthcare utilization.
- Readmission information can be used to further investigate patient outcomes and hospital utilization.
- Diabetes medication and medication-change information provide additional dimensions for analyzing patient treatment patterns.

These findings are based on the available Excel dataset and analysis included in the project.

## Dashboard Overview

The Excel project includes a dashboard designed to present the major hospital analytics findings in a summarized and visual format.
<img width="1669" height="620" alt="image" src="https://github.com/user-attachments/assets/a1047d32-273c-496b-8a2d-f3a689289e4f" />

The dashboard focuses on important areas such as:

- Total Patient Encounters
- Average Time in Hospital
- Gender Distribution
- Patient Demographics
- Race Distribution
- Age Distribution
- Medical Specialty
- Hospital Visit Patterns
- Medication Usage
- Readmission Analysis

The dashboard provides a consolidated view of the hospital data and helps users explore important patient and hospital utilization patterns.

## Key Performance Indicators

The project focuses on important hospital KPIs such as:

| KPI | Description |
|---|---|
| Total Patient Encounters | Total number of hospital encounters analyzed |
| Average Time in Hospital | Average number of days patients stayed in the hospital |
| Female Encounters | Number of encounters associated with female patients |
| Male Encounters | Number of encounters associated with male patients |
| Total Procedures | Number of procedures associated with patient encounters |
| Total Lab Procedures | Number of laboratory procedures recorded |
| Total Medications | Number of medications recorded across encounters |
| Readmission | Patient readmission status and related analysis |

## Recommendations

Based on the analysis performed, the following recommendations can be considered:

- Monitor hospital stay duration across different patient groups and specialties.
- Analyze medical specialty workload to understand hospital service utilization.
- Monitor readmission patterns to identify areas requiring further investigation.
- Examine emergency, inpatient, and outpatient visit patterns for better resource planning.
- Monitor procedure and laboratory activity to understand healthcare service utilization.
- Analyze medication usage and medication changes across patient groups.
- Improve the completeness of medical specialty and demographic information where Unknown or missing values occur.
- Use demographic and hospital utilization patterns to support healthcare resource planning.
- Continue monitoring patient encounter and readmission trends using regularly updated data.

## Conclusion

The Hospital Analytics Excel project demonstrates how Microsoft Excel can be used to analyze healthcare data and create meaningful analytical insights.

The project covers patient demographics, hospital stay duration, medical specialties, procedures, medications, hospital visits, diagnoses, and readmission information.

Using Excel tables, pivot-based analysis, calculations, and dashboard visualization, the project transforms hospital encounter data into an understandable analytical report.

Overall, the project demonstrates practical skills in Excel-based data cleaning, data analysis, pivot table analysis, KPI development, data visualization, and dashboard creation.

