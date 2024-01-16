# Market-Basket-Analysis-using-Python
Market Basket Analysis is a data-driven technique used to uncover patterns and relationships within large transactional datasets, particularly in retail and e-commerce. It helps businesses understand which products or items are often purchased together, providing insights for optimizing product placement, marketing strategies, and promotions. So, if you want to learn how to perform Market Basket Analysis, this article is for you. In this article, I’ll take you through the task of Market Basket Analysis using Python.

# Market Basket Analysis: Process We Can Follow
1.Gather transactional data, including purchase history, shopping carts, or invoices.
2.Analyze product sales and trends.
3.Use algorithms like Apriori or FP-growth to discover frequent item sets and generate association rules.
4.Interpret the discovered association rules to gain actionable insights.
5.Develop strategies based on the insights gained from the analysis.

# The above output shows association rules between different items (antecedents) and the items that tend to be purchased together with them (consequents). Let’s interpret the output step by step:

**Antecedents:** These are the items that are considered as the starting point or “if” part of the association rule. For example, Bread, Butter, Cereal, Cheese, and Chicken are the antecedents in this analysis.
**Consequents:** These are the items that tend to be purchased along with the antecedents or the “then” part of the association rule.
**Support:** Support measures how frequently a particular combination of items (both antecedents and consequents) appears in the dataset. It is essentially the proportion of transactions in which the items are bought together. For example, the first rule indicates that Bread and Apples are bought together in approximately **4.58%** of all transactions.
**Confidence:** Confidence quantifies the likelihood of the consequent item being purchased when the antecedent item is already in the basket. In other words, it shows the probability of buying the consequent item when the antecedent item is bought. For example, the first rule tells us that there is a **30.43%** chance of buying Apples when Bread is already in the basket.
**Lift:** Lift measures the degree of association between the antecedent and consequent items, while considering the baseline purchase probability of the consequent item. A lift value **greater than 1** indicates a **positive association**, meaning that the items are more likely to be bought together than independently. A value **less than 1** indicates a **negative association**. For example, the first rule has a lift of approximately **1.86**, suggesting a positive association between Bread and Apples.

*So, this is how you can perform Market Basket Analysis using Python.*

# Summary:
Market Basket Analysis is a valuable tool for businesses seeking to optimize their product offerings, increase cross-selling opportunities, and improve marketing strategies. It can lead to higher revenue, enhanced customer satisfaction, and overall business success. I hope you liked this article on Market Basket Analysis using Python. 
