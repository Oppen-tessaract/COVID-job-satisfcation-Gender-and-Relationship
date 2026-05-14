# Investigating Job Satisfaction Before and After COVID-19: Is There an Association with Gender?

## Overview
This project examines whether job satisfaction changed between the pre-COVID and post-COVID periods and whether any change was associated with gender. The analysis uses data from the Understanding Society: UK Household Longitudinal Study and combines descriptive statistics, regression models, and visualisations.

## Research Questions
1. Did job satisfaction change between the pre-COVID period (2018–2019) and the post-COVID period (2021–2022)?
2. Is the change in job satisfaction before and after the pandemic associated with gender?

## Dataset
This project uses the UK Household Longitudinal Study, a nationally representative survey of households in the United Kingdom. The analysis draws on individual-level data from Wave 10 and Wave 13 of the adult interview response files.

## Data Preparation
The analysis used job satisfaction, gender, and age variables from both waves. The data were cleaned and combined into one dataset for comparison across periods.

Key preparation steps included:
- selecting the relevant variables from each wave,
- creating a binary period variable for pre- and post-COVID comparison,
- recoding job satisfaction into a binary outcome,
- recoding gender into a binary variable,
- filtering out invalid or missing responses,
- and grouping age into categories for descriptive comparison.

## Descriptive Analysis
The table of satisfaction levels showed that job satisfaction remained very high in both periods. Only small differences were observed between men and women before and after COVID-19. Overall, the proportions of satisfied workers changed very little across time.

The age-group figure suggested that satisfaction patterns varied slightly across age groups, with younger workers showing a small decline after COVID-19 and older workers showing slightly different patterns by gender. However, these differences were modest.

## Regression Analysis
Two linear regression models were estimated:
- Model 1 included period and gender.
- Model 2 added an interaction between period and gender.

The results showed that neither period nor gender had a statistically significant effect on job satisfaction. The interaction term was also not significant, and the model comparison suggested that adding the interaction did not improve model fit.

## Key Findings
- Job satisfaction remained very high in both periods.
- There was no statistically significant change in job satisfaction between pre-COVID and post-COVID periods.
- There was no statistically significant difference in job satisfaction between men and women.
- The interaction between period and gender was not significant.
- Age-group patterns showed only small differences across periods and genders.

## Limitations
This analysis focuses only on employed respondents with valid job satisfaction responses, which may introduce selection bias. The binary measure of satisfaction simplifies the original response scale and may hide smaller differences. In addition, the analysis compares only two waves, so it does not capture the full pandemic period.

## Conclusion
The results suggest that job satisfaction stayed consistently high before and after COVID-19, with no statistically significant differences by gender or by period. The interaction between gender and period was also not significant, indicating that changes over time were similar for men and women.

