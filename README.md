# Ionospheric Radar Classification Using Linear SVM and Random Forest  

## Overview  
This project focuses on **classifying ionospheric radar data** using **machine learning models** such as **Linear Support Vector Machine (SVM)** and **Random Forest**. The dataset is preprocessed, analyzed, and classified to distinguish between different ionospheric radar signals.  

## Tech Stack  
- **Python**  
- **scikit-learn**  
- **pandas**  
- **matplotlib & seaborn**  
- **imbalanced-learn (SMOTE for oversampling)**  

## Project Workflow  
1. **Importing Required Libraries**  
2. **Loading & Preprocessing the Dataset**  
   - Handling missing values (if any)  
   - Dropping irrelevant columns  
   - Feature scaling  
3. **Exploratory Data Analysis (EDA)**  
   - Checking feature correlation using a heatmap  
   - Visualizing class distribution  
4. **Splitting the Data**  
   - Using **Stratified Train-Test Split** to maintain class balance  
5. **Model Training & Evaluation**  
   - **Linear SVM** Model  
   - **Random Forest** Model  
   - Evaluating performance using classification reports  
6. **Handling Class Imbalance**  
   - **Oversampling using SMOTE**  
   - Retraining models with balanced data  
7. **Final Predictions & Analysis**  

## Getting Started  
To run this notebook, install the required dependencies:  

```bash  
pip install pandas scikit-learn matplotlib seaborn imbalanced-learn  
```

Then, open the Jupyter Notebook and execute the cells in order.  

## Results  
- Performance is measured using **classification reports** (precision, recall, F1-score).  
- The impact of **SMOTE oversampling** on model performance is analyzed.  
- A comparison is made between **Linear SVM** and **Random Forest** models.  
