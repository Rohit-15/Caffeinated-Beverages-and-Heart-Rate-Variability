# Caffeinated-Beverages-and-Heart-Rate-Variability


# Caffeine and Heart Rate Experiment

## Introduction

This repository contains the code, data, and documentation for an experiment designed to investigate the effects of different types of caffeinated drinks on heart rate. The experiment aimed to answer the question: "Do different types of caffeinated drinks affect the heart rate differently?"

## Experimental Design

The experiment followed a pre-test and post-test design with multiple treatment groups:

1. **Treatment Groups**:
   - Coffee (Keurig coffee)
   - Energy drinks (Red Bull)
   - Pre-workout supplements (Caffeine capsules)
   - Water (Control group)

2. **Control Variables**:
   - Age
   - Gender
   - Diet
   - Weight
   - Physical activity level

3. **Dependent Variable**:
   - Heart rate (in beats per minute, bpm) measured using an Apple Watch Series 9

## Data Collection

Heart rate readings were taken before and 30 minutes after the consumption of caffeinated drinks. The data was collected from participants recruited from the cohort, friends, and family using a simple random sampling method.

## Analysis

The analysis involved the following steps:

1. **Data Normality and Constant Variance Tests**:
   - Anderson-Darling test for normality
   - Bartlett's test for constant variance

2. **ANOVA and Post-hoc Tests**:
   - Welch's ANOVA to identify differences between groups
   - Tukey's test for pairwise comparisons

3. **Single Sample t-tests**:
   - Conducted to determine if observed differences were statistically significant

4. **Average Treatment Effect (ATE)**:
   - Calculated for each treatment group

5. **Impact of Control Variables**:
   - Analysis of how control variables (gender, diet, physical activity, age) affected heart rate

## Results and Conclusions

The main findings of the experiment are summarized in the `Analysis.pdf` file. The key takeaways include:

1. Higher doses of caffeine corresponded to increased heart rate changes.
2. Different caffeine sources exhibited varying effects on heart rate, with pre-workout supplements yielding the highest Average Treatment Effect (ATE).
3. Individuals with unhealthy diets and lower physical activity levels demonstrated increased susceptibility to fluctuations in heart rate following caffeine intake.


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to thank all the participants who volunteered for this experiment and contributed to the success of this research.
