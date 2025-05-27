# Module 07: Regression Modeling – Predicting Suicide Rates

### Assignment Summary
In this module, the focus shifted from classification to **regression**, using the previously preprocessed **Suicide Rates Overview 1985–2016** dataset. The task was to model the suicide rate (`suicides/100k pop`) as a continuous variable using multiple linear regression, while exploring the impact of encoding strategies and feature engineering.

### Tasks Covered
- Reused the **one-hot encoded dataset** from Module 3 to build a **multiple linear regression** model.
- Calculated the number of regression coefficients in the one-hot encoded model.
- Used the model to make predictions for individuals with:
  - Age: 20
  - Sex: Male
  - Generation: Generation X
- Evaluated model performance using **Mean Absolute Error (MAE)**.
- Reconstructed a new regression model using **numerical transformations** of the original nominal features (`age`, `sex`, and `generation`).
- Compared performance (prediction + MAE) between the **one-hot** model and the **numerically encoded** model.
- Predicted suicide rate for a novel case: Age 33, Male, Generation Alpha (not present in training data).
- Discussed the advantages of using regression vs. classification in this scenario.
- Reflected on the benefit of using **numerical features** over one-hot encoding for regression tasks.

### Highlights
- Demonstrated how the choice of feature encoding (categorical vs. numerical) affects both the number of model coefficients and prediction accuracy.
- Showed how linear regression handles both in-sample and extrapolated predictions (e.g., unseen categories).
- Used interpretability of regression to justify use in policy-driven modeling tasks like public health analysis.

### File
- `Shewale-Assign7.ipynb`: Complete regression pipeline with both encoding strategies, prediction logic, error metrics, and discussion of model selection.
