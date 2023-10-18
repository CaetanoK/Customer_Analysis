# Customer Segmentation Analysis for an American Bank

In this study, we aim to understand the customer base of an American bank to categorize them into groups using the "clustering" technique. This allows us to tailor marketing campaigns that are increasingly effective and specific for each group.

## Data Preparation
The data source for this project is from Kaggle, and it can be found [here](https://www.kaggle.com/code/caesarmario/clustering-for-effective-marketing-strategy). The dataset comprises approximately 160,000 records, with 8,950 customer entries classified across 17 features.

For a comprehensive understanding of each column, please refer to the complete explanation provided on the [Kaggle website](https://www.kaggle.com/code/caesarmario/clustering-for-effective-marketing-strategy). However, some key features that will be crucial in the initial analysis are:

- **"BALANCE"**: The amount of money the customer keeps in their account.
- **"ONEOFF_PURCHASES"**: The quantity of one-time purchases made by each customer.
- **"PURCHASE_FREQUENCY"**: Indicates how frequently a consumer makes a purchase, with 1 being the maximum purchase frequency.
- **"CASH_ADVANCE"**: The loan amount (withdrawn from the credit card balance) for each customer.

In this type of clustering application, it is highly important to involve someone with a business-oriented perspective. While a Data Analyst plays a crucial role in quickly determining insights, a deeper understanding of each group is enhanced by collaboration with business and marketing teams. This collaboration is vital for crafting campaigns tailored to each segment.

Despite utilizing six groups in this study, I particularly delved deeper into understanding three groups:

1. **VIP Group**: Customers with higher credit limits who frequently pay the full statement amount. The bank might consider increasing the credit limit for this group to further stimulate purchases, given their low risk of default.

2. **High-Risk Group**: Customers who take out many loans and seldom pay the full amounts of their installments. Although their account balance is close to the loan amount, the bank needs to remain vigilant to prevent the debt from escalating, ensuring that the bank ultimately receives the outstanding amounts.

3. **Low Activity Group**: Customers who exhibit minimal account activity and keep little money in their checking account. A possible reason for not keeping money idle could be a preference for investment with higher returns. The bank could consider showcasing the benefits of using the card to these users, as the bank also generates revenue per transaction.

This collaborative approach involving business, data analysis, and marketing teams ensures a holistic understanding of customer segments, leading to more targeted and effective strategies.
