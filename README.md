# Gold-Recovery-
🟡 Gold Recovery Prediction Project
This project focuses on predicting the efficiency of gold recovery in a mineral processing plant using industrial data. Accurate predictions help optimize extraction and reduce metal loss during production.

🎯 Objective
To build and evaluate machine learning models that predict:

Final gold recovery efficiency from flotation and hydrometallurgical processes

Model performance using Symmetric Mean Absolute Percentage Error (sMAPE)

🛠 Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)

Scikit-learn (Linear Regression, Decision Trees, Random Forest, Gradient Boosting)

sMAPE metric for evaluation

Jupyter Notebook

📂 Project Workflow
1. Data Preprocessing
Loaded training and test datasets

Calculated target recovery values using the provided formula

Verified that features in the test set are present in the training set

Filled missing values using forward fill method

2. Exploratory Data Analysis (EDA)
Analyzed feature distributions and correlation with recovery

Investigated outliers and inconsistencies in data

Visualized concentrations of gold, silver, and lead across processing stages

3. Feature Engineering
Removed irrelevant and low-variance features

Added calculated features like total recovery

Scaled data where needed

4. Model Training & Evaluation
Trained and compared several models using cross-validation:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Used custom sMAPE function to evaluate model performance on multiple targets

5. Final Testing
Selected best-performing model and validated it on test set

Achieved performance within business metric requirements

📈 Key Metric
Symmetric Mean Absolute Percentage Error (sMAPE):

Averages the absolute percentage error for both final and rougher recovery stages

Penalizes over- and under-prediction equally
