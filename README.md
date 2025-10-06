# Heart Attack Classifier

This project focuses on predicting the likelihood of a heart attack using various machine learning models.  
The goal was to build a full end-to-end pipeline — from data exploration and cleaning to model training, evaluation, and interpretation — to see how different algorithms perform on a real medical dataset.

---

## Dataset

- **Source:** [Kaggle - Heart Attack Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)  
- **Size:** 303 observations × 14 features  
- **Features include:** age, sex, cholesterol, resting blood pressure, maximum heart rate, and other clinical indicators.  
- The target variable indicates whether a patient is likely to have a heart attack (`1`) or not (`0`).

---

## Tools & Libraries

- **Languages:** Python  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, SciPy, scikit-learn

---

## Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Visualized feature distributions and relationships  
   - Checked for missing values and class balance  
   - Identified key predictors of heart attack likelihood

2. **Data Preprocessing**  
   - Feature scaling  
   - Train-test splitting  
   - Handled categorical variables

3. **Modeling**  
   - Trained multiple classification models, including:  
     - Logistic Regression  
     - k-Nearest Neighbors  
     - Bernoulli Naïve Bayes  
     - Decision Trees  
     - SVM  
     - Random Forest

4. **Evaluation**  
   - Accuracy, AUC, confusion matrices, and ROC curves  
   - Compared performance across models

---

## Results

- **Bernoulli Naïve Bayes** achieved the **best performance** with:  
  - **Accuracy:** 86.9%  
  - **AUC:** 0.94  

- This outperformed logistic regression, k-NN, and SVM on this dataset.  
- Visualizations (ROC curves and feature relationships) helped interpret model behavior and dataset characteristics.
