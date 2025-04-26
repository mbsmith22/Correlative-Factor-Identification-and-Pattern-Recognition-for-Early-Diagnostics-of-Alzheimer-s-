# Correlative Factor Identification and Pattern Recognition for Early Diagnostics of Alzheimer's Using Demographic, Clinical, Symptomatic, and Historical Data

## Project Object Goal
This project aims to statistically analyze and correlate medical history, demographics, clinical evaluations, and symptoms to recognize patterns that are indicative of an Alzheimer's diagnosis in hopes of providing a tool that aids in earlier diagnosing to help in the mitigation of symptoms and even potentially alter or discontinue the disease progression. The aim and hope of this project is that, with an examination, a solution can be provided that will lead to more research that could aid in treatment and alleviate some of the burden that the disease causes. 

## Dataset Outline

Dataset Ciation and Source: 
Rabie El Kharoua. (2024). 🧠 Alzheimer's Disease Dataset 🧠 [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/8668279

- Patient total: 2149
- Column total: 35

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


## Problem Statement
Alzheimer’s is a neurodegenerative, progressive disease and one of the top 10 causes of death. Early detection is vital in patient outcome improvement, but the current methods of diagnosis are costly, not accessible to all, and invasive. This project analyzes medical history, lifestyle factors, demographics, clinical assessments, and clinical evaluations from an extensive dataset for pattern identification of linkages to Alzheimer's disease diagnosis.

## Structure
📁 Alzheimers_Code/ <br /> 
├── alzheimers_disease_data.csv/ <br />
├── PCA and Correlative Analysis.ipynb/ <br />
├── ML_Algorithms.ipynb / <br />
└── Graphs and Data.ipynb / <br />

Note:  Jupyter Notebooks are best for visualizations and interactiveness for coding and graphs. 
Code can be download as .py (Python) files from Jupyter if needed. 

## Files
Files are included in this repository and labeled: Alzheimers_Code

The order of the files is:
* The dataset needs to be loaded first for the other files to run
1. alzheimers_disease_data.csv – must be loaded first
2. PCA and Correlative Analysis.ipynb
3. ML_Algorithms.ipynb
4. Graphs and Data.ipynb

*This is the file execution order for how the code was created and should be run. 

## Running the code
To run this code: 
1. Download the files from the repository or clone them
2. Open Jupyter notebook and navigate to where you want to store the files
3. Go to the "Upload" button at the top, and select the folder file or upload the files one by one and insert them.
*The dataset needs to be loaded first for the other files to run.
4. The code is set in blocks for each part of the code that does specific tasks and press the ⏵ button or navigate to the top of the notebook, select run, and specify how you would like the cells to be run. 

## Libraries Used 
Some common libraries that might need to be installed use the following command:/ <br />
!pip install pandas matplotlib seaborn scikit-learn/ <br />
There are several libraries used in this project. Most are in the Jupyter notebook application. If they are not run: !pip install {library name}/ <br />
Some libraries that needed to be installed are commented out. If the library is needed to run the code, remove the # to uncomment the code and run the block. 

## Contact / Author
Project by Madison B. Smith/ <br />
All code written by ChatGPT - comments mostly my own. / <br />
Feel free to reach out via GitHub Issues or discussions for any questions. / <br />
