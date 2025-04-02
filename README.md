# Fairness-Aware Credit Risk Prediction

![screenshot-localhost_8888-2025 04 02-15_33_00](https://github.com/user-attachments/assets/8e3cff6e-8812-4807-8c4a-7bae4015f95d)


### Project Overview

This project tackles algorithmic bias in credit risk assessment by comparing three fairness-aware machine learning techniques:

1. Reweighting (Fairlearn)
2. Adversarial Debiasing (TensorFlow)
3. Reject Inference (Simulated Missing Data)

**Goal**: Reduce disparities in approval rates between male and female applicants while maintaining model accuracy.

### Dataset

The dataset contains credit application information, including applicant demographics, financial status, and loan outcomes. Key variables include:

- Age
- Gender
- Credit History
- Employment Duration
- Loan Amount
- Default (Target Variable: 1 = Default, 0 = No Default)

### Key Insights:

- Bias exists in baseline models: The unprotected group (male applicants) had 8% higher approval rates.
- Mitigation works: All techniques reduced bias, but adversarial debiasing was most effective.
- Fairness ≠ Accuracy trade-off: The best model improved both fairness and accuracy.

### Conclusion

This project demonstrates that fairness-aware ML is not a zero-sum game—with the right techniques, models can become both more equitable and more accurate. Adversarial debiasing, in particular, shows promise for reducing discrimination in financial decision-making while maintaining performance.

### Source

![German Credit Data from Kaggle](https://www.kaggle.com/datasets/varunchawla30/german-credit-data)
