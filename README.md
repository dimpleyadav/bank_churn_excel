# Bank Churn Rate Analysis

This dataset contains information about bank customers, including their demographics, financial details, and account activity. It provides insights into customer behavior and churn patterns (whether a customer has left the bank).

### Field description

![image](https://github.com/user-attachments/assets/dab90992-de68-454d-b687-89508283b064)

Customer churn rate is the percentage of customers who stop doing business with an organization over a period of time.

The churn rate formula is: (Lost Customers ÷ Total Customers at the Start of Time Period) x 100. For example, if your business had 250 customers at the beginning of the month and lost 10 customers by the end, you would divide 10 by 250. The answer is 0.04. You then multiply 0.04 by 100, resulting in a 4% monthly churn rate.

### Data Transformation

Added two columns: CreditBracket and AgeBracket. 

CreditBracket column has 5 categories namely Poor(300-579), Fair(580-669), Good(670-739), Very Good(740-799), and Excellent(800-850).

![image](https://github.com/user-attachments/assets/aaea4fea-cdfb-4939-95dc-9ba2d3d79f8a)

AgeBracket column has 3 categories namely Young(18-39), Middle(40-59), and Old(>=60).

![image](https://github.com/user-attachments/assets/059da4a8-27a0-45c6-bada-e45d40f7a978)

### Questions

1. What is the overall churn rate in the bank?

The overall churn rate is 20%.

2. How does the churn rate vary by different demographics like age, gender, geography, or credit score?

Churn varies significantly across demographics. Middle-aged(40-59) customers,mostly females and customers in Germany tend to churn more, while those with lower credit scores (i.e., less than 740) also have higher churn rates.

3. Are males or females more likely to churn?

Females are more likely to churn (1,139) compared to males (898).

4. Is churn consistent across France, Germany, and Spain?

No, churn is highest in Germany (814), followed by France (810), and lowest in Spain (413).

5. Which credit bracket has the highest churn rate?

Customers with Fair credit scores have the highest churn rate (685).

6. How are customer attributes like tenure, number of products, balance, and salary correlated with the likelihood of a customer churning (exiting) the bank?

The correlation values for tenure, number of products, balance and salary suggest that these factors have little to no effect on churn.

![image](https://github.com/user-attachments/assets/ff17e4fb-c5fe-49e4-a136-71c9a0f0fa45)


![image](https://github.com/user-attachments/assets/0c2718ee-7cc0-4caa-bfdf-4d7bb6e0d86a)




