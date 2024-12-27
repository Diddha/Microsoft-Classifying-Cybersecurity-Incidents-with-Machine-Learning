# Microsoft-Classifying-Cybersecurity-Incidents-with-Machine-Learning
🚨Microsoft: Classifying Cybersecurity Incidents with Machine Learning🔐 - Updated Description
Project Overview
The Classifying Cybersecurity Incidents🚨 initiative leverages machine learning to streamline the operations of Microsoft Security Operation Centers (SOCs). This project centers on developing a robust classification model to predict the triage grade of cybersecurity incidents accurately. By doing so, it empowers SOC analysts to prioritize critical issues, enhancing their ability to address threats efficiently.

The incident classification includes:

True Positive (TP): A validated threat.
Benign Positive (BP): A harmless alert.
False Positive (FP): An incorrectly flagged threat.
Key Features & Skills
This project provides hands-on experience with essential machine learning and cybersecurity techniques, including:

Data Preprocessing & Feature Engineering: Transforming raw data into actionable insights for effective model training.
Classification Techniques: Employing advanced algorithms like Random Forest and XGBoost for incident categorization.
Evaluation Metrics: Utilizing Macro-F1 Score, Precision, and Recall to gauge performance.
Cybersecurity Frameworks: Integrating insights from the MITRE ATT&CK framework for enhanced data understanding.
Imbalanced Data Solutions: Strategies such as SMOTE, adjusted class weights, and ensemble techniques to handle uneven data distributions.
Model Optimization: Fine-tuning hyperparameters for superior accuracy and reliability.
Business Use Cases
The solution drives innovation in various cybersecurity operations, including:

SOCs Efficiency: Automates incident triage, enabling rapid decision-making.
Incident Response Automation: Enhances speed and accuracy of response actions.
Threat Intelligence: Boosts the precision of identifying true and false positives using historical patterns.
Enterprise Security: Reduces false alarms, sharpens threat detection, and accelerates response time.
Project Approach
Data Exploration & Preprocessing

Initial Dataset Inspection: Review structure and distribution of the target variable.
EDA: Visualize trends, correlations, and anomalies, addressing class imbalance.
Model Development

Data Splitting: Use training and validation sets for balanced evaluations.
Baseline Models: Establish benchmarks using logistic regression and decision trees.
Advanced Models: Implement Random Forest and XGBoost for enhanced classification.
Cross-Validation: Apply k-fold cross-validation for robustness.
Model Evaluation

Focus Metrics: Optimize Macro-F1 Score, Precision, and Recall.
Hyperparameter Tuning: Employ Grid/Random Search for performance optimization.
Class Imbalance Handling: Incorporate techniques like SMOTE or class-weight adjustments.
Final Evaluation

Testing: Assess the final model using the test dataset.
Baseline Comparison: Confirm improvements over baseline performance.
Results
Model Performance: Accurate predictions for TP, BP, and FP classifications.
Feature Insights: Identification of critical factors influencing model predictions.
Comprehensive Documentation: Detailed project workflow, from data preprocessing to final evaluation.
Evaluation Metrics
Macro-F1 Score: Balances precision and recall across all classes for a holistic evaluation.
Precision: Ensures accuracy in identifying true positives among all positive predictions.
Recall: Guarantees critical threats are detected without omission.
Dataset Overview
The GUIDE dataset comprises over 1 million incidents annotated with triage grades (TP, BP, FP), providing real-world security scenarios for modeling.

Features:

Evidence: Individual items like IPs, emails, and user logs.
Alerts: Grouped evidence indicating potential threats.
Incidents: Comprehensive scenarios combining alerts into actionable security events.
Usage Instructions
Load the datasets (train.csv and test.csv).
Perform preprocessing and feature engineering.
Train and evaluate the model.
Validate model performance using key metrics.
Technologies Used
Languages: Python.
Libraries:
Data Processing: Pandas, NumPy.
Modeling: Scikit-Learn, XGBoost, LightGBM.
Visualization: Matplotlib, Seaborn.
Imbalance Handling: SMOTE.
