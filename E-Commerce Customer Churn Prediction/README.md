## E-Commerce Customer Churn Prediction

In the rapidly evolving world of e-commerce, understanding customer behavior is crucial for the growth and sustainability of online businesses. One of the key metrics that businesses need to monitor closely is customer churn, also known as customer attrition.

Customer churn refers to the scenario when a customer stops doing business or ends the relationship with a company. Predicting customer churn involves using data analysis and machine learning techniques to predict the likelihood of a customer leaving a service or product.

In the context of e-commerce, customer churn prediction can help businesses identify potential churners early on and take appropriate actions to retain them, thereby saving on the cost of acquiring new customers. This process involves analyzing various customer-related factors such as purchase history, customer engagement, product preference, and many others.

```
  customers.csv
```

| Feature     | Description                     |
| :---------- | :------------------------------ |
| `CustomerID`| Unique customer ID      |
| `Churn` | Churn Flag    |
| `Tenure`| Tenure of customer in organization      |
| `PreferredLoginDevice`| Preferred login device of customer      |
| `CityTier`| City tier     |
| `WarehouseToHome` | Distance between warehouse to home of customer   |
| `PreferredPaymentMode`| Preferred payment method of customer    |
| `Gender`| Gender of Customer      |
| `HourSpendOnApp`| Number of hours spend on mobile application or website      |
| `NumberOfDeviceRegistered` | Total Number of devices is registered on particular customer    |
| `PreferredOrderCat`| Preferred order category of customer in last month      |
| `SatisfactionScore`| Satisfactory score of customer on service      |
| `MaritalStatus`| Total number of added address on particular customer    |
| `NumberOfAddress` | Distance between warehouse to home of customer   |
| `Complain`| Any complaint has been raised in last month    |
| `OrderAmountHikeFromLastYear`| Percentage increases in order from last year      |
| `CouponUsed`| Total number of coupon used in last month    |
| `OrderCount` | Total number of orders has been placed in last month   |
| `DaySinceLastOrder`| Day since last order by customer    |
| `CashbackAmount`| Average cashback in last month      |


This project focuses on predicting customer churn for an e-commerce platform using machine learning. Churn prediction is crucial for businesses as it helps identify customers who are likely to stop using the platform, enabling proactive retention strategies. The goal of this project is to build a robust model that accurately predicts churn based on customer behavior and transaction data.

### 1. Problem Statement
Customer churn is a major challenge for e-commerce businesses, as acquiring new customers is often more expensive than retaining existing ones. The objective of this project is to develop a machine learning model that can predict which customers are likely to churn, enabling businesses to take action before they leave the platform. E-commerce customer churn prediction is a crucial area of research that utilizes various machine learning algorithms to forecast whether customers will continue their engagement with an online platform or discontinue their relationship. Several studies have explored this field, demonstrating the application of different predictive models and algorithms to tackle this challenge.

**Objectives**
- To perform a comprehensive analysis of the provided customer data to extract insights into customer behavior and characteristics.
- To construct a machine learning model that can accurately predict customers who are likely to churn. This model should leverage the provided variables to identify at-risk customers.

### 2. Dataset
The dataset used in this project contains various features related to customer behavior, demographics, and transaction history. Key features include:
- **CustomerID**: Unique identifier for each customer.
- **Demographic Information**: Gender, WarehouseToHome, CityTier, etc.
- **Transaction History**: PaymentMode, Preferred Order Category, Coupon Used, etc.
- **Engagement Metrics**: Hour Spend On App, Number Of Device Registered, Day Since Last Order.
- **Churn Status**: A binary feature indicating whether the customer has churned or not.

### 3. Data Preprocessing
Several steps were taken to clean and prepare the dataset for modeling:
- **Handling Missing Values**: Missing demographic and transaction data were handled using imputation techniques.
- **Encoding Categorical Variables**: Categorical features like gender and location were transformed into numerical values using encoding techniques such as one-hot encoding.
- **Feature Scaling**: Continuous variables like transaction amounts and time spent on the platform were scaled using normalization or standardization techniques to ensure consistent input to the model.
- **Feature Engineering**: New features such as customer lifetime value (CLV) and engagement score were created to provide more predictive power to the model.

### 4. Data Exploration and Visualization
Exploratory Data Analysis (EDA) was performed to understand the distribution of features and uncover insights about customer behavior:
- **Churn Distribution**: Visualizations to show the proportion of customers who churned versus those who didn’t.
- **Correlation Analysis**: Heatmaps and correlation matrices to examine relationships between features.
- **Behavioral Patterns**: Bar charts and line plots to explore how purchase frequency, average order value, and engagement affect churn likelihood.

### 5. Model Building
Several machine learning models were developed to predict customer churn:
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **XGBoost Classifier**
- **Support Vector Classifier (SVC)**

Each model was trained on the processed data, and hyperparameters were tuned using cross-validation to enhance performance.

### 6. Evaluation Metrics
The performance of the models was evaluated using the following metrics:
- **Accuracy**: Overall correctness of predictions.
- **Precision and Recall**: To assess the balance between correctly identifying churners and minimizing false positives.
- **F1-Score**: A harmonic mean of precision and recall, useful in cases of imbalanced data.
- **ROC-AUC Curve**: To evaluate the model's ability to distinguish between churned and non-churned customers.
- **Confusion Matrix**: To visualize true positives, false positives, true negatives, and false negatives.

### 7. Model Comparison and Interpretation
The models were compared based on their performance metrics, and the best-performing model was selected. Feature importance analysis was conducted to interpret which factors contributed the most to customer churn, providing actionable insights for the business.

### 8. Conclusion and Future Work
The project successfully predicted customer churn with a high degree of accuracy. The findings provide valuable insights into customer behavior, helping businesses identify at-risk customers. Future work includes:
- Improving the model by incorporating more advanced techniques such as deep learning.
- Deploying the model into a production environment to make real-time predictions.
- Integrating customer feedback and external factors such as market trends for more comprehensive churn prediction.

### 9. For Further Information
For more details and code implementation, please refer to the project notebook included in this repository.

---

This outline covers every aspect of your project and provides a clear and detailed explanation for potential viewers on GitHub.


