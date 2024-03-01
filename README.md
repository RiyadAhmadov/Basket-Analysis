# Apriori Algorithm for Basket Analysis

!['Apriori Algorithm'](https://github.com/RiyadAhmadov/Basket-Analysis/assets/116457780/f50d4295-af8e-443f-8815-a2f67b8e07e3)

## Introduction to Apriori Algorithm

The Apriori algorithm, proposed by Rakesh Agrawal and Ramakrishnan Srikant in 1994, is a classic algorithm in data mining. It is widely used for discovering association rules from large datasets. The algorithm is particularly efficient in finding frequent itemsets, which are sets of items that frequently appear together in transactions.

## How Apriori Works

The Apriori algorithm employs a breadth-first search strategy to discover frequent itemsets in a dataset. It uses the "apriori property," which states that if an itemset is frequent, then all of its subsets must also be frequent. The algorithm iteratively generates candidate itemsets, counts their support in the dataset, and prunes the candidates that do not meet a minimum support threshold.

The main steps of the Apriori algorithm include:

1. **Generate Candidate Itemsets:** Create candidate itemsets of length k based on frequent itemsets of length k-1.
2. **Scan Dataset:** Count the support of each candidate itemset by scanning the entire dataset.
3. **Prune Candidates:** Remove candidate itemsets that do not meet the minimum support threshold.
4. **Repeat:** Repeat the process until no new frequent itemsets can be generated.

## Applications of Apriori Algorithm

The Apriori algorithm finds applications in various fields, including:

- **Retail:** Analyzing shopping basket data to identify product associations and improve marketing strategies.
- **Healthcare:** Discovering patterns in patient records to improve healthcare management.
- **Web Usage Mining:** Analyzing user behavior on websites to enhance user experience.
- **Telecommunications:** Identifying calling patterns and customer preferences.

## Where Apriori is Used ?

The Apriori algorithm is used in a variety of industries and domains, including:

- **Retail and E-commerce:** Analyzing customer purchase behavior to optimize product placement and promotions.
- **Healthcare:** Identifying co-occurrence of symptoms or diseases in patient records.
- **Finance:** Detecting fraudulent activities by finding patterns in transaction data.
- **Marketing:** Understanding customer preferences and improving targeted advertising.

Let's look at rules's header description: 

1. **antecedents**: 
   - Description: Items that usually appear before another set of items.
   - Text Description: Things that often happen before something else.

2. **consequents**:
   - Description: Items that usually appear after another set of items.
   - Text Description: Things that often happen after something else.

3. **antecedent support**:
   - Description: How often the first set of items appears alone.
   - Text Description: How often the first things occur by themselves.

4. **consequent support**:
   - Description: How often the second set of items appears alone.
   - Text Description: How often the second things occur by themselves.

5. **support**:
   - Description: How often both sets of items appear together.
   - Text Description: How often both things happen at the same time.

6. **confidence**:
   - Description: How likely the second set of items appears when the first set appears.
   - Text Description: How sure we are that the second things happen when the first things happen.

7. **lift**:
   - Description: How much more likely the second set of items appears when the first set appears compared to random chance.
   - Text Description: How much more often the second things happen when the first things happen, compared to if they were unrelated.

8. **leverage**:
   - Description: How much more often both sets of items appear together than expected if they were independent.
   - Text Description: How much more often both things happen together than we'd expect if they were unrelated.

9. **conviction**:
   - Description: How much more likely it is that the first set of items appears without the second set compared to if they were unrelated.
   - Text Description: How much more likely it is for the first things to happen without the second things, compared to if they weren't related.

10. **zhangs_metric**:
    - Description: A combined measure of how likely the second set of items is given the first set, and how much more likely it is compared to random chance.
    - Text Description: A way to see how likely the second things are given the first things, and if that's more likely than random chance.


## Contributing

Riyad Ahmadov
_(Data Scientist / Data Analyst)_

## Contact

For questions or feedback regarding this README or Apriori Algorithm project, please contact *Riyad* at *riyadehmedov03@gmail.com*.
