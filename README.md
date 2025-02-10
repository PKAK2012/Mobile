# Mobile
Overview
This project aims to predict the price of mobile phones using machine learning regression models. The dataset contains various features such as brand, model, RAM, storage, battery capacity, and other attributes that influence the price of a mobile phone.

Dataset Description
Age - Age of the buyer
Gender - Gender of the buyer (Male/Female)
City - Location where the purchase was made
Income Level - Income category of the buyer
Brand - Mobile brand (iPhone, Samsung, Oppo, etc.)
Model - Specific model of the phone
Payment Mode - Mode of payment (Credit Card, UPI, EMI, etc.)
Purchase Platform - Online or Offline purchase
Screen Time (hrs) - Average screen usage per day
Data Consumption (GB) - Monthly data usage
Preferred App - Most used app by the buyer
Rating - User rating for the phone
Purchase Reason - Reason for buying the phone (Performance, Price, Brand, etc.)
Storage (GB) - Internal storage capacity
RAM (GB) - RAM size of the phone
Battery (mAh) - Battery capacity
Dual SIM - Whether the phone supports dual SIM (Yes/No)
Purchase Month - Month of purchase
Price (INR) - Price of the mobile phone (Target Variable)

Machine Learning Approach
The dataset contains labeled data, meaning we have both input features (e.g., brand, RAM, storage, battery, purchase reason, etc.) and output labels (price). Since we are trying to predict the price, this makes it a supervised learning problem.
The target variable Price (INR) is continuous (numerical), which makes regression the right approach. Regression models are used to predict numerical outcomes based on input features.

Conclusion
This dataset is well-suited for supervised learning with regression, with Price (INR) as the target variable. Various machine learning algorithms, such as linear regression, decision trees, and random forests, can be applied to predict mobile phone prices based on the given attributes.

