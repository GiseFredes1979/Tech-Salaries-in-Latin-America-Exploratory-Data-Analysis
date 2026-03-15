# Tech Salaries in Latin America — Exploratory Data Analysis

## Project Overview

This project explores salary patterns in the technology sector across Latin America using data from the Stack Overflow Developer Survey.

The analysis focuses on understanding how different factors such as professional experience, job role, work modality, and geographic location influence salary levels in the regional technology market.

The goal is to identify key patterns in salary distribution and explore the factors associated with higher income levels among developers in Latin America.

---

## Dataset

The analysis uses data from the **Stack Overflow Developer Survey**, one of the largest global surveys of software developers.

From the original dataset (114 variables), a subset of relevant variables was selected:

* Country
* ConvertedCompYearly (annual salary in USD)
* YearsCodePro (professional experience)
* Employment
* RemoteWork
* DevType

The dataset was filtered to include only developers working **full-time** in selected **Latin American countries**.

---

## Data Cleaning and Preparation

Several preprocessing steps were performed before conducting the analysis:

* Selection of relevant variables from the original dataset
* Filtering for full-time employed developers
* Restricting the dataset to Latin American countries
* Handling missing values in key variables
* Converting the `YearsCodePro` variable to numeric format
* Detecting and removing extreme salary outliers above USD 500,000
* Removing roles and countries with insufficient observations

These steps ensured a more reliable dataset for analysis.

---

## Exploratory Analysis

The analysis was structured into several sections:

### 1. Salary Distribution in Latin America

Examines how salaries are distributed across different ranges and identifies the proportion of high salaries within the regional market.

### 2. Professional Experience and Salary

Explores the relationship between years of experience and salary levels.

### 3. Professional Role and Salary

Analyzes salary differences across different developer roles and evaluates how specialization may influence income.   

4. Remote Work and High Salaries

Investigates whether remote work is associated with a higher probability of earning salaries above USD 100,000.

5. Country Influence on Salaries

Examines regional differences by analyzing salary levels and experience across Latin American countries.

Key Findings

Several important insights emerge from the analysis:

The majority of salaries in the Latin American tech market are concentrated below USD 100,000 annually.

Professional experience is positively associated with salary levels, but it is not the only determining factor.

Developer roles show significant salary variation even among professionals with similar experience.

Remote work is strongly associated with higher salaries.

Developers earning high salaries are predominantly working remotely, suggesting participation in global labor markets.

Overall, the results suggest that access to international job markets may play a key role in achieving higher salaries in the Latin American technology sector.

Tools and Libraries

The analysis was conducted using Python and the following libraries:

pandas

numpy

matplotlib

seaborn

Repository Structure
tech-salaries-latin-america-eda
│
├── tech_salaries_latam_eda.ipynb
└── README.md
Author

Gisela Fredes
Data analysis project focused on exploratory data analysis and labor market insights in the technology sector.

