# Capstone Project

## Project Description
This repository contains data and code for predicting long-term ICU mortality and analyzing the weekend effect using early admission data. The project leverages machine learning and statistical modeling to address two key research objectives:

### Objectives
1. **Mortality Prediction:** Developing models to predict ICU mortality using the first 24 hours of patient data. This includes preprocessing, feature engineering, and hyperparameter tuning for optimal performance.
2. **Weekend Effect Analysis:** Examining whether patients admitted over weekends have higher mortality rates compared to weekdays, utilizing statistical and machine learning approaches to identify potential patterns.

### Features
- **Comprehensive Data Analysis:** Includes data cleaning, preprocessing, and exploratory data analysis (EDA) for insightful visualizations.
- **Machine Learning Models:** Employs Random Forest, XGBoost, and logistic regression models for predicting mortality.
- **Survival Analysis:** Utilizes survival models such as Cox Proportional-Hazards to study time-to-event data and evaluate the weekend effect.
- **Reproducible Workflows:** Scripts and notebooks are designed for easy replication and customization.

## Significance
This project aims to contribute to the understanding of critical care patient outcomes by:
- Identifying key predictors of ICU mortality within the first 24 hours of admission.
- Highlighting disparities in patient outcomes related to admission timing, potentially informing hospital staffing and resource planning.

## File Structure
The repository is organized into two main directories corresponding to the research questions:

### **Research Question 1**
This folder contains Jupyter notebooks for data preprocessing, feature engineering, and training machine learning models:
- `1.Filter_and_Merge.ipynb` - Data filtering and merging of relevant datasets.
- `2.nan_data_cleaning.ipynb` - Cleaning missing values in the dataset.
- `3.NaN_Checker.ipynb` - Identifying and handling missing values.
- `4.data_preprocessing_pipeline.ipynb` - Comprehensive preprocessing pipeline.
- `5.Logistic_Regression.ipynb` - Logistic Regression model for ICU mortality prediction.
- `6.Random_Forest.ipynb` - Random Forest model for ICU mortality prediction.
- `7.XGBOOST.ipynb` - XGBoost model for ICU mortality prediction.
- `8.Graph.ipynb` - Visualizations and graphs of model performance.

### **Research Question 2**
This folder focuses on statistical analysis and survival modeling:
- `1.Filter_and_Merge.ipynb` - Initial filtering and merging of relevant datasets.
- `2.statistical_analysis.ipynb` - Statistical exploration of the weekend effect.
- `3.nan_data_cleaning.ipynb` - Handling missing values.
- `4.NaN_filling.ipynb` - Filling missing data with imputation techniques.
- `5.Try_reduced_model.ipynb` - Building a simplified model for survival analysis.
- `Survival Models.Rmd` - R Markdown file detailing survival modeling processes.
- `Survival Models.html` - Rendered HTML version of the survival analysis.
- `cleaned_final_cox_dataset.csv` - Preprocessed dataset for Cox Proportional-Hazards modeling.

## Dataset
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
