# Module 10: Cybersecurity Intrusion Detection – IDS-2017 Dataset

### Assignment Summary
This assignment focused on developing machine learning models to detect cybersecurity intrusions using the **CIC-IDS 2017 dataset** from the University of New Brunswick. The dataset simulates real-world attack scenarios and includes labeled network traffic data for multiple types of intrusions.

### Tasks Covered
- Registered for and downloaded the **GeneratedLabelledFlows.zip** dataset, containing 8 files, each associated with a different type of network attack.
- Selected one file (Dataset 1) and confirmed the presence of **multiple class labels**.
- Chose an appropriate ML methodology (e.g., Random Forest, SVM, etc.) and justified its suitability for the task.
- Transformed the multi-class problem into a **binary classification task**:
  - `BENIGN` traffic → `0`
  - All attack traffic → `1`
- Explored and **engineered key features**, including:
  - Source and Destination Ports (with one-hot encoding of known ports, grouping others under `'other ports'`)
  - Byte/packet counts and connection duration
- Visualized data with **histograms** to support feature selection.
- Trained and evaluated **multiple classifiers** using **10-fold cross-validation**.
- Generalized the pipeline to process **all 8 datasets** using reusable code.
- Applied the selected classifier to Datasets 2–8 and reported performance metrics.
- Discussed the challenge of building a domain-agnostic ML model (e.g., for cybersecurity) as a non-expert.

### Highlights
- Created a flexible preprocessing and classification pipeline for real-world security data.
- Demonstrated high accuracy and robustness of selected classifier across multiple attack types.
- Addressed issues like **class imbalance** and **feature heterogeneity**.
- Reflected on the importance of domain knowledge in high-stakes ML applications like intrusion detection.

### File
- `Shewale-Assign10.ipynb`: Includes data exploration, preprocessing, binary classification modeling, cross-validation, and performance evaluation across all datasets.
