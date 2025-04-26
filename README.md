# Correlative Factor Identification and Pattern Recognition for Early Diagnostics of Alzheimer's Using Demographic, Clinical, Symptomatic, and Historical Data

## Project Object Goal
This project aims to statistically analyze and correlate medical history, demographics, clinical evaluations, and symptoms to recognize patterns that are indicative of an Alzheimer's diagnosis in hopes of providing a tool that helps in diagnosing earlier to aid in the mitigation of symptoms and even potentially alter or discontinue the disease progression. The aim and hope of this project is that, with an examination, a solution can be provided that will lead to more research that could aid in treatment and alleviate some of the burden that the disease causes. 

## Dataset Outline
There is an extensive evaluation of health for 2149 patients with 35 columns of information – 33 about health, 1 to identify patients, and one of redacted confidential information. The dataset contains historical, clinical, cognitive, symptomatic, and confidential and diagnostic information. There is a patient identification number ranging from 4751 – 6900 used to individualize the patients. 

Demographics contain:
*	Age (60 – 90 years)
*	Gender (0 = male; 1 = female)
*	Ethnicity (0 = Caucasian; 1 = African American; 2 = Asian; 3 = Other)
*	EducationLevel (0 = none; 1 = high school; 2 = Bachelor’s; 3 = Higher)

Lifestyle Factors contain:
* BMI (score ranges from 15 – 40)
* Smoking (0 = no; 1 = yes)
*	AlcoholConsumption (consumption per weekly unit ranging from 0 – 20)
*	PhysicalActivity (activity hours per week 0 – 10)
*	DietQuality (score ranging from 0 – 10)
*	SleepQuality (score ranging from 4 – 10)

Medical History contains:
*	FamilyHistoryAlzheimers (0 = no history; 1 = history)
*	CardiovascularDisease (0 = no presence of disease; 1 = presence of disease)
*	Diabetes (0 = no diabetes; 1 = diabetes)
*	Depression (0 = no depression; 1 = depression)
*	HeadInjury (0 = no history; 1 = history)
*	Hypertension (0 = no presence; 1 = presence)
  
Clinical Measurements contain: 
*	SystolicBP – Systolic blood pressure (90 – 180 mmHg)
*	DiastolicBP - Diastolic blood pressure (60 – 120 mmHg)
*	CholesterolTotal – total levels of cholesterol (150 – 300 mg/dL)
*	CholesterolLDL – low-density levels of lipoprotein cholesterol (50 – 200 mg/dL)
*	CholesterolHDL - high-density levels of lipoprotein cholesterol (20 – 100 mg/dL)
*	CholesterolTriglycerides – levels of triglycerides (50 – 400 mg/dL)

Assessments of Cognition and Functionality contain:
*	MMSE – score via the Mini-Mental State Examination (0 – 30 (lower = higher impairment of cognition))
*	FunctionalAssessment (0 – 10 (lower = higher impairment))
*	MemoryComplaints (0 = no complaints; 1 = complaints)
*	BehavioralProblems (0 = no behavioral issues; 1 = behavioral issues)
*	ADL – score on Activities of Daily Living (0 – 10 (lower = higher impairment))

Symptoms contain: 
*	Confusion (0 = no confusion; 1 = confusion)
*	Disorientation (0 = no disorientation; 1 = disorientation)
*	PersonalityChanges (0 = no changes; 1 = changes)
*	DifficultyCompletingTasks (0 = no difficulty; 1 = difficulty)
*	Forgetfulness (0 = no forgetfulness; 1 = forgetfulness)

Diagnostic Results:
*	Diagnosis (0 = no disease; 1 = having disease)

Confidential Information
*	DoctorInCharge (all patients have “XXXConfid”)

Dataset Ciation: 
Rabie El Kharoua. (2024). 🧠 Alzheimer's Disease Dataset 🧠 [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/8668279

## Problem Statement
Alheimer's is neurologically deterioative progressive disease and one of the top 10 causes of death. Early detection is vital in patient outcome improvement, but the current methods of diagnosis are costly, not accessible for all, and invasive. This project analyzes medical histoey, lifestle factors, demographics, clinical assessments and clinical evaluations from a inclusively extensive dataset for pattern identification of linkages to Alzheimer's disease diagnosis.

## Structure
There are 4 files contained in the zip files of this project. There is a jupyter notebook zip as jupter is best for the graphs and visualizations. The zip contain the dataset, PCA and Correlative Factor Analysis, Machine Learning Algorithms, and Graphs and Statistical Analysis. 

## Files
Files are included in this repository and labeled: Alzheimers_Final_Code.zip

## Running the code
To run this code: download the files, open jupyter notebook, nagivate to where you want to store the files, go to the "Upload" button at the top and select the zip file and 
To run this code simply 
