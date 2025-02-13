# Supervised-Learning-For-Identity-Theft-Detection-in-Application-Data

## Project Overview

### Introduction
Identity theft remains a major challenge in the financial sector, leading to significant financial losses, operational inefficiencies, and reputational risks. This project leverages supervised machine learning techniques to enhance fraud detection capabilities in application data, ensuring early identification of fraudulent applications.

### Objective
The primary goal of this project is to build a fraud detection model that accurately classifies applications as fraudulent or legitimate. By applying various machine learning techniques, we aim to improve fraud detection rates while minimizing false positives to optimize operational efficiency.

### Methodology
1. Data Acquisition & Preprocessing
   - The dataset consists of 1,000,000 synthetic application records, designed to retain the statistical properties of real-world data.
   - Data cleaning included handling missing values, correcting date formats, and addressing placeholders for missing identity details.

2. Feature Engineering & Selection
   - Additional variables were created to capture applicant behaviors and interactions, improving fraud detection accuracy.
   - Feature selection techniques, including filter-based methods and forward stepwise selection, were applied to retain the most predictive features.

3. Model Development & Evaluation
   - Various machine learning models were tested, including Logistic Regression, Decision Trees, Random Forest, LightGBM, CatBoost, XGBoost, and Neural Networks.
   - Performance metrics such as precision, recall, and Fraud Detection Rate (FDR) were used for evaluation.
   - he final model, CatBoost, was selected for its superior performance and robustness.

4. Financial Optimization
   - A cost-benefit analysis was conducted to determine the optimal fraud detection threshold.
   - A 2% score cutoff was identified to maximize fraud detection while minimizing false positives and financial losses.

### Key Findings
- Personal identity inconsistencies, such as repeated SSNs and addresses, were strong indicators of fraudulent applications.
- The CatBoost model demonstrated the highest validation performance while maintaining stability across different datasets.
- Implementing the recommended model and cutoff strategy can significantly reduce fraud-related risks and financial losses.

### Conclusion & Future Work

This project successfully implemented a machine learning-based fraud detection system for application data. Future enhancements could include:
- Automated hyperparameter tuning using GridSearchCV to improve model efficiency.
- Integration with real-time fraud detection systems to prevent identity theft at the application stage.
- Expanding feature engineering techniques to incorporate additional behavioral and network analysis.

By leveraging machine learning, businesses can enhance fraud prevention strategies, protect customer identities, and mitigate financial risks effectively.


P.S The foundational code for this project was provided by the professor, and my primary task involved refining the code and adapting it to achieve the desired outputs.

