## Wheat Variety Classification

### Project Overview

This project aims to classify **three different varieties of wheat** (Kama, Rosa, and Canadian) based on seven geometric properties of the wheat kernels. By leveraging features such as area, perimeter, compactness, length, width, asymmetry coefficient, and groove length, the goal is to develop a machine learning model that can accurately distinguish between the wheat varieties.

-----

### Technical Highlights

  * **Dataset**: [Kaggle - Wheat Variety Classification](https://www.kaggle.com/datasets/sudhanshu2198/wheat-variety-classification)
  * **Size**: 210 entries, 8 columns
  * **Key Features**:
      * area, perimeter, compactness, length, width, asymmetry coefficient, groove length.
  * **Approach**:
      * Data Cleaning: No missing values or duplicates were found.
      * Exploratory Data Analysis: Histograms, Boxplots, and Heatmaps were used for visualization to understand data distributions and correlations.
      * Label Encoding: Applied to all columns, including numerical ones and the target 'category' (which is already numerical but gets re-encoded).
      * Multi-class Classification: The target variable 'category' has three distinct values (1, 2, 3), representing the three wheat varieties.
      * Models Used:
          * Logistic Regression, Ridge Classifier, SVC, Random Forest, XGBoost, AdaBoost, Gradient Boosting, Bagging, Decision Tree.
  * **Best Accuracy**:
      * 92.9% with Gradient Boosting Classifier.
      * 90.5% with Bagging Classifier and SVC.
      * 88.1% with Logistic Regression, Ridge Classifier, XGBoost Classifier, and Random Forest Classifier.

-----

### Purpose and Applications

  * Automate the **sorting and classification of wheat varieties** for quality control in the agricultural industry.
  * Aid farmers and food producers in distinguishing between different wheat types, which have varying end-use properties.
  * Improve efficiency in grain processing and supply chain management.
  * Support research in agricultural science and machine vision for crop analysis.

-----

### Installation

Clone the repository:

```bash
git clone https://github.com/BhaveshBhakta/Wheat-Variety-Classification-Using-ML.git
cd Wheat-Variety-Classification-Using-ML
```

Install the necessary libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost
```

-----

### Collaboration

We welcome contributions to improve the project. You can help by:

  * Performing comprehensive hyperparameter tuning and cross-validation for all models to achieve optimal performance.
  * Exploring more advanced feature engineering techniques, such as creating new features from the existing geometric properties.
  * Investigating the impact of different scaling methods or outlier handling strategies.
  * Adding explainability (e.g., SHAP or LIME) to understand which geometric properties are most discriminatory between the wheat varieties.
