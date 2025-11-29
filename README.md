# MSCS_634_Lab_6

#  Association Rule Mining with Apriori and FP-Growth

## Overview

This repository contains the Jupyter Notebook for **Lab 6: Association Rule Mining with Apriori and FP-Growth**. In this lab, we explore the association rule mining techniques using the **Apriori** and **FP-Growth** algorithms. The goal of this lab is to analyze a dataset, identify frequent itemsets, and generate meaningful association rules to uncover hidden patterns in the data.

The dataset used in this lab is the **IMDb Top 1000 Movies** dataset, which includes various movie attributes such as genres, directors, and stars. These attributes are treated as items in a transaction dataset, allowing us to apply association rule mining techniques to discover correlations between these items.

## Objectives

1. **Frequent Itemset Mining**: 
   We mine frequent itemsets from the dataset using both **Apriori** and **FP-Growth** algorithms.
   
2. **Association Rule Generation**: 
   After finding frequent itemsets, we generate association rules and evaluate metrics such as support, confidence, and lift to interpret the results.

3. **Comparative Analysis**: 
   The lab includes a comparison of the performance of the **Apriori** and **FP-Growth** algorithms in terms of execution time and effectiveness.

## Steps Covered

1. **Data Preprocessing**: 
   - Cleaned the dataset by removing rows with missing values.
   - Converted relevant columns (genre, director, and stars) into lists for transaction encoding.

2. **Apriori and FP-Growth Implementation**: 
   - Implemented the **Apriori** algorithm for frequent itemset mining.
   - Implemented the **FP-Growth** algorithm for comparison.

3. **Visualization**: 
   - Created visualizations of the most frequent itemsets using **Seaborn** to highlight key patterns.

4. **Performance Comparison**: 
   - Compared the execution times of **Apriori** and **FP-Growth**.

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- MLxtend (for Apriori and FP-Growth)

## How to Run

1. Clone the repository to your local machine.
2. Install the required libraries using pip:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run each cell in sequence.

## Conclusion

The lab provides a detailed comparison between **Apriori** and **FP-Growth**, highlighting their strengths and limitations for frequent itemset mining and association rule generation. Both algorithms successfully mined interesting patterns from the IMDb dataset, with Apriori proving faster for the given data size.



Happy mining!

