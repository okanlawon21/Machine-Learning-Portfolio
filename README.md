# 🚀 Applied Machine Learning & Predictive Analytics

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Data_Science-blue?style=for-the-badge)

**Author:** Okanlawon Micheal Olatunji  
**Background:** Industrial Physics → Machine Learning Engineering  
---

## 📌 Engineering Philosophy
This repository contains a curated collection of production-grade machine learning pipelines. Coming from an Industrial Physics background, my approach to machine learning is highly systematic. I do not treat algorithms as "black boxes." Instead, I focus on:
1. **Strict Data Hygiene:** Preventing data leakage through rigorous cross-validation and proper pipeline sequencing.
2. **Mathematical Interpretability:** Translating model coefficients and feature importances into actionable business logic.
3. **Occam's Razor:** Prioritising simpler, computationally efficient models (like linear regressions) over heavy ensembles when performance is mathematically tied.

---

## 📂 Project Architecture

### [01. Clinical Diagnostics: Handling Severe Imbalance](./01_Diabetes_Diagnostics)
* **Domain:** Healthcare / Tabular Data
* **Senior ML Skills:** Addressed critical class imbalance in medical data using `scale_pos_weight` in XGBoost. Focused on the Recall/Precision trade-off, recognising that optimising for "False Negatives" is the most critical business metric in clinical diagnostics.

### [02. Real Estate Regression: Feature Engineering & Grid Search](./02_California_Housing)
* **Domain:** Real Estate / Regression
* **Senior ML Skills:** Built a baseline model, then engineered domain-specific mathematical ratios (e.g., `Rooms_per_Household`). Wrapped a Random Forest in a 5-Fold `GridSearchCV` to systematically hunt for optimal tree depth and split criteria without overfitting.

### [03. Unstructured NLP: News Article Classification](./03_News_NLP_Classification)
* **Domain:** Natural Language Processing (NLP)
* **Senior ML Skills:** Processed noisy, unstructured text using custom Regular Expressions (Regex). Built a robust `TfidfVectorizer` pipeline to convert text into sparse mathematical matrices for multi-class logistic classification.

### [04. Survival Analysis: Pipeline Sequencing (Titanic)](./04_Titanic_Survival)
* **Domain:** Demographics / Binary Classification
* **Senior ML Skills:** Demonstrated strict leakage prevention by applying `SimpleImputer` and `StandardScaler` *only after* the Train/Test split. Extracted tree-based `feature_importances_` to mathematically prove which demographic variables drove the survival predictions.

### [05. Unsupervised Learning: Customer Segmentation](./05_Customer_Segmentation)
* **Domain:** Retail / Clustering
* **Senior ML Skills:** Applied the K-Means algorithm to raw, unlabeled data. Utilised the Elbow Method and Silhouette Scores to mathematically validate the optimal number of clusters ($k$), ultimately translating the vectors into actionable marketing personas.

### [06. Dimensionality Reduction: The PCA Trade-off](./06_Breast_Cancer_PCA)
* **Domain:** Oncology / High-Dimensional Data
* **Senior ML Skills:** Conducted a scientific A/B test comparing a model trained on raw data vs. PCA-compressed data. Documented the engineering trade-off: while PCA speeds up training time, the loss of variance and interpretability is a net-negative for this specific medical dataset. 

### [07. Multi-Class Cultivar Classification: Occam's Razor](./07_Wine_Cultivars)
* **Domain:** Chemical Analysis / Multi-Class Classification
* **Senior ML Skills:** Handled varying chemical measurement scales using standardisation. Achieved 100% accuracy with both a Random Forest and a Logistic Regression model, but successfully applied *Occam's Razor* to select the simpler, lighter linear model for final theoretical deployment to save on compute costs.

---

## 🛠️ Core Tech Stack
* **Languages:** Python, SQL
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`, `xgboost`
* **Visualisation:** `matplotlib`, `seaborn`
* **Engineering Tools:** Git, Jupyter, Custom Pipelines, Hyperparameter Tuning

---
## 📫 Current Focus: Energy AI & Climate Tech
I am currently bridging my background in Industrial Physics with Deep Learning to tackle challenges in the energy sector. My active research involves **Time-Series Forecasting (LSTMs, Temporal Fusion Transformers)** and **Physics-Informed Neural Networks (PINNs)** for energy demand and grid optimisation.

* **LinkedIn:** [Micheal Okanlawon](https://www.linkedin.com/in/micheal-okanlawon/)
* **X / Twitter:** [@OlatunjiokanAI](https://x.com/OlatunjiokanAI)
