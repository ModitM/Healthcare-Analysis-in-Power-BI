# Healthcare-Analysis-in-Power-BI
In today's data-driven world, no sector of society remains untouched by the insights drawn from data. Healthcare sector is no exception to it. Today, data is used in healthcare sector to determine safety, effectiveness, efficiency, timeliness, equity and patient-centeredness in any healthcare facility. These factors form the 'Analytical Framework For Healthcare Quality'.  
### Problem Statement
Conduct data analysis on the data set to determine the efficiency in a healthcare facility and root cause analysis for variance in efficiency for the patients who underwent Hips-replacement surgery. 
### Data set
Data set contains the details of the hospitals, demographic details of the patients,  details of the disease and treatment undergone, length of stay at the hospital, and cost associated with treatment  etc. for the state of New York in the year 2016. Most of the record (>99%) belongs to the patients who had undergone a Hips-replacement Surgery. 
### Approach
1. Performed data cleaning, formatting, filtering in Power query editor.
2. Created a new table for taking account of Surgical Program Size in each facility.
3. Created two measures of efficiency using DAX for healthcare facility - Average LOS (days) i.e average length of stay of the patient and Average Cost per Discharge.
4. Performed root cause analysis using KPIs to know why the measures of efficiency changes.
### Results
1. Average LOS is 2.65 days and Average Cost per Discharge is $20,910.
2. Severity of illness - Extreme, Risk of mortality - Extreme, Health Service Area - New York City are the common factors increasing the Average LOS and Average Cost per Discharge.
### Dashboard
Created a dashboard for LOS Comparision, Cost Comparision and Hospital Profiles.
