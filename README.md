# Cross-Sell Insurance Prediction

## Introduction
Welcome to the Cross-Sell Insurance Prediction project! In this project, we aim to assist an insurance company in predicting whether customers who have purchased health insurance in the past year would be interested in buying vehicle insurance as well. By leveraging machine learning techniques, we strive to build a predictive model that can identify potential cross-selling opportunities.

## Dataset Overview
The dataset comprises the following properties:

- **id**: Unique identifier of the buyer.
- **Gender**: Gender of the buyer.
- **Age**: Age of the buyer.
- **Driving_License**: 1 if the user has a driving license, 0 otherwise.
- **Region_Code**: Unique code of the buyer's region.
- **Previously_Insured**: 1 if the user already has vehicle insurance, 0 otherwise.
- **Vehicle_Age**: Age of the vehicle.
- **Vehicle_Damage**: 1 if the user has damaged the vehicle in the past, 0 otherwise.
- **Annual_Premium**: The amount the user must pay as a premium during the year.
- **Policy_Sales_Channel**: Anonymized code of the channel used for the proposal (e.g., email, phone, in-person, etc.).
- **Vintage**: Number of days since the user has been a customer of the company.
- **Response**: 1 if the buyer responded positively to the sales proposal, 0 otherwise.

## Objective
Our goal is to predict the value of the `Response` variable, indicating whether a customer is likely to respond positively to the vehicle insurance sales proposal.

## Handling Class Imbalance
It's important to note the potential issue of class imbalance in the dataset. To address this, we can consider the following strategies:
- Penalizing the most frequent class using `class_weight`.
- Utilizing oversampling or undersampling techniques.

## Conclusion
By leveraging machine learning algorithms and addressing class imbalances, we aim to develop an accurate predictive model to identify cross-selling opportunities for vehicle insurance. Stay tuned for updates and results!
