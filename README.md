# Group 2

Mini-Report: Customer Churn Analysis

Data: Telco Customer Churn

<img width="562" alt="team" src="https://github.com/user-attachments/assets/fec90f6d-d349-40c5-bfdc-f46314403e31">


Target:

1.Discover the factors that influence customer churn.

2.Provide analytics-based recommendations to retain customers and optimize business strategy.

I.Introducing the Data

Data set description:

Number of lines: 7,043 customers

Number of columns: 21 variables, including: Customer information: Gender, age, marital status.

Service information: Service type (Internet, Phone), Contract.

Cost: Monthly fees and total fees.

Result: Churn status – customers leave or continue to use the service.

Analysis goal:

1.Determine who is most likely to leave.

2.Analyze the main factors affecting churn.

Suggest improving strategies to retain customers.

1.Chart 1: Churn by Gender and Contract Type

Objective: Analyze the influence of gender and contract type on churn.

Analysis:

Chart: Grouped bar chart.

Identified from chart data: Monthly contracts have very high churn rates in both men and women. This shows that this type of contract easily causes customers to leave because it does not require a long-term commitment. 1-year and 2-year contracts have low churn rates for both men and women.
Customers who sign long-term contracts often have had a good experience or received an attractive incentive for a long-term commitment. Gender does not significantly affect churn rate: Both men and women have similar churn rates in each contract type.

Conclusion from the data:
Contract type is the main factor influencing churn, not gender. Monthly contracts give customers a lot of freedom of choice, and if the service doesn't meet expectations, they will quickly leave.

Long-term contracts (1 year and 2 years) help the company significantly reduce churn thanks to customer commitment. Promotions or discounts for these contracts have been effective.

Actions drawn from data: Improve experience for monthly contract customers:
Focus on the early stages (1-3 months) to build loyalty. Offer incentives or discounts for customers who sign longer contracts.

Increase promotion of long-term contracts:
Offer flexible packages or attractive promotions for customers switching from a monthly contract to a 1-year or 2-year contract. Extending the commitment period will help the company stabilize revenue and reduce churn in the long term.

<img width="612" alt="Screenshot 2024-10-19 083105" src="https://github.com/user-attachments/assets/b9059bd8-912a-4acf-86f7-4cee937c8ced">

1. Overview of Chart 2
Chart type: Boxplot (box chart) to compare monthly fees between two customer groups: Churn (Yes) and No Churn (No).

Objective: Test if there is a connection between monthly fees and churn. This helps determine whether price is a factor causing customers to leave the service.

Identify and Analyze Data from Charts
The average monthly fee of the Churn group is higher than the No Churn group: The box plot shows that the median value of Monthly Charges in the Churn group is significantly higher than that in the No Churn group. This suggests that high fees may be an important factor driving customers to leave the service.

The Churn group's monthly fee distribution range is wider: The Churn group has clients with monthly fees ranging from low to very high (with many outliers). This may reflect that it is not just high-fee customers that churn, but even mid-fee customers are likely to churn.

The No Churn group has lower and more stable fees: The monthly fee distribution of the No Churn group is relatively concentrated around the lower average (~40-60 USD). Customers with low fees tend to maintain service longer.

Conclusion from Chart 2
High monthly fees are correlated with high churn rates. Customers who pay more are more likely to leave the service, perhaps because they feel the cost is disproportionate to the value received.

Keeping prices reasonable is an important factor in reducing churn. Customers with lower monthly fees are less likely to churn.

However, average or low fees do not absolutely guarantee customer retention, as there are cases of outliers in the churn group with low fees.

Take Action from Data
Consider adjusting monthly fees: Evaluate the value of higher priced plans to ensure that customers feel they get their money's worth. Offer lower priced or flexible service plans for churn-prone customers.

Analyze other factors besides fees: Customers churn not only because of high fees, but also because the service has not met expectations. It is necessary to combine further analysis of service quality and satisfaction level.

Special offers for customer groups at risk of churn: Offer promotions or temporary fee reductions to customers showing signs of churn, especially those paying high fees.

<img width="556" alt="python 1" src="https://github.com/user-attachments/assets/f3af72d3-0045-4dee-8327-a6c3f00523fc">


Identified from chart data: The churn rate of Fiber optic service is the highest (~41% of the customer group with churn).

This shows that Fiber optic may be having problems with quality or value that is not commensurate with customer expectations. DSL has a markedly lower churn rate than Fiber optic.

Customers may feel DSL (Digital Subscriber Line) is more suitable for their needs and affordability.

Customers who do not use the Internet have a churn rate close to zero.

These customers may be holding on to other services (like TV or phone) and are less likely to leave the company.

Conclusion from the data: Even though Fiber optic is modern technology, it still causes many customers to leave. This may be due to:

High cost: Customers feel that there is not enough value received compared to the amount of money spent.

Competition: Fiber optic has many options from other providers, making it easy for customers to switch.

echnical problem: Service quality is not stable. Customers who do not use the Internet or use DSL have low churn rates, indicating that this group is relatively satisfied with the basic service.

Actions drawn from data:

Focus on improving Fiber optic quality:

Reduce downtime and increase bandwidth speed. Implement incentive programs for old customers to retain them.

Encourage DSL customers to switch to Fiber optic: Offer a free or discounted migration plan for the first few months.

<img width="635" alt="python 2" src="https://github.com/user-attachments/assets/bef4016f-e432-4e14-be8c-66c56ea0ccb3">


III.Conclusion and Recommendations

Conclude

Contract type: Customers with monthly contracts are more likely to leave.

Cost: Customers with high monthly fees are more likely to leave the service.

Time of use: Customers leave mainly in the first 6 months.

Strategy proposal

Promotion for long-term contracts: Discount for customers using monthly contracts to switch to a 1-year or 2-year package.

Promotional packages for new customers: Increase positive experiences in the first 6 months, for example, give vouchers or reduced fees.

Discounts for high paying customers: Build a loyalty program or service combo

IV.Applications for Management

Church analysis helps managers: Optimize marketing campaigns: Focus on high-risk customer groups.

Adjust pricing policy: Reduce churn by offering reasonable incentive programs.

Improve customer experience: Special care in the first months.




