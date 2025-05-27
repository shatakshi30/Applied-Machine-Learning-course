# Module 06: Ensemble Learning with Bagging – Heart Disease Classification

### Assignment Summary
This assignment explored **ensemble learning** using the **Bagging** technique. The goal was to classify heart failure presence using a Kaggle dataset by comparing standard classifiers and ensembles of weak classifiers. Custom functions were written for fitting and aggregating predictions from ensembles to evaluate their robustness across different training subsample ratios.

### Tasks Covered
- Loaded the **heart.csv** dataset from Kaggle and performed data preprocessing:
  - Converted nominal features using OneHotEncoding
  - Ensured data was suitable for classifiers requiring numerical input
- Evaluated the baseline performance of individual classifiers using 10-fold cross-validation:
  - GaussianNB
  - Linear SVC
  - MLPClassifier
  - DecisionTreeClassifier
  - RandomForestClassifier (as a built-in ensemble benchmark)
- Created **ensembles of 100 weak classifiers** for the first four models using underpowered hyperparameters (e.g., small hidden layers or shallow trees).
- Implemented:
  - `ensemble_fit()` to train each classifier on a subsampled version of the training data (bagging).
  - `ensemble_predict()` to aggregate predictions using probability-based majority voting.
- Compared performance of ensembles at various subsample ratios (0.2, 0.05) with regular classifiers.
- Extended the evaluation to six subsample ratios: 0.005, 0.01, 0.03, 0.05, 0.1, 0.2
- Plotted comparative performance curves for ensembles vs. regular classifiers across ratios.

### Highlights
- Ensembles consistently outperformed individual classifiers at low training sample ratios.
- Noted diminishing returns at higher sampling ratios for some models.
- Observed that even weak classifiers, when aggregated, produce competitive and stable performance.
- Demonstrated clear visual evidence via 4 comparative plots (ensemble vs. regular classifier) for each model type.

### File
- `Shewale-Assign6.ipynb`: Includes all preprocessing, model building, bagging logic, performance evaluations, and plots.
