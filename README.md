# Admissions-Analysis-of-Certified-Chemical-Dependence-Treatment-Programs-in-New-York-State
A comprehensive analysis of chemical dependence treatment admissions in New York State (2007-2019), focusing on trends, demographics, and substance abuse patterns through data cleaning, relational structuring, and visualization.

# Overview

This project analyzes reported admissions to certified chemical dependence treatment programs throughout New York State (NYS) from 2007 to 2019. The dataset, published by the Office of Addiction Services and Support, provides insights into admissions based on program category, county location, age group at admission, and the primary substance of abuse. The goal of this project is to clean, transform, and analyze the dataset to extract meaningful trends and visualizations that highlight the patterns in addiction treatment admissions across the state.

# Background

Substance abuse treatment programs play a crucial role in addressing addiction and supporting recovery. Understanding admission trends across different counties, age groups, and substance categories can help policymakers, healthcare professionals, and researchers make informed decisions about resource allocation and intervention strategies. This project employs data wrangling, relational structuring, exploratory data analysis, and visualization techniques to gain deeper insights into the dataset.

# Dataset 

https://query.data.world/s/orm7vayxgdtwvfceewvazzo5psj6wn?dws=00000

# Tasks

# Data Loading:

Load the dataset directly from the given URL into the R environment.

# Data Preparation & Cleaning:

Evaluate the dataset for missing values, outliers, and inconsistencies.

Generate summary statistics and visualizations to understand data distribution.

# Relational Data Structuring:

Create four structured data frames:

county: Stores unique county names and their respective county codes.

program_category: Contains unique program categories with assigned identifiers.

primary_substance_group: Lists primary substances of abuse with unique codes.

admissions_data: Contains details on reported admissions, referencing foreign keys instead of textual names.

# Annual Admissions Trend Analysis:

Develop the annualAdmissions() function to compute total admissions per year.

Visualize results using a line chart, highlighting the year with the highest admissions.

# County-Level Admissions Analysis:

Compute the percentage of admissions for each county.

Visualize the top 5 counties with the highest admissions using a bar chart.

# Rehabilitation Facility Admissions & Substance Trends:

Use regular expressions to filter admissions related to rehabilitation facilities.

Identify the most prominent substance of abuse for each age group.

Visualize findings to illustrate substance trends across different demographics.

This project provides a structured approach to analyzing addiction treatment data and presents actionable insights for stakeholders. The final outputs include cleaned datasets, structured relational data, interactive visualizations, and key analytical findings.
