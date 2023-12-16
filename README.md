# My Interactive Bank Customer Churn Analysis Project Using a Mock Dataset

<h2>Tableau Dashboard Link: https://public.tableau.com/views/Bank_Churn_Analysis_17024737420960/Story1?:language=en-US&:display_count=n&:origin=viz_share_link</h2>

<h2>Description</h2>
This is an exploratory data analysis project where I have a wider range of freedom to examine various data points to make observations and improve the company. In this memo, I'll be covering every graph and chart displayed in my project and explaining its meaning and/or significance in the context of improving the business (the bank in this case). I'll be using Tableau for this visualization to showcase my range of tools, along with Tableau having more visually-pleasing and clearer visuals. I utilized my business understanding, technical skills, and critical thinking skills for this project. 

<h2>What is Customer Churn?</h2>
Customer churn, also known as customer turnover, refers to the percentage of lost customers. "Lost customers" in the context of banking, are customers who close their accounts or have stopped using bank services over a specific period. In this case, it will be measured in years. A lower churn rate is desired since it signifies that customers stay with the bank for longer.

<h2>Observations & Next Steps</h2>

![BankChurn1](https://github.com/javamesql/Bank-Churn-Analysis-Project/assets/141413672/72d19835-3b83-4603-b759-1aee8d2e4832)

In this chart comparing customer age, number of customers, and churn rate, customers between 45 and 60 tend to leave the bank at much higher rates than other age groups. This may be due to the bank catering to relatively younger customers resulting in older customers being disatisfied. Or, it could be related to life changes like retirement. Some actionable steps might be creating retirement-focused financial plans or the offering of specific incentives catering to older customers.

![BankChurn2](https://github.com/javamesql/Bank-Churn-Analysis-Project/assets/141413672/1fd6bcaa-ae99-4141-a170-bf1270761c75)

This chart compares the number of customers to tenure and churn rate. Tenure, or the years that the customers have been using the bank for, doesn't really impact churn rates as they're relatively constant across all tenures. This is a good sign of stability since the amount of customers seem to be similar across all years of tenure. The consistent churn rates across tenure years suggests that the bank's customer retention strategies might've have been effective.

![BankChurn3](https://github.com/javamesql/Bank-Churn-Analysis-Project/assets/141413672/bbdff935-418d-40dc-acc8-06392f4cffa6)

This chart shows the relationship between the number of customers, their points earned, and the churn rate. The churn rate among customers with fewer points is notably higher than those with more points. Customers who have 200 points and over, churn at a consistent rate. It might be possible that customers with fewer points may not be using the bank's services, leading to a higher likelihood of leaving.

![BankChurn4](https://github.com/javamesql/Bank-Churn-Analysis-Project/assets/141413672/e80329fe-2a8a-4776-9e80-41e1e3c072d9)

An interesting trend emerges when comparing the number of customers, number of products, and churn rate between them. Customers with 3 or 4 products left more often. There's also a large disparity between the amount of customers with 1 or 2 products and customers with 3 or 4 products. It seems like customers either didn't like the fact that they were sold many products or that managing multiple products were too complex or that additional services weren't adding value. I'd recommend reevaluating the value of addition products or providing more incentives for customers to have more products.

![BankChurn5](https://github.com/javamesql/Bank-Churn-Analysis-Project/assets/141413672/2160598d-e5dc-48eb-9945-2bb7f81366a4)

This chart compares the amount of customers exited, tenure, and points earned. The points earned seems to be relatively constant over tenure. In the case of the amount of customers exited, customers who have been with the bank for less than a year and over 10 years exit the least. While there is a consistent amount of customers exiting in between. The bank might want to have customer retention strategies targeted to those in between 1 and 10 years of tenure.

![BankChurn6](https://github.com/javamesql/Bank-Churn-Analysis-Project/assets/141413672/2b86b43d-3a22-44d6-b123-a31d8d6e54ab)

According to the cross-tabulation, active customers who have not complained at all have not left the bank, whereas inactive customers who have complained pretty much have all left the bank. While a measly .11% of customers who aren't active anymore didn't complain. My recommendation is to improve the process of customer complaint resolution and customer support.

![BankChurn7](https://github.com/javamesql/Bank-Churn-Analysis-Project/assets/141413672/30de7f4d-f63b-4775-bc80-5461c5b029e2)

Surprisingly, the churn rates across satisfaction scores were relatively stable, along with the relatively even amount of customers among the different satisfaction scores. I would have thought that lower satisfaction scores would lead to higher churn rates. This metric needs deeper analysis on. There might be factors outside of this dataset that influences this occurance.

![BankChurn8](https://github.com/javamesql/Bank-Churn-Analysis-Project/assets/141413672/399a3049-5703-4418-adc0-682113265aab)

These 2 charts compares card types, churn rates, and tenure. I conclude that for customers who have been with the bank for under 7 years, churn rates tend to be lowest for gold card types and highest for diamond card types. There's quite an amount of volatility for card types with over 7 years of tenure. Although churn rates are overall the lowest for gold card types and highest for diamond card types, the difference between the two are relatively miniscule.

![BankChurn9](https://github.com/javamesql/Bank-Churn-Analysis-Project/assets/141413672/0bf1eab7-7629-461c-9698-6a764da1977d)

Lastly, the map shows that customers from Germany churn almost twice as much as compared to customers in Spain or France. Some factors that might have affected this disparity in churn rates are a socioeconomic or demographic difference. Or it may be a difference in marketing strategy, service quality, or competition compared to the 2 other countries. I recommend investigating the difference through surveys, market research, or analysis of customer interactions with the bank.

<h1>Data Sources</h1>
<h2>Bank Customer Churn Dataset From Kaggle: https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn/data</h2>


