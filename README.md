# Data Mining 2 Project

## Authors
- Lorenzo Albani  
- Luigi Ascione  
- Tommaso Maitino  

📅 **Date**: July 4, 2025  

## Description
This project builds upon the work previously carried out in Data-Mining-1 on the analysis of an IMDb dataset containing information about movies, TV series, and other audiovisual content. Specifically, advanced techniques were employed for **outlier detection, imbalanced learning, classification, regression, and explainable AI (XAI)**, along with methods for **time series analysis**.

## Project Contents
The project is structured as follows:

### 1️⃣ **Data Understanding and Preparation**
- Semantic data analysis  
- Descriptive statistics and variable distribution  
- Data cleaning and transformation  
- Correlation analysis and feature selection  

### 2️⃣ **Outliers**
- Use of techniques such as: **HBOS(Histogram-based outlier), LOF(Density-based approach), CBLOF(Clustering-based approach), Extended Isolation Forest(Model-based approach), kNN distances (Distance-based approach)**  
- In-depth analysis of the **Extended Isolation Forest**
- Final handling of outliers

### 3️⃣ **Imbalanced Learning**
- Undersampling using: **Random Undersampling, Tomek Links, Edited Nearest Neighbors, Cluster Centroids**.  
- Oversampling using: **Random Oversampling, SMOTE, ADASYN**
- Combined Approach  
- Balancing at the Algorithm Level 

### 4️⃣ **Advanced Classification**
- **Logistic Regression**  
- **Support Vector Machines: Linear and Non-Linear SVM's**  
- **Neural Networks: MLPClassifier(scikit-learn), Deep MLP, MLP with Batch Normalization, Residual MLP**  
- **Ensemble Methods: Random Forest**
- **Gradient Boosting Machines: XGBoost**
- Final results

### 5️⃣ **Advanced Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**   
- Final results  

### 6️⃣ **Explainability**
- **SHAP**
- **LORE**

### 7️⃣ **Time-Series**
- Preparation
- **Motifs** discovery  
- **Discords** discovery
- Clustering: **K-Means, Hierarchical**, Conclusions
- Classification: **Instance-based models, Shapelets-based model**, Other methods, Final considerations  

## 📊 Main Results
- **Combined Approach** led to an improvement of 0.08 in the ROC AUC Score for the *has_award* variable.
- **XGBoost** achieved a very high accuracy of 0.94 for the *titleType* variable classification.  
- **Random Forest** performed significantly better than **XGBoost** in the **Advanced Regression** task.
- **SHAP** confirmed the hypotheses derived from the classifiers results regarding the misclassification of minority classes.
- Bi-weekly peaks were observed in the time-series.
- The best classifiers in time-series classification are the dictionary-based ones, in particular the model based on the **BORF transformation**.


## 🛠 Technologies Used
- **Language**: Python 🐍  
- **Main libraries**: 'Pandas', 'NumPy', 'matplotlib', 'seaborn' 'Scikit-learn', 'Pytorch', 'PyOD', 'imblearn', 'XGBoost', 'SHAP', 'LORE', 'tslearn', 'TSFresh, 'BORF', 'SAX'     
- **Notebook**: Jupyter  

## 📖 License
This project is released under the **MIT** license.  

You can see the full details in the `LICENSE` file.  

---
🔹 Feel free to use, modify, and contribute to the project! 🚀

---

Additionally, the complete report is available in the file `Imbd_report.pdf`.
