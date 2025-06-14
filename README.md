### Predicting Chronic Kidney Disease: Exploratory Data Analysis

**Author:** Ruban Sellathurai
---

#### Executive Summary

This project applies the CRISP-DM framework to perform exploratory data analysis (EDA) on a clinical dataset to identify key variables that predict Chronic Kidney Disease (CKD) in patients. The analysis includes thorough data cleaning, visualization, and an initial machine learning baseline model.

---

#### Rationale

Chronic Kidney Disease is a major global health concern, often underdiagnosed until advanced stages. Early prediction can help guide interventions, slow disease progression, and improve patient outcomes. Understanding which clinical features best predict CKD can improve screening and diagnosis.

---

#### Research Question

**Which clinical and laboratory variables are most strongly associated with CKD, and how accurately can we predict CKD status using a baseline machine learning model?**

---

#### Data Sources

- The dataset used: [`kidney_disease.csv`](https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease)
- Contains anonymized clinical, and laboratory information for 400 patients.

---

#### Methodology

- **CRISP-DM framework**: Business understanding, data understanding, data preparation, EDA, and baseline modeling.
- **Data cleaning:** Handling missing values, correcting data types, encoding categorical variables, and removing or imputing outliers.
- **Feature engineering:** Encoding binary and categorical variables for analysis.
- **EDA:** Visualizing target distribution, feature distributions, relationships with CKD, and correlation matrix.
- **Baseline modeling:** Logistic Regression using features selected by correlation strength with CKD, evaluated by accuracy, confusion matrix, and classification report.

---

#### Results

- The dataset has moderate class imbalance (62% CKD, 38% non-CKD).
- Key predictors identified include: low hemoglobin, high serum creatinine, high albumin in urine, diabetes, hypertension, and age.
- The baseline logistic regression model achieves high accuracy and recall, demonstrating the effectiveness of these clinical features in predicting CKD.

---

#### Next Steps

- In Module 24: Test additional machine learning models (e.g., Random Forest, SVM), further tune model parameters, explore advanced feature engineering, and prepare a final report for both technical and non-technical audiences.
- Consider addressing class imbalance using techniques such as resampling or adjusting class weights.

---

#### Outline of Project

- [Link to EDA notebook](kidney_disease_eda.ipynb)

---

##### Contact and Further Information

For questions or further discussion, please contact Ruban.sellathurai@gmail.com

