# Loan Approval and Rejection Prediction
This project focuses on analyzing and predicting loan approval and rejection based on a dataset of loan applications. The dataset contains various features such as income, loan amount, education level, credit score, and more. By performing exploratory data analysis (EDA) and utilizing logistic regression, the project aims to gain insights into the factors influencing loan approval decisions and develop a predictive model.

## [Dataset](https://github.com/Bytecode-Magnum/Loan_Approva_Rejection_EDA_Prediction/blob/main/loan_approval_prediction_dataset.csv)
The dataset consists of the following columns:

* loan_id: A unique identifier for each loan application.
* no_of_dependents: Number of dependents of the applicant.
* education: Education level of the applicant (Graduate or Not Graduate).
* self_employed: Whether the applicant is self-employed (Yes or No).
* income_annum: Annual income of the applicant.
* loan_amount: Amount of loan requested.
* loan_term: Loan term in months.
* cibil_score: CIBIL credit score of the applicant.
* residential_assets_value: Value of residential assets owned by the applicant.
* commercial_assets_value: Value of commercial assets owned by the applicant.
* luxury_assets_value: Value of luxury assets owned by the applicant.
* bank_asset_value: Value of assets held by the applicant in banks.
* loan_status: Loan approval status (Approved or Rejected).

## Exploratory Data Analysis (EDA)
The EDA process involves understanding the dataset, identifying missing values, exploring feature distributions, and analyzing relationships between features and loan approval status. Some of the EDA tasks performed include:

* Handling missing values and data preprocessing.
* Descriptive statistics to understand the range and distribution of numerical features.
* Visualization of categorical features using count plots to observe class imbalances.
* Pair plots and correlation analysis to identify potential relationships between features.
* Plotting histograms and kernel density estimates to analyze feature distributions.

## Data Preprocessing
[NoteBook](https://github.com/Bytecode-Magnum/Loan_Approva_Rejection_EDA_Prediction/blob/main/Loan_approval_prediction.ipynb)

Data preprocessing steps were taken to prepare the dataset for machine learning:

* Standardizing numerical features to have a mean of 0 and a standard deviation of 1.
* Applying label encoding to convert categorical variables into numerical format for the Logistic regression model.

## Logistic regression Model
 a classification algorithm, was employed to predict loan approval or rejection based on the dataset. The model was trained on the preprocessed data, taking into account the standardized and label-encoded features. The model's performance was evaluated using precision, recall, F1-score, and accuracy metrics.

## Visualizations
Several plots were generated to visually analyze and interpret the results:

* Histograms and kernel density plots to compare distributions of features for approved and rejected loans.
* Count plots to visualize the distribution of categorical variables among approved and rejected loans.
* Pair histograms to explore relationships between pairs of numerical features for different loan statuses.
## Conclusion
This project demonstrates the process of analyzing a loan approval dataset, performing exploratory data analysis, preprocessing the data for modeling, and using logistic regression to predict loan approval or rejection. By gaining insights into the factors influencing loan decisions and building a predictive model, this project contributes to understanding the dynamics of loan applications and provides a foundation for further improvement and refinement of the predictive model.
