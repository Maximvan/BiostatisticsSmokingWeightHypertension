# Biostatistics Project 1: Investigating the Impact of Smoking and Weight on Hypertension

## Introduction
A comprehensive analysis was conducted to investigate the impact of smoking and weight on hypertension by evaluating the systolic blood pressure of 500 individuals. The study involved observational units, exploring the relationship between systolic blood pressure, smoking status, and weight categories through statistical tests.

## Data Exploration
The dataset, named SBP_smoking, was loaded and summarized. Descriptive statistics revealed the distribution of non-smokers, smokers, and individuals in different BMI categories. Assumptions for general linear models were evaluated, demonstrating data independence within and between groups.

## Statistical Tests
1. **T-Test for Smoking Effect:**
   - Result: Smoking has a statistically significant effect on systolic blood pressure (p < 0.001).
2. **ANOVA for BMI Effect:**
   - Result: BMI categories have a statistically significant effect on systolic blood pressure (p < 0.001).
3. **Two-Way ANOVA for Smoking and BMI Interaction:**
   - Result: Both smoking and BMI have statistically significant effects on systolic blood pressure. Interaction term is not significant (p > 0.05).
4. **General Linear Model (GLM):**
   - Result: Smoking, overweight, and obesity are significantly associated with systolic blood pressure. Interaction terms are not significant. The model explains approximately 9.73% of the variability.

## Conclusion
The GLM analysis revealed significant associations between systolic blood pressure, smoking, and BMI categories. Smoking and BMI (overweight and obesity) exhibited significant positive effects on systolic blood pressure. However, the model explained only a small proportion of the variability in blood pressure.

## Further Reflections
1. **Sample Size:** A larger sample size would enhance the statistical power, especially for detecting smaller effects.
2. **Additional Variables:** Consideration of additional variables (age, gender, medication use, social class, ethnicity, family history) could provide a more comprehensive understanding of the relationships.
3. **Model Complexity:** The model could be refined by addressing multicollinearity and exploring interactions with additional variables.
4. **Balance in Variables:** Striking a balance between adding informative variables and avoiding overfitting is crucial for model accuracy and interpretability.

The study presents valuable insights into the relationship between smoking, weight, and systolic blood pressure, emphasizing the potential for further exploration and refinement in future research endeavors.
