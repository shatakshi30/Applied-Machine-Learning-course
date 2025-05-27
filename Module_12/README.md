# Module 12: Anomaly Detection – Credit Card Fraud Detection

### Assignment Summary
This assignment focused on building and evaluating models for **credit card fraud detection**, a classic example of **anomaly detection** in a highly imbalanced dataset. The task involved working with the popular Kaggle dataset that simulates real-world financial transaction patterns.

### Tasks Covered
- Explored the dataset:
  - 284,807 transactions with 30 features + 1 class label
  - Noted high class imbalance: only ~0.17% of transactions were fraudulent
- Justified the use of **evaluation metrics** such as F1-score, precision, and recall over accuracy due to the class imbalance.
- Preprocessed the data:
  - Standardized features using scaling
  - Ensured normalization where required for models like SVC and neural networks
- Split the data into **50% training and 50% testing subsets**
- Ran four classifiers **without regularization or pruning**:
  - Support Vector Classifier (SVC)
  - Decision Tree
  - Multi-layer Perceptron (MLPClassifier)
  - Random Forest
- Re-ran SVC, Decision Tree, and MLP with **tree pruning or regularization** using hyperparameter tuning (manual or GridSearchCV)
- Developed a **PyTorch neural network**:
  - With one or two hidden layers
  - Evaluated its performance on the same data split
- Added **Dropout** to the PyTorch model for robustness and retrained the model
- Applied **10-fold cross-validation** to both the Random Forest and both PyTorch models to compare generalization

### Highlights
- Performance improved significantly with regularization and dropout.
- PyTorch models showed comparable or better results than MLPClassifier with enhanced robustness.
- Demonstrated the importance of **model generalization and stability** in high-stakes domains like fraud detection.

### File
- `Shewale_Assign12.ipynb`: Includes data exploration, preprocessing, model training (with and without regularization), PyTorch implementation, and cross-validation comparisons.
