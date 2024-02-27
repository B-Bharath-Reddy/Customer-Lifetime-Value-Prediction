# Customer Lifetime Value Prediction Project

## Overview
This project focuses on predicting customer spending behavior and purchase probabilities to calculate the Customer Lifetime Value (CLTV). By leveraging advanced machine learning techniques, including XGBoostRegressor and XGBoostClassifier, the goal is to provide actionable insights for strategic decision-making and customer relationship management.

By analyzing historical data and leveraging machine learning models, we were able to address key business questions such as:

#### Identifying Customers with High Spend Probability: 
The developed models allow us to pinpoint customers with the highest likelihood of spending in the upcoming 90 days. This information can be valuable for targeted marketing efforts and personalized customer engagement strategies.

#### Identifying Unlikely Repeat Buyers:
By analyzing customer purchase patterns, we can identify those who have recently made purchases but are unlikely to buy again in the near future. This insight can help optimize resource allocation and retention strategies.

#### Identifying Missed Opportunities:
The models also help highlight instances where predicted purchases did not materialize. By understanding why certain predictions did not align with actual customer behavior, businesses can refine their predictive models and improve decision-making processes.

## Key Features
- Utilizes XGBoostRegressor to forecast the next 90 days' spend.
- Employs XGBoostClassifier to predict the probability of purchases within the next 90 days.
- Combines temporal in and out data for training and evaluation.
- Applies feature engineering techniques to create recency, frequency, and monetary features using reference data and temporal in and out data.
- Develops individual and dependent variables based on temporal in and out data.
- Provides insights into customer spending patterns and purchase probabilities without splitting the data.
- Identifies significant features contributing to model predictions for strategic decision-making.
- Incorporates model evaluation and feature importance analysis for real-world applicability.
- Splits the combined data into train and test sets to evaluate model performance for future usage.

## Conclusion
In this project, I employed XGBoostRegressor to forecast the next 90 days' spend and XGBoostClassifier to predict the probability of purchases within the next 90 days. To calculate the Customer Lifetime Value (CLTV), I merged temporal in and out data, which encompass historical features and target variables, respectively. By training and evaluating the model on this combined dataset, I aimed to address specific business inquiries.

By leveraging the models trained on the combined dataset, I provided insights into customer spending patterns and purchase probabilities without splitting the data. This approach facilitated the assessment of high spend probabilities, identification of recent purchasers unlikely to buy again, and detection of missed opportunities where predicted purchases did not materialize.

Furthermore, I split the combined data into training and evaluation sets to ensure model robustness and performance assessment. Through this process, I identified significant features contributing to model predictions, which can be crucial for model deployment and future prediction tasks.

In summary, the project utilized advanced modeling techniques and a unified dataset to derive actionable insights, enabling strategic decision-making and enhancing customer relationship management strategies. The incorporation of model evaluation and feature importance analysis ensures the applicability and reliability of the developed models in real-world scenarios.



