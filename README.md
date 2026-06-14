# Tanmaya_ML_Internship
Business Reflection Questions & Answers
Q1) Which factors appear to influence subscription renewal the most? 
Answer: By analyzing the feature importances from the model, factors like WatchHoursPerWeek , AdClicks , and specific SubscriptionType typically show a high influence. Highly engaged users (more watch hours) and users interacting with the platform tend to renew more often.

2.  Why is subscription renewal a classification problem?
Answer: Subscription renewal is a classification problem because the target variable ("SubscriptionRenewed") has discrete, categorical outcomes—specifically, it is a binary outcome. We are trying to classify the user into one of these two distinct categories.

3. Why is monthly spending a regression problem?
Answer: Monthly spending is a regression problem because the target variable ("MonthlySpend") is a continuous numerical value.Instead of predicting a category, the model predicts an actual quantity/amount (e.g., $15.99, $22.50).

4. Which algorithm performed better for renewal prediction? Answer: Depending on the exact distributions in the dataset, either KNN  or Decision Tree will perform better. The Python script prints a direct comparison at the end of Part E (Q18) to answer this accurately based on the evaluation metrics.

5. How could the platform use these predictions to improve customer retention?
Answer:  Targeted Interventions: The platform can use the Classification model to identify users who are predicted not to renew (high churn risk). They can then send targeted promotional offers, discounts, or personalized content recommendations to re-engage them before their subscription ends. Revenue Forecasting: By using the Regression model, Netflix can predict future monthly revenue based on changing user behavior (like increased device usage or watch hours) and adjust their marketing budget and strategy accordingly.
