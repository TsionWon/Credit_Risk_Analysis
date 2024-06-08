<h1>Credit risk analystis for Bati-Bank</h1>

<h2>Project Overview</h2>
<p>This project encompasses a comprehensive analysis of credit risk, including data understanding, exploratory data analysis, feature engineering, and model building. The following tasks were completed:

1. Task 1 - Understanding Credit Risk
2. Task 2 - Exploratory Data Analysis (EDA)
3. Task 3 - Feature Engineering
4. Task 3.1 - Default Estimator and WoE Binning
5. Task 4 - model building</p>

<h2>Task 1 - Understanding Credit Risk</h2>

<p>The project began with an in-depth understanding of credit risk, including the types of credit risk, factors strating from the terminology. </p>

<h2>Task 2 - Exploratory Data Analysis (EDA)</h2>

Objective: Analyze and understand the structure and key characteristics of the dataset.

Steps and Findings:

1. Overview of the Data:

Inspected the number of rows, columns, and data types.
Dataset contains n rows and m columns.
2. Summary Statistics:

Calculated mean, median, standard deviation, min, and max for numerical features.
3. Distribution of Numerical Features:

Visualized the distribution of numerical features using histograms.
Identified skewness and potential outliers.
4. Distribution of Categorical Features:

Visualized the distribution of numerical features using bar plots.
Observed the frequency and variability of categories.
5. Correlation Analysis:

Generated a correlation matrix.
Identified strong and weak relationships between numerical features.
6. Identifying Missing Values:

Checked for missing values.
Used appropriate imputation strategies to handle missing data.
7. Outlier Detection:
Used box plots to identify and analyze outliers.

<h2>Task 3 - Feature Engineering</h2>
Objective: Create new features that can improve the model's performance.
Steps and Findings:
1. Feature Extraction:
Extracted relevant features from existing ones.Total Transaction Amount, Average Transaction Amount, Transaction Count, Standard Deviation of Transaction Amounts were calculated for each customer.
2. Extract Features:
Transaction Hour, Day, Month, and Year were extracted from the transaction timestamp.
3. Feature Transformation:Encode Categorical Variables:
Transformed categorical features using one-hot encoding and label encoding.
4. Handle Missing Values:
Imputed missing values using mean and median imputation.
5. Normalize/Standardize Numerical Features:
Normalized numerical features using Min-Max Scaler and Standard Scaler.

<h2>Task 3.1 - Default Estimator and WoE Binning</h2>
Objective: 

Steps and Findings:
1. Default Estimator :
Used the default estimator to calculate the WoE (Weight of Evidence) for each feature.
2. WoE Binning :
Conducted WoE binning for categorical variables, transforming them into numerical values that hold significant predictive power.

<h2>Task 4 - Modelling</h2>
Objective: Train and evaluate machine learning models to predict Credit Risk.

Steps and Findings:
1. Model Selection :
Selected 5 models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and Support.
2. Model Training :
Trained each model using the preprocessed dataset.
3. Model Evaluation :
Evaluated each model using metrics: Accuracy, Precision, Recall, F1-score, AUC-
ROC.
4. Hyperparameter Tuning :
Performed hyperparameter tuning using GridSearchCV for each model.
5. Model Selection :
Selected the best-performing model based on the evaluation metrics.
Random Forest was chosen as the best model with an AUC-ROC of 0.999977.


