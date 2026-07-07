 Wine Quality Prediction using Machine Learning

Project Overview

This project focuses on predicting wine quality using Machine Learning classification algorithms based on physicochemical properties such as acidity, sugar content, density, alcohol percentage, pH level, and more.

The objective of this project is to compare multiple classification models and determine which model performs best for predicting wine quality.



Objective

To train and compare different machine learning classification models for predicting whether a wine is **Good** or **Bad** based on its chemical properties.


Tech Stack

* Python
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* Jupyter Notebook


Dataset

Dataset Used:

Wine Quality Dataset (UCI Machine Learning Repository)

Features include:

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol
* Quality


Project Workflow

1️⃣ Data Loading & Inspection

* Loaded the dataset using pandas
* Checked dataset shape, columns, and data types
* Verified missing values

2️⃣ Exploratory Data Analysis (EDA)

Performed:

* Distribution plots for all features
* Correlation heatmap
* Wine quality class distribution analysis

Key Insights:

* Quality scores 5 and 6 were dominant
* Some quality classes were underrepresented
* Alcohol showed positive correlation with quality


3️⃣ Class Imbalance Discussion

The dataset contained imbalanced quality classes.

To improve classification performance:

Quality scores were converted into binary classes:

 Good Wine → Quality ≥ 7
 Bad Wine → Quality < 7

This simplified the prediction problem and improved model stability.


Machine Learning Models Used

✅ Random Forest Classifier

* Ensemble-based learning model
* Handles nonlinear relationships effectively
* Provides feature importance analysis

✅ SGD Classifier

* Fast and efficient linear classifier
* Suitable for large datasets

✅ Support Vector Classifier (SVC)

* Powerful classification algorithm
* Effective in high-dimensional spaces

📈 Model Evaluation

Each model was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

 📌 Feature Importance

Random Forest feature importance analysis was performed to identify the most influential features affecting wine quality.

Important features included:

* Alcohol
* Sulphates
* Volatile Acidity

📋 Model Comparison

| Model                     | Performance           |
| ------------------------- | --------------------- |
| Random Forest             | Best Overall Accuracy |
| SGD Classifier            | Moderate Performance  |
| Support Vector Classifier | Good Performance      |



🏆 Conclusion

After comparing all models:

* Random Forest Classifier achieved the best performance.
* It provided higher accuracy and better robustness.
* Feature importance made the model more interpretable.

Therefore, Random Forest is the most suitable model for deployment in this wine quality prediction task.

