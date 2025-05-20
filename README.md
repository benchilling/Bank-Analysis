# Bank-Analysis
Bank Marketing Campaign Analysis
Project Overview
This project analyzes a dataset from a Portuguese banking institution's marketing campaigns, comparing the performance of multiple machine learning classifiers to predict term deposit subscriptions. The analysis aims to improve campaign efficiency by identifying high-potential customers and optimizing resource allocation.
Dataset
The dataset contains records from 17 marketing campaigns conducted between May 2008 and November 2010, with 41,188 client contacts. Features include client demographics, campaign information, and socioeconomic context variables.
Key Findings
Client Segmentation Insights

Demographics Matter: Students and retired individuals have significantly higher subscription rates (25-30%) compared to blue-collar workers (6-7%)
Seasonal Patterns: Campaigns in March, December, September, and October showed subscription rates 4-5 times higher than other months
Economic Sensitivity: Customer responses are strongly influenced by economic indicators, particularly employment variation rate and Euribor rates

Model Performance
After comparing Logistic Regression, K-Nearest Neighbors, Decision Tree, and Support Vector Machine classifiers:

Best Overall Model: Logistic Regression provides the optimal balance of performance (highest ROC AUC at 0.8034) and computational efficiency (0.14s training time).
Business Implications

Our analysis suggests the bank could:
Reduce Contact Volume: Target only high-probability clients, potentially reducing contacts by 70-80% while maintaining 80-90% of successful subscriptions
Optimize Timing: Schedule major campaigns during high-yield months
Segment Approach: Develop specialized messaging for high-potential demographic segments
Economic Monitoring: Adjust campaign intensity based on economic indicators

Recommendations

Implement Predictive Scoring: Deploy the Logistic Regression model to score and rank potential clients before campaigns
Strategic Timing: Schedule major campaigns during March, December, September, and October
Targeted Demographics: Focus on students and retired individuals with tailored messaging
Pilot Testing: Validate model performance with a small-scale test campaign
Data Enhancement: Collect additional client information to further improve prediction accuracy
