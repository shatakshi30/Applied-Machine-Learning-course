# Module 04: ROC Analysis and Classifier Evaluation on Fake News Dataset

### Assignment Summary
This assignment focused on using ROC curves to evaluate and compare the performance of multiple classifiers on a real-world binary classification task—**fake news detection**. Students were asked to tune hyperparameters and assess trade-offs between True Positive Rate (TPR) and False Positive Rate (FPR) using ROC plots.

### Tasks Covered
- Loaded and preprocessed the **Fake.csv** and **True.csv** news datasets, labeling fake news as `1` and true news as `0`.
- Extracted text features from the `title` column using **TF-IDF** vectorization with dimensionality control.
- Trained and evaluated three classifiers:
  - **Decision Tree**
  - **Random Forest**
  - **Neural Network**
- Tuned at least two hyperparameters per classifier (e.g., depth, number of estimators, learning rate, hidden layer size).
- Conducted **cross-validation** to compute mean TPR and FPR values across models and hyperparameter combinations.
- Plotted **ROC curves** showing performance spread and interpreted decision boundaries.

### Highlights
- Observed expected ROC behavior with trade-offs between detection and false alarm rates.
- Selected the most optimal classifier + hyperparameter setting based on ROC analysis and application goals (e.g., minimizing false positives for real news).
- Added the `text` column as an additional feature vector and re-ran the classification pipeline using TF-IDF on combined title + text.
- Noted significant performance improvement due to richer textual information in the `text` field.

### File
- `Shewale-Assign4.ipynb`: Includes all steps from preprocessing and modeling to ROC visualization and performance comparison.
