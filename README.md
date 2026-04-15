# Healthcare-data-analysis

# Overview

This project presents an exploratory and statistical analysis of Medicare cost data to uncover insights into disease prevalence, treatment costs, and demographic variations across the United States.

The analysis focuses on identifying:

Most common medical conditions
Cost distribution across treatments
Demographic (gender & race) differences
Expense patterns across percentiles
# Key Objectives
Analyze prevalence of major medical conditions
Compare treatment costs across diseases
Study cost distribution (inpatient vs outpatient)
Evaluate demographic differences using statistical methods
# Exploratory Analysis Insights
# Disease Prevalence
Heart-related conditions are the most prevalent across all states and within each state
Stroke is among the least prevalent conditions
# Cost Distribution
Stroke has the highest treatment cost despite low prevalence
Inpatient expenses dominate higher cost percentiles
Outpatient expenses dominate lower cost percentiles
# Demographic Trends
Disease prevalence is relatively uniform across genders
White patients show the highest overall prevalence nationally
State-level variations exist due to demographic distribution

# Statistical Analysis Insights
# Cost Comparison
Stroke and cancer have the highest treatment costs
Stroke has a slightly higher mean cost than cancer, but:
The effect size is small → difference is not practically significant
# Distribution Across Demographics
Diseases are distributed differently across race and gender
This is supported by the Chi-Squared Test
# Gender-Based Probability
Male patients have a higher probability of:
Ischemic heart disease
Diabetes
However:
Odds ratios are only slightly > 1 → weak effect
# Race-Based Probability
White patients have a higher probability of:
Ischemic heart disease
Diabetes
Again:
Odds ratios are only slightly > 1 → not strongly significant
# Key Takeaways
Heart disease dominates in prevalence, but stroke drives costs
Cost burden is heavily influenced by inpatient care
Demographic differences exist, but most effects are weak
Statistical tests confirm variation, but practical significance is limited
# Tools & Technologies
Python (Pandas, NumPy)
Data Visualization (Matplotlib / Seaborn / Power BI)
Statistical Testing (A/B testing,Chi-Squared Test, Odds Ratio)
