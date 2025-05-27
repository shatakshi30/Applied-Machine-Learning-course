# Module 02: Data Features and Correlation Analysis

### Assignment Summary
This assignment focused on understanding different types of features, comparing key classifiers, exploring advanced classification metrics, and performing correlation analysis from scratch using real-world admissions data.

### Tasks Covered
- Compared classifiers: **Perceptron**, **SVM**, **Decision Tree**, and **Random Forest** based on speed, robustness, feature handling, and underlying methodology.
- Defined and illustrated examples for various feature types:
  - Numerical
  - Nominal
  - Date
  - Text
  - Image
  - Dependent variable
- Researched and explained alternative model evaluation metrics including:
  - Precision, Recall
  - F1-Score
  - Specificity, etc., along with definitions of TP, FP, FN, TN.
- Implemented a correlation matrix calculation **from scratch** (without using NumPy functions like `mean`, `std`, or `cov`) on the `Admission_Predict.csv` dataset.
- Verified the custom correlation matrix with `pandas.DataFrame.corr()`.

### Highlights
- Explained why 'Serial No.' should not be used in modeling.
- Identified **GRE Score** and **CGPA** as having the strongest correlations with 'Chance of Admit'.
- Demonstrated correct diagonal values (1s) in the correlation matrix.
- Successfully derived correlation metrics manually, reinforcing understanding of statistical fundamentals.

### File
- `Shewale-Assign2.ipynb`: Complete notebook with detailed answers, classifier comparisons, custom correlation matrix implementation, and interpretive analysis.
