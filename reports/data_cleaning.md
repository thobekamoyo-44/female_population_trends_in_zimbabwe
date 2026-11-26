# Data Cleaning and Preparation

## 1. Dataset Inspection

The original Zimbabwe health dataset was inspected using Python and Pandas.

The dataset contained:

- 10,535 rows
- 6 columns
- 604 health indicators
- Data covering 1960–2025

The original columns were:

- Country Name
- Country ISO3
- Year
- Indicator Name
- Indicator Code
- Value

## 2. Data Quality Checks

The dataset was checked for missing values and duplicate records.

### Missing Values

The inspection found no missing values in the dataset.

Therefore, no missing-value imputation or deletion was required.

### Duplicate Records

The dataset was checked for exact duplicate rows.

No exact duplicate records were identified.

## 3. Data Filtering and Preparation

The dataset was restricted to Zimbabwe using its country code (ZWE).

Relevant women's health indicators were then selected for further analysis.

These included:

- Female population
- Total fertility rate
- Contraceptive use
- Difficulty accessing healthcare due to distance
- Median age at first marriage
- Teenage pregnancy and motherhood

## 4. Feature Preparation

A decade classification was created from the Year column to support comparisons across decades.

This allowed the analysis to examine long-term trends rather than focusing only on individual years.

Wealth-quintile indicators were also grouped to compare reproductive health outcomes across different wealth levels.

## 5. Final Preparation

After inspection and preparation, the selected indicators were ready for exploratory data analysis and visualisation.

The preparation process focused on filtering relevant records, checking data quality and organising the data for meaningful comparisons.