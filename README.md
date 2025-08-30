# Honey-Wildflower-Price-Prediction

## 📌 Project Overview
This project analyzes the **Honey Wildflower dataset** to explore the factors that influence the **market price of honey**.  
The goal is to build a **predictive model** that can estimate honey prices based on its physical and chemical attributes.  

## 🛠️ Tools & Technologies
- **Programming Language:** R  
- **Libraries & Packages:** tidyverse, caret, psych, skimr  
- **Techniques Used:**  
  - Data preprocessing (scaling, partitioning, feature selection)  
  - Exploratory visualization (pair plots, correlation analysis)  
  - Linear regression with 10-fold cross-validation  
  - Model performance evaluation (RMSE, R², MAE)  

### 1. Data Preprocessing
- Imported dataset (`Honey.Wildflower.csv`) and explored its structure.  
- Removed non-informative features (e.g., `Pollen_analysis`) and highly correlated features (e.g., `Purity`).  
- Standardized numerical attributes to ensure comparability.  
- Partitioned the dataset into **training (80%)** and **testing (20%)** sets.  

### 2. Exploratory Data Analysis (EDA)
- Used pair plots to visualize attribute relationships.  
- Identified correlations between honey attributes and price.  
- Highlighted which features were most predictive.  

### 3. Model Training
- Built a **linear regression model** using repeated **10-fold cross-validation**.  
- Optimized model performance and reduced risk of overfitting.  

### 4. Model Evaluation
- Evaluated the model on the **test dataset** using RMSE and R².  
- Assessed prediction accuracy compared to baseline variation in honey price.  

---

##  Results & Insights
- The linear regression model successfully identified key factors that influence honey price.  
- **Feature reduction** improved performance by eliminating redundancy.  
- Achieved strong predictive accuracy, showing that honey pricing can be **effectively modeled using regression techniques**.  
- Demonstrates how **machine learning can support agricultural pricing and decision-making**.  

---
