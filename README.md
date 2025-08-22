# Analysis of Early Childhood Development Trajectories in Social Perinatal Health Contexts

## Tools used for this project

- AirTable
- Excel
- Power BI
- Jupyter Notebook
- Python

## Overview
This project aims to evaluate developmental progress among children receiving social and health services within a vulnerable population. By analyzing early childhood developmental scores, the study seeks to compare outcomes between children with early intervention 9during pregnancy) versus those with later engagement. The ultimate goal is to identify key social determinants influencing developmental delays and to inform targeted interventions that improve early childhood health outcomes.

## Problem Statement and Objectives
Children in vulnerable settings are at increased risk for developmental delays, depending on the social determinants of health of their environement and affecting their families. This analysis seeks to quantify these risks by examining developmental scores over time and comparing children with varying degrees of service engagement. 

Specific objectives include: 

- Assessing developmental trajectories across different cohorts and service participation levels.
- Identifying the social determinants or family caracteristics (e.g. immigration status) most strongly associated with delays.
- Providing evidence-based insights to optimize early childhood intervention strategies.

## Data Sources

Data were collected from multiple sources within the organization’s infrastructure. Client demographic and social determinant information were obtained from site-specific databases, which included variable details on social and environmental factors. Developmental assessment scores (ASQ) were compiled via an Airtable form completed by organization staff, focusing on children aged 4-5 years across various locations. Cross-referencing was conducted using anonymized Client ID and Child ID fields, ensuring confidentiality with all nominal identifiers omitted.

## Data Cleaning and Preparation

Data cleaning was conducted in Excel in accordance with the organization's requirements, enabling the team to reproduce the same procedures for future analyses:

- Standardizing and merging datasets from multiple sites into a unified database.
- Eliminating extraneous variables irrelevant to the analysis.
- Harmonizing data types, including date formats, to ensure consistency.
- Cleaning identifier fields by removing extraneous characters from Client ID and Child ID.
- Converting Boolean indicators of social determinants into numerical variables for analysis.
- Encoding categorical risk levels (e.g., “At risk,” “High risk”) into numerical scales.
- Computing aggregate scores at specific developmental milestones (8, 24, and 48 months) by summing relevant sub-scores.

This structured data preparation ensures a robust foundation for subsequent statistical analysis and modeling.
