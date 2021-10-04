
# [Project 1: Predicting Sales Using Webtraffic](https://github.com/JaclynGlosson/Predicting_Online_Sales)
For my final project in STAT 642 (Data Mining), I used webtraffic data to predict purchasing behavior for an online retailer. The data included redundant variables, irrelevant variables, correlated variables, as well as large amounts of variation and noise. Decision Tree and Naive Bayes methods were compared. 

The final recommended Decision Tree model, which corrected for class imbalance, correctly predicted who would purchase from the company at a rate of approximately 80%, as well as who would not purchase from the company at a rate of approximately 86%.

A comprehensive, business-oriented report is availible [here.](https://github.com/JaclynGlosson/Predicting_Online_Sales/blob/main/Decision%20Tree%20and%20Naive%20Bayes%20Project.pdf)

# [Project 2: Chronic Kidney Disease Screener](https://github.com/JaclynGlosson/Predicting_CKD)
The objective of this case study was to create a screening tool which allows identification of those individuals who are at a higher risk of suffering from CKD. The data used in this analysis was gathered by the National Center for Health Statistics of the Centers for Disease Control and Prevention. The data contains information on 33 different variables from 8,819 adults and was collected between 1999 and 2002.

The dataset contained 1,864 rows of missing data that was imputed using Multivariate Imputation by Chained Equation, or MICE, in R studio. Variables were chosen for the logistic regression model based on (a) prior medical research, (b) stepAIC, and (c) cross validation. The predictive model had a median is .015, meaning half the patients have less than a 1.5% chance of getting CKD. The expected profit for the model was $292,200.

A screening tool was created using linear regression and the variables identified from the logistic regression model. This screening tool identified who should be recommended to be screened for CKD. The screening tool consisted of 8 questions and approximated 95% of the accuracy of the logistic regression model, while maintaining interpretability and ease of use for patients.

A comprehensive report is availible [here.](https://github.com/JaclynGlosson/Predicting_CKD/blob/main/CKD%20Case%20Study.pdf)
