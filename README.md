# Food Access Research Project

## Overview
This project analyzes the 2019 Food Access Research Atlas dataset to investigate the relationships between food accessibility, demographic features, income levels, and geographic factors across different tracts in the United States. The analysis aims to uncover insights into how these factors interact and influence the distribution of resources like Supplemental Nutrition Assistance Program (SNAP) benefits.

## Objectives
The primary goals of this project include:
1. Understanding the distribution of median family income across urban and rural areas.
2. Analyzing the relationship between food accessibility (low-income and low-access flags) and SNAP benefits.
3. Investigating the demographic characteristics (race, age, etc.) of low-income vs. high-income tracts.
4. Exploring racial distributions between low-income and high-income tracts.
5. Identifying factors associated with the distribution of SNAP benefits.
6. Examining correlations between demographic, income, and accessibility features.
7. Comparing urban and rural areas regarding population and poverty rates.
8. Testing for significant differences in poverty rates and median family incomes between urban and rural areas.

## Dataset
- **Source**: U.S. Department of Agriculture (USDA) Food Access Research Atlas ([link](https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data/)).
- **Description**: Contains data on food access indicators, SNAP program usage, and demographic distributions.
- **Key Features Used**:
  - **Geographic**: State, County, Urban (flag for urban/rural tract).
  - **Demographics**: Population counts (total, by race, age groups), housing units, and vehicle access.
  - **Economic**: Poverty rate, median family income, and SNAP benefits.
  - **Accessibility**: Low-income and low-access flags (e.g., LILATracts_half, LATracts10).

## Methodology
1. **Data Preprocessing**:
   - Extracted relevant features.
   - Conducted exploratory data analysis (EDA) to understand data distributions and structure.
   - Cleaned and transformed data for analysis.

2. **Analysis**:
   - Visualized income distribution across urban and rural tracts.
   - Performed correlation analysis between demographic, income, and accessibility features.
   - Conducted hypothesis testing to compare poverty rates and incomes across different categories.

3. **Tools Used**:
   - **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scipy, Scikit-learn.
   - **Statistical Methods**: Descriptive statistics, correlation analysis, hypothesis testing.

## Results
- Visualized key trends and patterns in food accessibility, income, and demographic distributions.
- Identified significant differences in income levels and poverty rates between urban and rural areas.
- Explored correlations between SNAP benefits, income levels, and demographic factors.

## Conclusions
The project provides valuable insights into food access disparities and demographic characteristics influencing SNAP benefit distributions. These findings can help policymakers design targeted interventions to address food accessibility challenges.

