## E-Commerce Customer Churn Prediction

In the rapidly evolving world of e-commerce, understanding customer behavior is crucial for the growth and sustainability of online businesses. One of the key metrics that businesses need to monitor closely is customer churn, also known as customer attrition.

Customer churn refers to the scenario when a customer stops doing business or ends the relationship with a company. Predicting customer churn involves using data analysis and machine learning techniques to predict the likelihood of a customer leaving a service or product.

In the context of e-commerce, customer churn prediction can help businesses identify potential churners early on and take appropriate actions to retain them, thereby saving on the cost of acquiring new customers. This process involves analyzing various customer-related factors such as purchase history, customer engagement, product preference, and many others.

E-commerce customer churn prediction is a crucial area of research that utilizes various machine learning algorithms to forecast whether customers will continue their engagement with an online platform or discontinue their relationship. Several studies have explored this field, demonstrating the application of different predictive models and algorithms to tackle this challenge.

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

### Objectives
- To perform a comprehensive analysis of the provided customer data to extract insights into customer behavior and characteristics.
- To construct a machine learning model that can accurately predict customers who are likely to churn. This model should leverage the provided variables to identify at-risk customers.
