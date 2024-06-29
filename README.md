Objective:
The goal of this project is to predict fraudulent transactions from a given dataset. Given the imbalanced nature of the data, standard metrics for evaluating classification algorithms, such as accuracy, are insufficient. The focus is on Sensitivity (true positive rate) and Specificity (true negative rate) to find an optimal trade-off, prioritizing high sensitivity to ensure fraudulent transactions are detected with high probability.

Data Exploration:

Libraries Used: NumPy, Pandas, Matplotlib, Seaborn, and warnings for ignoring warnings.
Dataset: The dataset contains 284,807 transactions with 31 features. There are no null values.
Fraud vs. Genuine Cases: The dataset is highly imbalanced with a small number of fraud cases.
Descriptive Statistics & EDA: Descriptive statistics and exploratory data analysis were performed, including histograms and scatter plots to visualize the distribution of fraud and genuine transactions over time and amount.
Correlation Analysis: A heatmap was used to visualize the correlation between features.

Model Building:

Data Preparation: The data was split into training and testing sets (70-30 split).
Model 1: Random Forest Classifier
Achieved high accuracy in predicting fraudulent transactions.
Model 2: Logistic Regression
Also demonstrated high accuracy.
Model 3: Decision Tree Regressor
Similarly, performed with high accuracy.
Conclusion:
All models achieved high accuracy, with a focus on optimizing sensitivity to effectively detect fraudulent transactions.
