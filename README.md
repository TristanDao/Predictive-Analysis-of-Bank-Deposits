# **Predictive Analysis of Bank Deposits**

Dataset Name: **Bank Target Marketing Dataset**

Source: [Kaggle](https://www.kaggle.com/datasets/seanangelonathanael/bank-target-marketing) ( 17columns, 9994 rows)

## Context

The older marketing options have contributed minimally to increasing the business of banks. Due to internal competition and financial crisis, European Banks were under pressure to increase their financial assets. They offered long-term deposits with good interest rates to the people using a direct marketing strategy but contacting many people takes a lot of time and the success rate is also less. So they want to take the help of technology to come up with a solution that increases efficiency by making fewer calls but improves the success rate. Banking Institutions have provided the data related to marketing campaigns that took over phone calls.

## Objective

- One of the Portuguese banking institutions conducted a marketing campaign based on phone calls. The records of their efforts are available in the form of a dataset. The objective here is to apply machine learning techniques to analyze the dataset and figure out the most effective tactics that will help the bank in its next campaign to persuade more customers to subscribe to bank term deposits.
- Bank profitability depends on long-term deposits. Targeted marketing tactics that let customers interact with banks directly are the main focus of bank marketing.

## Main Question:

1. **How can the bank reduce the high rate of negative responses in marketing campaigns?**

2. **How can the bank optimize customer outreach while minimizing resource expenditure?**

3. **Which customer segments should the bank prioritize based on data from previous campaigns?**

4. **What strategies can improve the success rate of future marketing campaigns using existing customer data?**

5. **How can the bank increase the proportion of customers who register for long-term deposits?**

6. **Which machine learning models can be used to predict customer behavior and improve the targeting of marketing campaigns?**

## Result

### 1. Customer Insights

- **Occupation:** Students and unemployed individuals have a higher propensity to sign up for long-term deposits compared to other groups.
- **Age:** Customers between the ages of 20-30 and over 60 have the highest registration rates.
- **Loans:** Customers without personal loans, home loans, or credit defaults have a higher registration rate.
- **Balance:** Customers with positive or average balances are more likely to register than those with negative or zero balances.
- **Previous campaign results:** Customers who participated in previous deposit campaigns are highly likely to re-register.

### 2. Campaign Insights

- **Contact month:** May and the last months of the year have the highest number of successful customer contacts.
- **Call duration:** The likelihood of success increases with longer call durations.
- **Number of contacts:** Customers contacted fewer than 5 times have a higher success rate than those contacted multiple times.

### 3. Machine Learning Model

- **GradientBoostingClassifier** was chosen after testing many different models, with a recall of 0.75 and precision of 0.51.

## Recommendations

- **Focus on high-potential customers:** Prioritize campaigns targeting **students, unemployed individuals, retirees, and customers without loans or bad debt**.
- **Prioritize customers from previous campaigns:** Re-engage customers who have signed up for long-term deposits in previous campaigns to increase the success rate of the next campaign.
- **Optimize contact timing:** Intensify campaigns during the **last months of the year** and focus on increasing call duration with potential customers.
- **Select customers to contact:** Avoid contacting customers with negative or zero balances multiple times as they are less likely to sign up for long-term deposits.
- **Deeper analysis of contact timing and frequency:** Adjust the number of contacts with potential customers to **less than 5 times** to optimize conversion rates.
