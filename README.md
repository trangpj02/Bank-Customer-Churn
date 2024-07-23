# Bank-Customer-Churn

![image](https://github.com/user-attachments/assets/dd655470-a950-45d3-8b01-b877f50597b2)

# Project Description

The goal of this analysis is to identify the factors driving the increased customer churn rate at the bank and to provide business users with actionable insights. These insights will enable them to make informed decisions and develop strategies to enhance customer retention and reduce churn.

# Data Overview

Data sources: [here](https://www.kaggle.com/datasets/zagroz901/customer-churn-dataset?select=Customer-Churn-Records.csv)

The dataset used for this analysis contains 10,000 rows and 18 columns.

Columns description:

- `RowNumber`: corresponds to the record (row) number and has no effect on the output.
- `CustomerId`: contains random values and has no effect on customer leaving the bank.
- `Surname`: the surname of a customer has no impact on their decision to leave the bank.
- `CreditScore`: can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
- `Geography`: a customer’s location can affect their decision to leave the bank.
- `Gender`: it’s interesting to explore whether gender plays a role in a customer leaving the bank.
- `Age`: this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
- `Tenure`: refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
- `Balance`: also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
- `NumOfProducts`: refers to the number of products that a customer has purchased through the
- `HasCrCard`: denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
- `IsActiveMember`: active customers are less likely to leave the bank.
- `EstimatedSalary`: as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
- `Exited`: whether or not the customer left the bank.
- `Complain`: customer has complaint or not.
- `Satisfaction Score`: Score provided by the customer for their complaint resolution.
- `Card Type`: type of card hold by the customer.
- `Points Earned`: the points earned by the customer for using credit card.

# Data Visualization

![Screenshot (52)](https://github.com/user-attachments/assets/55adf576-bc83-45a7-a0e2-e262b6bd6239)

![Screenshot (53)](https://github.com/user-attachments/assets/63ecfa46-3596-4abc-9144-95c6247f212f)

# Insights

1. Female customers have a higher rate of churn compared to male customers. They make up 44% of total customers base but account for 56% of the churn churn.
2. Diamond card holders are the ones who exited the most for both the genders.
3. France reported the highest churn, followed by Germany and Spain.
4. It is obvious that an inactive customer are more likely to churn than active ones. Although they represent 48% of the customers base, they contribute to 64% of the churn.
5. The age group 45–60 experiences a high churn rate of 40%.
6. 70% of customers who own credit cards have exited the bank.
7. Bank customers who purchased at least 1 product through the bank show a higher churn percentage than other categories.
8. Credit Score:
    - Customers with scores < 400 churn at a 100% rate
    - Score groups of 400 and above have a churn rate fluctuating between 19-21%
9. Whose account balance are >200k have the highest churn rate
10. Unfortunately, veteran customers (7-10 years) have the highest churn rate.
11. It can be seen that most of the customers of various age interval were having good and excellent points (>400) interval. It is bad news for the bank as really loyal and frequent service users are exiting the bank.

# Possible Causes

1. **Customer Satisfaction:** These products and services may not meet customer expectations or needs.
    - Complain: out of 2038 customers that exited the bank, 2034 customers had complaints. Additionally, older customers (45-60 years old) had the highest number of complaints.
    - Satisfaction score: around 40% of the churned customers gave bad (<3/5) satisfaction score
2. **Lack of engagement and insufficient communication with inactive customers**
3. **Finance:** Customers with low credit scores might face financial difficulties, making it hard for them to maintain their accounts.
4. **Geographical disparities:** Cultural differences or localized service issues
5. **Competitors** might be providing better offers.

# Suggestions

1. **Improve Customer Satisfaction**
    
    Regularly collect and analyze customer feedback to identify pain points and areas for improvement. Implement changes based on feedback to enhance customer satisfaction and reduce churn.
    
2. **Localized Services**
    
    Tailor services and offers to meet the cultural and localized needs of customers in different regions,
    
3. **Re-engagement Strategies for Inactive Customers**
    
    Implement re-engagement campaigns to activate inactive customers. This could include personalized offers, reminders about unused benefits, and incentives for account activity.
    
4. **Age-Specific Engagement**
For the 45–60 age group, consider offering products and services that cater to their life stage, such as retirement planning, health insurance, and investment opportunities. Personalized communication and support can also help retain this demographic.
5. **Credit Card Ownership**
    
    Develop retention offers for credit card holders, such as cashback rewards, lower interest rates, and exclusive benefits, while also considering fee reductions to make credit cards more attractive.
    
6. **Product Utilization Encouragement**
Encourage customers to purchase and use more bank products by highlighting the benefits and providing bundled offers. Educate customers on how these products can meet their financial needs.
7. **Credit Score Improvement Programs**
    
    Offer financial counseling and credit score improvement programs to customers with low credit scores. This can help them manage their finances better and reduce the likelihood of churn.
    
8. **Premium Services for High-Balance Customers**
    
    Provide premium services and personalized financial advice to customers with account balances over 200k. Ensure they feel valued and receive the level of service they expect.
    
9. **Veteran Customer Appreciation**:
    
    Recognize and reward long-term customers with special loyalty programs, anniversary bonuses, and personalized services to show appreciation for their loyalty and reduce churn.
    
10. **Competitor Analysis and Competitive Offers**
    
    Conduct a thorough analysis of competitors’ offerings and develop competitive and attractive offers to retain customers. Highlight the unique benefits of staying with your bank.
