Loan Status Prediction - Data Analysis and Machine Learning

This project demonstrates how to predict loan approval status using a dataset containing various applicant features, such as credit history, income, and loan amount. The analysis includes cleaning the data, exploring important features, and applying machine learning models to predict loan status.

Objective

The goal of this project is to predict whether a loan application will be approved or denied based on several applicant features like credit score, income, and employment status. The project demonstrates data analysis, preprocessing, and applying machine learning models for prediction.

Data Preprocessing

The dataset was preprocessed by:
- Handling missing values and imputing or removing them as necessary.
- Converting categorical variables to numerical values.
- Normalizing data and scaling numerical features to improve model performance.

Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) was performed to understand the dataset and extract useful insights:
- Analyzed the distribution of loan status and visualized trends.
- Checked for correlations between features like credit score, income, and loan approval.
- Visualized key relationships to uncover patterns that could influence loan approval.

Models Used

The following models were used to predict loan approval:
- Gaussian Naive Bayes: For continuous features assumed to follow a normal distribution.
- Multinomial Naive Bayes: Suitable for features representing counts or categories.
- Bernoulli Naive Bayes: Used for binary features.

Model Performance

The accuracy of the models was evaluated using the test set:
- Gaussian Naive Bayes: 0.7945
- Multinomial Naive Bayes: 0.8460
- Bernoulli Naive Bayes: 0.8470

Bernoulli Naive Bayes performed slightly better than the others.

Key Insights

- Credit Score: Higher credit scores increased the chances of loan approval.
- Income: Applicants with higher income were more likely to be approved.
