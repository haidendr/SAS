# Closing the Gap: Immunization Compliance and Predictive Analytics for HEDIS Measures

## Overview
This project investigates immunization disparities and predictive strategies to improve adolescent vaccine compliance across Oregon. Using publicly available data from the **Oregon Immunization Program’s Tableau dashboard**, the study evaluates adherence to two critical **HEDIS** measures:

- **Childhood Immunization Status (CIS)**
- **Immunizations for Adolescents (IMA)**

By applying statistical and machine learning techniques, the project identifies geographic and demographic disparities, builds predictive models, and offers actionable insights to support targeted outreach and improve public health outcomes.

## Objectives
- Analyze ZIP-level immunization rates across Oregon’s 36 counties
- Identify geographic and demographic disparities in vaccine compliance
- Evaluate adherence to CIS and IMA benchmarks
- Develop predictive models to flag ZIP codes at risk of under-immunization
- Assess the influence of specific vaccines (HPV, COVID-19, influenza) on series completion
- Support data-driven public health interventions and risk stratification

## Data Sources
- **Primary Source**: Oregon Immunization Program’s Tableau Dashboard
- **Population**: Children aged 0–13 across all Oregon ZIP codes
- **Vaccines Analyzed**:
  - Tdap
  - MenACWY
  - HPV (initiation and completion)
  - Influenza
  - COVID-19

## Methods

### Statistical Analysis
- **Descriptive Statistics**: Baseline coverage and trends
- **ANOVA & Kruskal-Wallis**: Geographic disparities across counties
- **Pearson Correlation & Regression**: Vaccine predictors of series completion
- **T-tests**: Population bin comparisons (10–49 vs. ≥50 individuals)

### Predictive Modeling
- **Random Forest Classifier** (SAS PROC HPFOREST)
  - 100 decision trees
  - Binary risk flag for ZIPs below threshold (e.g., 0.60)
  - Evaluated via OOB error and variable importance
- **General Linear Model (GLM)**: Influence of vaccine rates, population size, and geography on noncompliance

## Key Findings
- Significant variation in vaccine uptake across counties
- Pronounced gaps in **COVID-19** and **influenza** coverage
- **HPV completion** is the strongest predictor of adolescent series adherence
- ZIP codes with smaller populations show unique compliance challenges
- Predictive models successfully flag high-risk areas for targeted outreach

## Implications
This research provides a framework for:
- Enhancing HEDIS performance
- Reducing immunization gaps
- Advancing health equity across Oregon’s pediatric and adolescent populations

Healthcare organizations and policymakers can leverage these insights to allocate resources more effectively and improve preventive care outcomes.

## Tools & Technologies
- **Excel:** Data preprocessing and cleaning
- **SAS:** Statistical analysis, machine learning, and visualization

## Citation
If you use this research or build upon it, please cite appropriately. Suggested citation format:
*Closing the Gap: Immunization Compliance and Predictive Analytics for HEDIS Measures*. Oregon Immunization Program Data Analysis. [Diane Haiden], 2025.
