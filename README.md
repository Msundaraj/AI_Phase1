<h1 align="center"> MARKET BASKET INSIGHTS </h1>

<p align="center">
<a>
    <img alt="MARKET" src="sources/giphy-mbi.gif">
 </a>
  </p>

## Table of content
- [Design thinking](#design-thinking)
- [Innovation](#innovation)
- [Development part 1](#development-part-1)
- [Development part 2](#development-part-2)

## Design thinking
- **Data source** : A dataset containing transaction data, including lists of purchased products, is typically structured as a table or a collection of records. Each record represents a single transaction, and it includes information about the products that were purchased during that transaction. Here is an example schema for such a dataset:
- **Data processing** :
   - Item Identification
   - Binary Matrix Creation
   - Save the Binary Matrix
   - Perform Association Analysis
   - Interpret and Act
- **Association analysis** : The Apriori algorithm is a classic algorithm used for frequent itemset mining and generating association rules in data mining and market basket analysis. It works by iteratively finding frequent itemsets and generating association rules based on a minimum support threshold. Here's how you can utilize the Apriori algorithm in Python using libraries like mlxtend to identify frequent itemsets and generate association
rules
- **visualisation** : various types of visualizations and how you can create them to present discovered associations and insights from your data. You can then use a data visualization tool like Tableau, Excel, Python with libraries like Matplotlib or Seaborn, or any other preferred tool to create these visualizations. Here are some visualization ideas

## Innovation

<p>I have found some methods to do a prediction</p>

- **Ensemble Methods: Enhancing Accuracy and Robustness**
   - Bagging (Bootstrap Aggregating)
   - Boosting Algorithms (AdaBoost, Gradient Boosting):
   - Random Forest
-  **Deep Learning Architectures: Harnessing Neural Networks for Complex
Patterns**
   - Convolutional Neural Networks (CNNs)
   - Recurrent Neural Networks (RNNs)
   - Generative Adversarial Networks (GANs)
- Advanced Association Analysis Techniques: Mining Deep Insights
   - Apriori Algorithm
   - FP-growth Algorithm
## Development part 1

<p>In this part I did a preprocessing on a dataset </p>

### Required Libraries 
```
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from mlxtend.frequent_patterns import apriori, association_rules
```
[mlxtend](https://rasbt.github.io/mlxtend/) Mlxtend (machine learning extensions) is a Python library of useful tools for the day-to-day data science tasks

[Pandas](https://pandas.pydata.org/) pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language

[matplotlib](https://matplotlib.org/) Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python

[seaborn](https://seaborn.pydata.org/) Seaborn is a Python data visualization library based on matplotlib

[Scikit-learn](https://github.com/scikit-learn/scikit-learn) - tool for predictive data analysis built on numpy, scipy and matplotlib.

## Development part 2

  <p align="left" width="100%">
    <img  src="/sources/cluster.png">
</p>

<p>
  What is sklearn cluster?
  
It stands for “Density-based spatial clustering of applications with noise”. This algorithm is based on the intuitive notion of “clusters” & “noise” that clusters are dense regions of the lower density in the data space, separated by lower density regions of data points. Scikit-learn have sklearn. cluster
</p>




