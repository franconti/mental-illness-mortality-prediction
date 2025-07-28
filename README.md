# Mental illness mortality prediction
Reproduction of paper "Automatic prediction of mortality in patients with mental illness using electronic health records" for predicting predict 30-day mortality in patients from clinical MIMIC-III data set
https://arxiv.org/pdf/2310.12121

Predicting 30-Day Mortality in Patients with Mental Health Diagnoses
Mental disorders significantly impact global health, not only by hindering daily life but also by substantially shortening life expectancy. This project tackles the critical challenge of predicting mortality in patients with mental health diagnoses using predictive machine learning models and electronic health records (EHR).

## Project Overview
Data extracted from the widely-used MIMIC-III clinical dataset, focusing on patients with mental disease diagnoses. The information utilized includes demographic details, prescription records, and procedural information.

## Methodology
Use of four common machine learning algorithms to build our predictive models:

Logistic Regression

Random Forest

XGBoost

K-Nearest Neighbors

## Key Findings
XGBoost was the best-performing model in predicting 30-day mortality. The model relied heavily on drug administrations and procedures recorded during hospitalization and not on demographic data. Notably, Medicare emerged as a significant feature, likely reflecting the higher baseline risk associated with older populations. Consistent with existing literature, Oxycodone-Acetaminophen ranked among the most important predictors. This may indicate that patients requiring stronger pain management are often those in more critical condition, thus linking opioid use with increased short-term mortality.
