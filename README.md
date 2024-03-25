# Online-Shopper-Behavior-Analysis-and-Prediction-using-PySpark
**Project Overview**

**Objective:** Explore and analyze the "Online Shoppers Intention" dataset using PySpark to understand online shopper behavior and optimize e-commerce operations.

**Dataset Description:** "Online Shoppers Intention" dataset from Kaggle comprising 12,331 rows and 18 columns.

**Scope of Analysis:**
 1.Exploratory Data Analysis (EDA)
 2.Visualization
 3.Insight Generation
 4.Actionable Recommendations
**Prediction, Inference, and Other Goals**
**Project Aim:** Develop a predictive model to determine the likelihood of a session resulting in revenue using binary classification.
**Model Selection:** Logistic Regression, Decision Trees, Random Forests, and Gradient-Boosting Machines.
**Inference Objectives:** Analyze model performance metrics and feature importance.
**Further Goals:** Provide actionable insights, identify key user behaviors, and develop a sustainable model.

**Data Exploration**
Correlation Heatmap Analysis
Scatter plot: Bounce Rate vs Exit Rate
Visitor Types breakdown
Bar Chart: Sessions by Month
Box Plot: Exit Rate Trends by Month by Revenue

**Feature Engineering**
Preprocessing steps including boolean to integer conversion, string indexing, vector assembling, and standard scaling.

**Prepared Dataset for Modeling**
DataFrame ready for predictive modeling with standardized features and target variable.

**Results**
Evaluation of Logistic Regression, Gradient-Boosted Trees, and Random Forest models.
Metrics include Accuracy, AUC, ROC Curve Analysis, Recall, F1 Score, and Precision.
Summary of model performances and identified challenges.

**Problem Encountered**
Addressing imbalanced class distribution, deciding on cluster count in K-means, identifying key features for PCA, and training models with skewed data.

**Summary of Achievements**
Identification of influential features for clustering and revenue conversion.
Gradient-Boosted Trees model outperforms others in AUC and recall.
Random Forest demonstrates a balanced F1 score.
Logistic Regression maintains competitive performance despite lower recall.
