# MSCS_634_Lab_6

## README for MSCS_634_Lab_6: Association Rule Mining with Apriori and FP-Growth
Overview

This repository contains the Jupyter Notebook for Lab 6: Association Rule Mining using Apriori and FP-Growth. The purpose of this lab is to understand how association rule mining works and to apply two major algorithms—Apriori and FP-Growth—to extract meaningful patterns from a real-world dataset. The dataset used is the IMDb Top 1000 Movies, which includes attributes such as genres, directors, and leading stars. These features are converted into item transactions, enabling the discovery of hidden relationships within the movie industry.

## Purpose of the Lab

The main goal of this lab is to:

Explore how frequent itemsets and association rules are generated.

Compare the efficiency and performance of the Apriori and FP-Growth algorithms.

Interpret the patterns discovered from the IMDb dataset to gain insights into common movie characteristics.

## Key Insights and Findings

Through the analysis and rule mining process, several important insights were identified:

Frequent Genre Combinations: Genres such as Drama, Action, and Adventure frequently appeared together across many movies.

Popular Director-Actor Patterns: Some directors consistently worked with specific actors, which showed up as strong association rules.

High-Lift Rules: Several rules with high lift indicated strong correlations—for example, movies featuring certain stars tended to share similar genres.

FP-Growth was generally faster than Apriori on this dataset, especially during frequent itemset generation.

These insights help reveal common patterns in film creation, casting, and genre selection.

## Challenges and Decisions Made

During the lab, the following challenges were encountered:

Data Preprocessing Complexity: Some rows contained missing or inconsistent values, requiring cleaning before converting attributes into transactions.

Selecting Minimum Support/Confidence: Choosing appropriate thresholds was critical. Too high led to very few rules; too low resulted in too many uninformative rules.

Algorithm Performance Differences: Apriori took longer for itemset generation due to its iterative nature, whereas FP-Growth required building an FP-tree, which is efficient but takes more memory.

Decisions such as using moderate support thresholds and cleaning the dataset helped ensure meaningful, interpretable results.


## Conclusion

This lab demonstrated the strengths of Apriori and FP-Growth for mining frequent itemsets and association rules. Both algorithms uncovered meaningful patterns from the IMDb dataset, such as recurring genre combinations and director–actor relationships. FP-Growth proved to be more efficient computationally, while Apriori provided more transparent step-by-step generation of itemsets. Overall, the lab enhanced understanding of association rule mining concepts and their practical applications.

