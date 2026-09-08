**Healthcare data analysis:patient readmission pattern and hospital resourse optimization.**

This project focuses on analyzing healthcare data to understand patient readmission patterns and support hospital resource optimization.

The dataset contains information about patients, hospital beds, wards, doctors, diseases, waiting times, length of stay, discharge status, and readmission status.

The main purpose of this analysis is to identify important patterns that may contribute to patient readmission and to understand how hospital resources can be managed more effectively.

🎯 Objectives
Analyze patient readmission patterns.
Identify factors associated with hospital readmission.
Study patient demographics such as age and gender.
Analyze patient length of stay.
Examine hospital bed availability and occupancy.
Study patient waiting times.
Analyze disease and department patterns.
Understand discharge status and readmission.
Support better hospital resource planning and decision-making.
📊 Dataset Information
Total Records: 10,000
Total Columns: 26
File Format: CSV
Missing Values: No missing values were found in the dataset.
Main Features
Feature	Description
hospital_name	Name of the hospital
Admission_date	Patient admission date
hospital_id	Unique hospital ID
hospital_beds_available	Number of beds available
occupied_beds	Number of occupied beds
hospital_ward	Hospital ward
patient_id	Unique patient ID
patient_gender	Gender of the patient
patient_age	Age of the patient
patient_race	Race of the patient
patient_sat_score	Patient satisfaction score
patient_waittime	Patient waiting time
department_referral	Department to which the patient was referred
doctor_id	Unique doctor ID
doctor_name	Name of the doctor
doctor_specialty	Doctor's specialty
patient_assigned_doctor	Whether a doctor was assigned
patient_checkin_date	Patient check-in date
patient_checkout_date	Patient check-out date
patient_disease	Patient's disease/condition
patient_length_of_stay	Number of days the patient stayed
discharge_status	Patient's discharge status
readmission	Whether the patient was readmitted
🛠️ Tools and Technologies
Python
Google Colab / Jupyter Notebook
Pandas – Data cleaning and analysis
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical visualization
🧹 Data Cleaning

The dataset was checked and prepared before analysis.

The main data-cleaning steps included:

Checking the dataset structure.
Checking for missing values.
Checking duplicate records.
Reviewing data types.
Cleaning and formatting date columns.
Checking numerical and categorical variables.
Preparing the data for visualization and analysis.
📈 Exploratory Data Analysis

The analysis focuses on several important areas:

1. Patient Demographics

Analysis of patient distribution based on:

Gender
Age groups
Race
2. Readmission Analysis

The readmission variable is used to compare patients who were readmitted with those who were not.

0 = Not Readmitted
1 = Readmitted
3. Length of Stay vs Readmission

Patient length of stay is compared with readmission status to determine whether hospitalization duration shows a relationship with readmission.

4. Hospital Resource Utilization

Hospital bed availability and occupied beds are analyzed to understand resource utilization and capacity.

5. Patient Waiting Time

Waiting times are analyzed to understand patient flow and possible operational inefficiencies.

6. Disease Analysis

Different patient diseases are analyzed to identify common conditions and their relationship with hospital utilization and readmission.

7. Ward and Department Analysis

Hospital wards and department referrals are analyzed to understand where healthcare resources are most frequently required.

📊 Example Python Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
💡 Key Insights

This healthcare analysis can help identify:

Patient groups with higher readmission patterns.
Differences in length of stay between readmitted and non-readmitted patients.
Hospital wards with greater resource utilization.
Patterns in patient waiting times.
Common diseases and department referrals.
Bed occupancy and availability patterns.
Areas where hospital resources may be optimized.
🏥 Resource Optimization

The findings from this project can support hospitals in:

Improving bed allocation.
Managing patient flow.
Reducing unnecessary waiting times.
Identifying patients who may require additional follow-up.
Improving discharge planning.
Allocating staff and resources according to demand.
Supporting data-driven healthcare decisions.
📌 Conclusion

The Healthcare Data Analysis: Patient Readmission Patterns and Resource Optimization project demonstrates how healthcare data can be used to understand patient behavior and hospital operations.

By examining factors such as readmission status, length of stay, patient demographics, waiting time, diseases, hospital wards, and bed utilization, the analysis provides useful insights into both patient outcomes and hospital resource management.

These insights can support better decision-making, improve hospital efficiency, and help healthcare organizations develop strategies for reducing avoidable readmissions and optimizing available resources.

📂 Project Structure
Healthcare-Data-Analysis/
│
├── Healthcare Data Analysis for readmission.csv
├── Healthcare_Data_Analysis.ipynb
└── README.md
👩‍💻 Author

Fathima Fathi

Healthcare Data Analysis Project
Patient Readmission Patterns and Resource Optimization
