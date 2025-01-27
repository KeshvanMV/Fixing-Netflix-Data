# Fixing-Netflix-Data
# 📊 Netflix Movies Data Cleaning & Imputation Project

**Author:** Keshvan Vijay Rathnam  
**Date:** January 24, 2025  

---

## 📝 Project Overview  

This project focuses on cleaning and preprocessing a Netflix movies dataset, tackling challenges related to missing values in key columns such as `Boxoffice` and `Languages`. Instead of dropping valuable data, various data imputation techniques—including statistical methods and machine learning models—were explored to retain and enrich the dataset.  

---

## ⚙️ Project Workflow  

1. **Data Understanding & Exploration:**  
   - Identified missing values and patterns within the dataset.  
   - Standardized column names for consistency and ease of access.  

2. **Handling Missing Values:**  
   - Imputed missing values using domain knowledge and data-driven techniques.  
   - Used country names from the `Tags` column to infer missing languages.  
   - Applied interpolation and median imputation for numeric columns.  

3. **Predictive Imputation:**  
   - Machine learning models such as Random Forest and XGBoost were used to predict missing `Boxoffice` values.  
   - Model evaluation metrics were used to validate performance.  

4. **Evaluation & Visualization:**  
   - Visualized data before and after imputation to confirm data integrity.  
   - Compared model performance with metrics like RMSE and R² Score.  

---

## 📂 Project Structure  

📦 Netflix-Movies-Data-Cleaning

│-- 📄 README.md # Project documentation

│-- 📄 Netflix_Data_Analysis.ipynb # Jupyter Notebook with the code

---

## 🚀 Technologies Used  

- **Programming Language:** Python  
- **Libraries:**  
  - `pandas` for data manipulation  
  - `numpy` for numerical operations  
  - `matplotlib` for visualizations  
  - `scikit-learn` for machine learning models  
  - `category_encoders` for categorical encoding  
  - `GridSearchCV` for hyperparameter tuning  

---

## 📊 Key Results  

- Successfully reduced the missing values without unnecessary data loss.  
- Boxoffice values were imputed using machine learning, improving data completeness.  
- RMSE and R² scores indicated strong model performance, validating the imputation techniques.  

---

## 🔍 Key Learnings  

- Importance of **effective column naming** for readability and usability.  
- Exploring alternatives beyond simply dropping columns with high null values.  
- Using **domain-driven imputation** (e.g., inferring languages from country tags).  
- Significance of patience and determination in data preprocessing tasks.  

---

## 📈 Model Performance Summary  

| Model            | Training RMSE | Test RMSE | R² Score       |  
|------------------|--------------|-----------|----------------|  
| RandomForest     | 1,564,994     | 0.0       | 1.0            |  
| XGBoost (No Tuning) | 124,256       | N/A       | 0.99999         |  
| GradientBoosting | 399,702       | N/A       | 0.99996         |  

---

## 📸 Visualizations  

The following visualizations were used to validate the imputation effectiveness:

- **Before and After Imputation Comparisons**  
- **Distribution of Boxoffice Values Post-Imputation**  
- **Model Performance Metrics Analysis**  

---

## 📬 Contact

If you have any questions or feedback, feel free to reach out via:

LinkedIn: www.linkedin.com/in/keshvan-vijay-rathnam-408517160

---

## 🔖 Acknowledgments
Special thanks to **Physics Wallah** for providing the course and guidance in data science.

