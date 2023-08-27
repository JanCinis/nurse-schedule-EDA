# nurse-schedule-EDA
EDA of nurses' work schedule in a Czech hospital

/// README ///

Hello! This is my EDA for the ap2020_anonymized.xlsx hospital dataset

The main part is described and can be observed in the Jupiter notebook:
https://github.com/JanCinis/nurse-schedule-EDA/blob/43e44e152cfbffed719fafac63f697f07147c002/Nurse_schedule_EDA.ipynb

Below is a brief guide to each step of my solution:

1. Under Sample Load & Preview you will find:
- Task Description
- Overview of the dataset, including a description of the variables, missing values and counts

2. Univariate analysis shows a visual overview of each variable individually
- Boxplots for numerical values, histograms for categorical values

3. Because the 'odeslán' distribution didn't seem usable, I searched and grouped the values for the Tomajerova nemocnice category and created an Other category for the remaining values.

4. Then follows multivariate analysis
- Comparison of the distribution of the number of doctors and threatened cases as a line chart
- Histogram for comparing reasons (důvod) in terms of threatened cases number for each week
- 3 histograms comparing the distribution of admissions (příjat), departures (odeslán), causes (důvod) for each doctor with the total number of individual cases
- For each plot there are conclusion points

5. Descriptive statistics for examining the normality of the age (ročník) distribution
- Measures of variability, central tendency, Q-Q/P-P plot and conclusion

6. Conclusion list for all the points from above together
- 9 conclusion points

7. EDA recommendations and insights for building a support tool for planning shifts for the next day
- 6 conclusion points
