# Overview of the Analysis
* In the recent analysis, we leveraged machine learning models to predict credit risk based on historical lending data. Our primary objective was to:

* Purpose of the Analysis: Determine if a borrower would be a healthy loan (0) or high-risk loan (1) candidate. Identifying high-risk loan candidates earlier can potentially save lending institutions from significant financial losses.

* Financial Information: The data encompassed a wide variety of financial indicators and personal attributes of borrowers. Our target variable was the “loan_status”, which indicated whether a loan was healthy or high-risk.

* Variables: The primary variable of interest was "loan_status". As observed, the data was imbalanced with a higher count of healthy loans compared to high-risk loans.

* Machine Learning Process: Our process began with data preprocessing where we separated features from the target variable. We then split the data into training and test sets. From here, we applied logistic regression on both the original and oversampled data to evaluate performance.

* Methods Used: We employed the LogisticRegression model from SKLearn. To address the imbalance in the data, we also utilized the RandomOverSampler method from the imbalanced-learn library.

# Results
* Machine Learning Model 1 (Logistic Regression with Original Data):
* Balanced Accuracy Score: Approx. 0.99, indicating a high ability to predict both healthy and high-risk loans.
* Precision: For healthy loans, the precision was 1.00, and for high-risk loans, it was 0.85.
* Recall: For healthy loans, the recall was 0.99, and for high-risk loans, it was 0.91.
* Machine Learning Model 2 (Logistic Regression with Resampled Data):
* Balanced Accuracy Score: Approx. 0.9937, showcasing an impressive accuracy in prediction.
* Precision: The model achieved a precision of 1.00 for healthy loans and 0.84 for high-risk loans.
* Recall: The model successfully predicted 0.99 of healthy loans and a remarkable 0.99 of high-risk loans.

# Summary
* Upon reviewing the results from both models:

* Performance: Both models displayed exceptional performance. However, Model 2 (resampled data) had a slightly higher balanced accuracy score and exhibited outstanding recall for high-risk loans.

* Recommendation: We recommend the second model (Logistic Regression with Resampled Data) for predicting high-risk loans. The primary reason is the impressive recall for high-risk loans, which is essential for lending institutions aiming to minimize potential defaults.

* Contextual Importance: While precision is crucial, in the context of predicting credit risk, recall takes precedence, especially for high-risk loans. By maximizing recall, we reduce the likelihood of overlooking potential high-risk candidates, thereby safeguarding the financial institution.

* In conclusion, while both models perform admirably, given the importance of recall for high-risk loans, the resampled data model stands out as the optimal choice.