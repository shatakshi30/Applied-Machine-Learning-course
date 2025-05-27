# Module 08: Unsupervised Clustering and Outlier Removal

### Assignment Summary
In this assignment, the focus was on using unsupervised learning to identify structure in a synthetic dataset composed of species with two defining features. The task was to cluster the data, identify potential outliers, and build a more accurate classifier by refining the dataset.

### Tasks Covered
- Visualized the dataset using a scatterplot to estimate the number of natural species clusters.
- Determined approximate **feature ranges** for each species to understand how they separate in feature space.
- Applied **K-Means clustering** to identify anomalies:
  - Outliers were defined as data points farthest from the cluster centroids.
- Applied **DBSCAN clustering** as an alternative anomaly detection method:
  - Detected core samples, border points, and noise to determine boundary-defining data.
- Chose one clustering method (K-Means or DBSCAN) to **remove outliers** from the dataset.
- Trained a **Decision Tree classifier** using the cleaned dataset to classify species.
- Visualized the decision tree using appropriate plotting tools for interpretability.
- Compared model performance before and after outlier removal to show the improvement in classification accuracy and generalization.

### Highlights
- Unsupervised clustering revealed well-defined species boundaries in feature space.
- Outlier removal significantly enhanced decision tree performance and boundary clarity.
- Demonstrated that **data refinement improves model robustness** beyond simple accuracy gain, especially in noisy biological datasets.

### File
- `Shewale-Assign8.ipynb`: Contains the full analysis including scatterplots, clustering, anomaly detection, data cleaning, decision tree training, and performance evaluation.
