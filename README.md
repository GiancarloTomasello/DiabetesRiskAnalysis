# Diabetes Diagnosis Data Analysis

## Project Summary

This project aims to develop a predictive model that can accurately identify patients with elevated risks of diabetes using their demographic and clinical data. The goal of this project is to provide a window into trends that may be more common for patients at risk of diabetes so medical practitioners can have some early warning signs to look out for during the disease screening. This will be done through the use of exploratory data analysis, machine learning, and dashboard creation as ways to identify the key risk factors and group patients by risk categories. THe final deliverables will be a predictive model and an interactive dashboard in power bi.

## Why it matters

Diabetes affects millions of individuals and early identification can help avoid significant health complications from the disease. Diabetes is a disease that can occur even if no family history which creates a situation where it may not be directly screened for in a patient. Creating tools that can identify high risk patients allows for doctors to be on the look out for the disease early on in the process.

## Project Objectives
* Analyze diabetes risk factors
* Identify variables associated with diabetes
* Build a few different predictive models
* Evaluate models performance against one another
* Categorize patients into risk groups
* Create a dashboard for healthcare stakeholders.

## Data Set Overview

Source: The Behavioral Risk Factor Surveillance System (BRFSS) by the CDC
> Sourced from Kaggel (https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

Contained 3 files
1. diabetes _ 012 _ health _ indicators _ BRFSS2015.csv
 - 253,680 records
 - Data split into 3 classes (0 for no diabetes, 1 for prediabetic, 2 for diabetic)
 - 21 feature variables
2. diabetes _ binary _ 5050split _ health _ indicators _ BRFSS2015.csv
 - 70,692 records
 - 2 classes (0 for diabetes and 1 for prediabetic)
 - Classes are split 50-50 between the 2 classes
 - 21 features
3. diabetes _ binary _ health _ indicators _ BRFSS2015.csv
   - 253,680 records
   - 2 classes (0 for diabetes and 1 for prediabetic)
   - Not balanced

Features
- Diabetes Class
- HighBP
- HighChol
- CHolCheck
- BMI
- Smoker
- HeartDiseaseorAttack
- PhysActivity
- Fruits
- Veggies
- HvyAlcoholConsump
- AnyHealthcare
- NoDocbcCost
- GenHlth
- MentHlth
- PhysHlth
- DiffWalk
- Sex
- Age
- Education
- Income

## Data Dictionary
A complete data dictionary is available in:
/documentation/data_dictionary.md

example 1
example 2
example 3

##Data Cleaning:

Due to the file coming preprepared a full data cleaning step was not neccesary but nonetheless I varified the following to ensure a proper data clean up was done by the file provider:
- Checked for null or missing values
- Varified value ranges for each column (Ex. Binary columns should be 0 or 1)
- Insured each column had the correct typing for the data it represented

##Exploratory Data Analysis

During this step i created a notebook to start to understand the data available to me in the provided files by performing the following:
- Created a break down of the distribution of values for certain key columns
- Determined the correlation each column had to the diabetes class outcome
- Compared the distribution of each diabetes classification to each other

### BMI Distribution

### Age Distribution

### Correlation to Outcome

##Modeling Approach

## Predictive Modeling

Models Evaluated:

1. Logistic Regression
2. Random Forest Classifier

Evaluation Metrics:

- Accuracy
- Precision
- Recall

##Results

-----------------

##Risk Satisfaction

--------------------------

##Dashboard

-------------------------

## Business Recommendation

------------------------

## Project Structure

------------------------

## Tools used

-------------------------

## Future Improvements


