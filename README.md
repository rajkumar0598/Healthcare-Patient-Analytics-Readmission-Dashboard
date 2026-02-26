# Healthcare-Patient-Analytics-Readmission-Dashboard
Healthcare analytics dashboard analyzing patient readmissions, risk drivers, and hospital performance using Power BI.
 
##  Project Overview

This Power BI project analyzes diabetic patient hospital encounter data to understand readmission patterns, identify high-risk patients, and uncover operational drivers affecting hospital performance.

The dashboard is designed to support hospital leadership and quality teams in making data-driven decisions related to patient care and readmission reduction.

---

##  Objective

* Analyze hospital encounter data at encounter level
* Measure readmission rates and 30-day readmissions
* Identify high-risk patient segments
* Understand drivers such as age, discharge disposition, insulin usage, and medication complexity
* Support operational decision-making for reducing readmissions

---

##  Dataset Information

* Dataset: Diabetic Patient Hospital Encounters
* Source: Hospital administrative records
* Total Records: ~100,000 encounters
* Grain: One row represents one hospital encounter
* Patient tracking enabled using `patient_nbr`

The data model follows a **star schema** with:

* Fact table : Hospital Encounters
* Dimension tables : Admission Type, Admission Source, Discharge Disposition

---

## Key KPIs

* Total Encounters
* Unique Patients
* Readmission Rate %
* 30-Day Readmission %
* High-Risk Patients
* Average Length of Stay
* Average Encounters per Patient

According to the dashboard, overall readmission rate is around **46-48%**, while **30-day readmission is ~11%**. 

---

## Dashboard Pages

### 1 Executive Overview

* Patient volume & demographics
* Readmission by age group
* Readmission by discharge disposition
* Key KPIs summary

### 2 Patient Demographics & Volume

* Encounters by age group
* Encounters by gender
* Encounters by admission type
* Unique patients and encounter distribution

### 3 Readmission Analysis & Risk Drivers

* Readmission by age group
* Readmission by discharge disposition
* Readmissions by gender
* High-risk rate analysis

### 4 Treatment Patterns & Risk Indicators

* Insulin usage %
* Medication complexity
* Emergency visits impact
* Readmission relationship with treatment patterns

---

##  Key Insights

* Elderly patients (60+) show the highest readmission risk
* Certain discharge dispositions drive early readmissions
* Higher medication complexity increases readmission probability
* Insulin usage is strongly associated with readmission risk
* Emergency admission types contribute significantly to repeat encounters

These insights highlight operational gaps in post-discharge planning. 

---

##  Business Impact

* Increased hospital operational burden
* Higher cost due to repeat admissions
* Identifies gaps in discharge planning
* Helps prioritize high-risk patient groups

---

##  Recommendations

* Strengthen post-discharge follow-up
* Focus transitional care programs on elderly patients
* Improve discharge planning for high-risk disposition types
* Review medication complexity before discharge

---

## Tools & Skills Used

* Power BI
* Data Modeling (Star Schema)
* DAX (KPIs & Measures)
* Healthcare Analytics
* Risk Analysis
* Data Visualization
* Business Insights

---

##  Skills Demonstrated

* End-to-end dashboard development
* KPI design
* Analytical thinking
* Healthcare domain analytics
* Insight generation
* Storytelling with data

---

##  Files Included

* Power BI Dashboard (.pbix)
* Project Documentation (PDF)
* Screenshots

---

## Author

Raj kumar 
Aspiring Data Analyst | Healthcare Analytics | Power BI
