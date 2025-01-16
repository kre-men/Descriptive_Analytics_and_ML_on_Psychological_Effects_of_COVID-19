# Descriptive_Analytics_and_ML_on_Psychological_Effects_of_COVID-19
A machine learning project analyzing the psychological effects of COVID-19 through descriptive analytics, classification, regression, and clustering, using demographic and behavioral data from 1,175 participants.


This project explores the psychological effects of COVID-19 through advanced data analysis and machine learning techniques. Using a dataset of 1,175 responses, it investigates participants' demographics, habits, and preferences during the pandemic.

Key Objectives and Methodology
Descriptive Analytics

Analyzed age, gender, and occupation distributions, as well as preferences for remote work and daily habits.
Found strong correlations between relaxation, personal time, and overall well-being.
Classification of Gender

Models used: Random Forest, SVM, and Naive Bayes.
Random Forest achieved the highest accuracy (95.3%), followed by SVM (89.7%) and Naive Bayes (83.8%).
Addressed data imbalance issues and improved classification performance by removing noisy categories.
Regression Analysis

Applied polynomial regression to predict the "self-time" attribute.
A degree-1 polynomial model offered better generalization, avoiding overfitting seen in higher-degree models.
Clustering

Performed K-Mode clustering to identify distinct behavioral patterns.
Identified four clusters with weak separations, highlighting potential feature limitations.
Used PCA for visualization and interpretation of clustering results.
Notable Data Preparation Steps
Preprocessed missing values, corrected errors, and encoded categorical features.
Scaled numerical features using MinMaxScaler for consistency.
Analyzed correlations and visualized patterns through heatmaps and scatterplots.
Key Findings
Younger age groups (19–25) dominated the dataset, influencing trends.
Preferences for remote work and study were mixed, with a strong inclination for physical presence.
Strong correlations were observed between well-being indicators such as relaxation, family connections, and personal time.

This project demonstrates how data-driven insights and machine learning can provide a deeper understanding of human behavior and preferences during disruptive events like the COVID-19 pandemic.
