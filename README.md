# credit-risk-classification
Credit Risk Analysis using Machine Learning
Project Overview
In the dynamic world of finance, identifying potential credit risks is paramount. This project revolves around leveraging machine learning to predict credit risk. We utilized historical lending data, processed it, and applied a logistic regression model to determine if a borrower would be a healthy or high-risk loan candidate.

Key Objectives
Data Preprocessing: Streamlining and setting up the data for efficient machine learning.
Predictive Analysis: Understand the ability of borrowers to repay their loans.
Modeling with Imbalanced Classes: As credit risk is typically an imbalanced classification problem, address the issue with effective modeling.
Performance Evaluation: Assess how well our models predict high-risk vs. healthy loans.
Tools and Technologies
Python: For scripting and data manipulation.
Pandas: Extensively used for data manipulation and analysis.
Sklearn: For machine learning and predictive analytics.
Imbalanced-Learn: To address the imbalanced nature of financial data.
Process
Data Retrieval: Extracted lending data and reviewed its structure.
Feature Selection: Segregated target labels and feature variables.
Data Splitting: Divided data into training and test sets.
Model Application: Applied logistic regression on original data and resampled data to evaluate performance.
Performance Evaluation: Utilized metrics like Balanced Accuracy Score, Precision, Recall, and F1-Score to determine the efficiency of our models.
Key Findings
The logistic regression model, when applied to oversampled data, exhibited an impressive recall for high-risk loans - a key metric for lending institutions to reduce potential defaults.
Resampled data using the RandomOverSampler from the imbalanced-learn library proved beneficial in enhancing the performance of the model.
Achieved a balanced accuracy score of approximately 0.9937 with the resampled data, showcasing an outstanding predictive capability.
Conclusion & Recommendations
Given the critical nature of identifying high-risk loans in the lending business, our machine learning model offers a robust solution. We recommend the logistic regression model trained on resampled data due to its high recall in predicting high-risk loans. This model can significantly aid financial institutions in their risk management endeavors.

Future Work
Explore other resampling techniques and ensemble methods to further improve model performance.
Incorporate more features and potentially more data for a comprehensive analysis.
Explore the potential of deep learning in predicting credit risk.
Acknowledgements
We express our gratitude to all contributors and developers of the Python, Pandas, Sklearn, and Imbalanced-Learn libraries for their incredible tools that made this analysis possible.