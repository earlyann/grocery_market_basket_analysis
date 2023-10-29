## Grocery Market Basket Analysis using Apriori Algorithm

### Overview
This project aims to analyze customer purchasing behavior in a grocery store using the Apriori algorithm for association rule mining. The dataset contains transactional data from 2014-01-01 to 2015-12-30, with unique 3898 customers, 167 items, and 14963 transactions.

#### What is the Apriori Algorithm?
The Apriori algorithm is a popular algorithm for mining frequent itemsets for Boolean association rules. It uses a breadth-first search strategy to explore the search space of possible itemsets and identifies all itemsets that have support greater than the user-specified minimum support. The algorithm then uses these frequent itemsets to generate association rules, which highlight itemsets that are often purchased together.

#### Key Terms
- Itemset: A set of one or more items.
- Support: The proportion of transactions in the dataset which contain an itemset.
- Confidence: Given two items A and B, confidence measures the percentage of times that item B is purchased, given that item A was purchased.
- Lift: The ratio of the observed support to that expected if the two rules were independent. Lift value greater than 1 indicates a useful rule.

#### Project Steps
- Data Preprocessing: The raw transactional data is transformed into a format suitable for association rule mining.
- Frequent Itemset Generation: The Apriori algorithm is applied to find frequent itemsets in the dataset.
- Rule Generation: Association rules are generated based on the frequent itemsets.
- Rule Evaluation: The generated rules are evaluated using metrics like support, confidence, and lift.
- Visualization: Various visualizations are used to interpret the rules.

#### Libraries Used
- Pandas for data manipulation
- mlxtend for Apriori algorithm implementation
- Matplotlib and Seaborn for data visualization
- NetworkX for network graphs

### Visualizations
- 
### Results
- in progress- 
