# Module 03: Preprocessing and Framing a Classification Problem

### Assignment Summary
This assignment focused on data exploration and preprocessing using the **"Suicide Rates Overview 1985 to 2016"** dataset from Kaggle. The goal was to define a real-world machine learning problem and build a working classification prototype to distinguish between high and low suicide rates.

### Tasks Covered
- Framed a meaningful machine learning question centered on global suicide rates and prevention insights.
- Justified the formulation of the problem as a **binary classification** task (high vs. low suicide rate).
- Discussed alternative ML formulations, including regression and unsupervised clustering.
- Selected the appropriate **dependent variable** (e.g., suicide rate per 100k population) and converted it into binary categories.
- Performed **feature selection and ranking** based on correlation with the target variable.
- Carried out **data preprocessing**:
  - Dropped irrelevant and derived features
  - Handled missing data
  - Converted categorical features using encoding techniques
- Built and evaluated a **baseline classification model** to predict suicide rates using the cleaned dataset.

### Highlights
- Identified critical features such as **age group**, **sex**, and **GDP per capita** as potential drivers of suicide trends.
- Demonstrated careful preprocessing by avoiding redundancy (e.g., excluding both `country` and `country-year`).
- Successfully developed a working classification pipeline suitable for further improvement in future modules.

### File
- `Shewale-Assign3_final.ipynb`: Full implementation including exploratory data analysis, feature engineering, correlation matrix, and classifier prototype.
