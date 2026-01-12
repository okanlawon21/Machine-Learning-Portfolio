# Scikit-learn Hands-on Practice – January 9, 2026

Welcome!  
This README summarizes today’s hands-on machine learning practice, featuring classification, regression, clustering, dimensionality reduction, and complete ML workflow simulation with Python’s scikit-learn library.  
Each task was designed to deepen my understanding of classic ML workflows and prepare me to advance into deep learning frameworks like PyTorch.

---

## 📝 Project Overview

Today’s journey involved step-by-step implementation and troubleshooting of regression and classification algorithms, unsupervised clustering, dimensionality reduction with PCA, and a full end-to-end mini project using real-world datasets. The practice strengthened my skills in building data pipelines, optimizing models, analyzing errors, and visualizing results—all as part of a strong ML foundation.

---

## 🚩 Objectives

- Implement and compare classic ML algorithms (Random Forest, Logistic Regression, SVM, KMeans).
- Build robust pipelines with preprocessing, scaling, feature selection, and dimensionality reduction (PCA).
- Apply unsupervised learning concepts and evaluate clustering performance.
- Use GridSearchCV for hyperparameter tuning and find optimal model settings.
- Visualize results for interpretability (confusion matrix, feature importances, cluster plots).
- Troubleshoot data issues and improve model convergence.
- Emulate a full ML workflow: from EDA to final model selection.

---

## 📁 Datasets Used

- **Wine dataset** (Classification)
- **Breast Cancer dataset** (Classification and PCA)
- **California Housing** (Regression)
- **Synthetic customer data** via `make_blobs` (Clustering)

---

## 🗂️ Work Done

### 1. **Regression and Classification**
- Built and evaluated pipelines using Random Forest and Logistic Regression.
- Scaled features and performed hyperparameter search for optimal accuracy.
- Interpreted model diagnostics with classification reports and confusion matrices.

### 2. **Clustering (Unsupervised Learning)**
- Generated synthetic blobs and grouped samples with KMeans.
- Used elbow method and silhouette score to select the best cluster count.
- Visualized clusters and centers for interpretation.

### 3. **Dimensionality Reduction**
- Reduced dimensionality using PCA, retaining 95% variance.
- Compared classifier performance before and after PCA.
- Analyzed cumulative explained variance and trade-offs of dimensionality reduction.

### 4. **End-to-End Mini Project**
- Conducted the entire supervised ML pipeline: loading, EDA, scaling, multiple model training, evaluation, and final selection.
- Used the Wine dataset for demonstration, with clear documentation and comparative plots.

---

## 📊 Results

- Achieved reliable performance metrics for each supervised and unsupervised task.
- Selected the best models based on test accuracy and visualized strengths/weaknesses.
- Demonstrated ability to handle real-world and synthetic data, and troubleshoot common issues (e.g., convergence, cache errors).
- Created informative visualizations for model interpretation and selection.

---

## 📝 Summary

Today's scikit-learn practice reinforced key skills in data preprocessing, modeling, clustering, dimensionality reduction, evaluation, and troubleshooting.  
With this solid platform, I am well-prepared to begin working with PyTorch and tackle advanced ML and deep learning projects with confidence.

---

## 📅 Date

January 9, 2026



# Scikit-learn Hands-on Regression & Classification — January 11, 2026

Welcome!  
This README summarizes my hands-on experimentation with classic machine learning workflows on real-world datasets using Python’s scikit-learn library.  
I explored regression, model evaluation, feature engineering, model selection/hyperparameter tuning, classification under imbalance, and dimensionality reduction.  
Today’s exercises deepened my core knowledge and prepared me for more advanced ML frameworks.

---

## 📝 Project Overview

This practical session involved step-by-step ML tasks—implementing, testing, visualizing, and troubleshooting the following:
- Regression (Random Forest & Linear Regression)
- Feature engineering and model interpretation
- Overfitting diagnosis and cross-validation
- Hyperparameter tuning with GridSearchCV
- Classification with imbalanced data
- Dimensionality reduction (PCA)
Each task used real datasets (California Housing, Breast Cancer) and showcased the end-to-end workflow: data prep, modeling, evaluation, and explanation.

---

## 🚩 Objectives

- Compare linear and tree-based regression models
- Diagnose overfitting using train/test/CV results
- Apply feature engineering to improve performance
- Tune Random Forest parameters using GridSearchCV and interpret results
- Deal with class imbalance in classification and use proper metrics (precision, recall, F1)
- Perform dimensionality reduction with PCA and analyze trade-offs
- Clearly explain model results and findings

---

## 📁 Datasets Used

- **California Housing** (Regression, feature engineering)
- **Breast Cancer** (Classification, PCA/dimensionality reduction)

---

## 🗂️ Work Done

### 1. **Regression Model Comparison**
- Trained both `LinearRegression` and `RandomForestRegressor` on California Housing data
- Used scaling only for the linear model
- Evaluated with R² and RMSE; visualized results

### 2. **Model Interpretation**
- Extracted coefficients (Linear) and feature importances (RF)
- Visualized most important features for each model and explained the difference

### 3. **Overfitting & Cross-Validation**
- Compared train, test, and 5-fold CV RMSEs to check for overfitting
- Tried increasing `n_estimators` and evaluated effects

### 4. **Hyperparameter Tuning**
- Tuned `n_estimators`, `max_depth`, and `min_samples_split` with GridSearchCV for Random Forest
- Reported the best parameters and compared CV/test RMSEs

### 5. **Feature Engineering Challenge**
- Engineered new features: "rooms per household" and "bedrooms per room"
- Measured RMSE improvement after feature addition

### 6. **Classification with Imbalanced Data**
- Created artificial imbalance in the breast cancer set (~86:14 ratio)
- Trained Logistic Regression and evaluated with precision, recall, F1 (not accuracy)
- Explained why accuracy misleads on imbalanced tasks

### 7. **PCA Trade-off Study**
- Used PCA on breast cancer data (retain 95% variance)
- Compared accuracy & training time of Logistic Regression with/without PCA
- Explained interpretability vs performance trade-off

---

## 📊 Results

- **Random Forest consistently outperformed Linear Regression on non-linear data**
- Feature engineering provided measurable accuracy boosts
- Cross-validation metrics matched test performance, indicating models generalize well
- Grid search tuning found optimal settings quickly, showing how tuning matters
- On imbalanced data, accuracy was misleading; recall/F1 gave better insight
- PCA reduced features and training time—with minimal accuracy loss but at the expense of clear interpretability

---

## 📝 Summary

Today’s scikit-learn work reinforced key ML skills: robust data processing, model building/selection, interpretation, evaluation, and diagnostics.
With this experience, I am ready to move on to deep learning with frameworks like PyTorch and solve more realistic, complex ML problems.

---

## 📅 Date

January 11, 2026