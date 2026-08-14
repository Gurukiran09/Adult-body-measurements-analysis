# Adult Anthropometric Analysis

## Overview

This project explores adult male and female anthropometric data using Python. The analysis looks at differences in weight, BMI, body measurements, and body proportion ratios between the two groups.

The project uses NumPy for data processing and calculations and Matplotlib for visualising the results.

## Data Source

The data comes from the National Health and Nutrition Examination Survey (NHANES). The adult male and female body measurement datasets were obtained from the Gagolewski teaching-data repository.

Source: https://github.com/gagolews/teaching-data/tree/master/marek

The datasets used are:

- `nhanes_adult_male_bmx_2020.csv`
- `nhanes_adult_female_bmx_2020.csv`

## What the Project Covers

The analysis includes:

- Comparing male and female weight distributions using histograms and boxplots.
- Calculating summary statistics to describe the weight distributions.
- Calculating BMI for the female participants.
- Standardising the female measurements using z-scores.
- Exploring relationships between height, weight, waist circumference, hip circumference, and BMI.
- Calculating Pearson and Spearman correlation coefficients.
- Calculating waist-to-height and waist-to-hip ratios for both males and females.
- Comparing the distributions of these ratios.
- Examining the standardised measurements of participants with the five lowest and five highest BMI values.

## Variables

The original datasets contain seven measurements:

- Weight (kg)
- Standing height (cm)
- Upper arm length (cm)
- Upper leg length (cm)
- Arm circumference (cm)
- Hip circumference (cm)
- Waist circumference (cm)

BMI is added to the female dataset, while waist-to-height and waist-to-hip ratios are added to both datasets during the analysis.

## Tools Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Repository Contents

```text
Adult-body-measurements-analysis/
├── Adult_Anthropometric_Analysis.ipynb
├── nhanes_adult_male_bmx_2020.csv
├── nhanes_adult_female_bmx_2020.csv
├── README.md
└── .gitignore
```

## Conclusion

The project provides a clear comparison of adult male and female anthropometric measurements using numerical and visual analysis. The results show how measures such as weight, BMI, waist-to-height ratio, and waist-to-hip ratio can be used to examine differences and relationships within the data. Overall, the analysis demonstrates how NumPy and Matplotlib can be used to work with and interpret multidimensional health-related data.
