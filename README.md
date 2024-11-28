# Capstone Project

## Project Description
This project focuses on leveraging healthcare data to predict long-term ICU mortality and analyze the "weekend effect," which examines whether patient outcomes differ based on the day of admission. Using early admission data from the MIMIC-III database, this project employs advanced machine learning models, including Random Forest, XGBoost, and survival analysis techniques, to extract actionable insights for improving patient care and resource allocation.

The analysis is divided into two main objectives:
1. **Mortality Prediction:** Developing models to predict ICU mortality using the first 24 hours of patient data. This includes preprocessing, feature engineering, and hyperparameter tuning for optimal performance.
2. **Weekend Effect Analysis:** Examining whether patients admitted over weekends have higher mortality rates compared to weekdays, utilizing statistical and machine learning approaches to identify potential patterns.

## Features
- **Comprehensive Data Analysis:** Includes data cleaning, preprocessing, and exploratory data analysis (EDA) for insightful visualizations.
- **Machine Learning Models:** Employs Random Forest, XGBoost, and logistic regression models for predicting mortality.
- **Survival Analysis:** Utilizes survival models such as Cox Proportional-Hazards to study time-to-event data and evaluate the weekend effect.
- **Reproducible Workflows:** Scripts and notebooks are designed for easy replication and customization.

## Significance
This project aims to contribute to the understanding of critical care patient outcomes by:
- Identifying key predictors of ICU mortality within the first 24 hours of admission.
- Highlighting disparities in patient outcomes related to admission timing, potentially informing hospital staffing and resource planning.

## Files
Although the actual data files are not uploaded due to privacy and size constraints, the following files were used in this project:

1. **admissions.csv** - Contains information about patient admissions (11 MB).  
2. **antibiotics.csv** - Records antibiotic usage (23.5 MB).  
3. **bloodculture.csv** - Includes blood culture test results (47 MB).  
4. **gcs_hourly.csv** - Tracks Glasgow Coma Scale (GCS) scores recorded hourly (31.8 MB).  
5. **icd9_diag.csv** - Lists ICD-9 diagnostic codes for patients (58.3 MB).  
6. **icustays.csv** - Details ICU stay information for patients (5.78 MB).  
7. **labs_hourly.csv** - Provides laboratory results recorded hourly (42.5 MB).  
8. **output_hourly.csv** - Captures patient output (e.g., fluids) recorded hourly (46.8 MB).  
9. **patients.csv** - Includes basic patient demographic data (2.46 MB).  
10. **pt_icu_outcome.csv** - Summarizes ICU outcomes for patients (8.61 MB).  
11. **pt_stay_hr.csv** - Contains detailed hourly records of patient stays (374 MB).  
12. **pt_weight.csv** - Provides patient weight information (41.4 MB).  
13. **pv_mechvent.csv** - Tracks mechanical ventilation usage (71.7 MB).  
14. **transfers.csv** - Documents patient transfers within the ICU (22.8 MB).  
15. **vasopressors.csv** - Records vasopressor medication data (16.8 MB).  
16. **vitals_hourly.csv** - Provides hourly vital sign measurements (258 MB).  


## How to Use
1. Clone the repository using the following command:
git clone https://github.com/18858295360/Capstone-Project.git
2. Set up your environment by installing the necessary dependencies listed in the `requirements.txt` file.
3. Run the provided Jupyter notebooks or R scripts to reproduce the analysis.

## Author
Liyang Li
