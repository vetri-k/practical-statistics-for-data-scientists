![Book cover](/images/cover-small.jpg)

# Code repository
**Practical Statistics for Data Scientists:**  

50+ Essential Concepts Using R and Python

by Peter Bruce, Andrew Bruce, and [Peter Gedeck](https://www.amazon.com/Peter-Gedeck/e/B082BJZJKX/)

- Publisher: O'Reilly Media; 2 edition (June 9, 2020)
- ISBN-13: 978-1492072942
- Buy on [Amazon](https://www.amazon.com/Practical-Statistics-Data-Scientists-Essential/dp/149207294X)
- Errata: http://oreilly.com/catalog/errata.csp?isbn=9781492072942

## Online
View the notebooks online:
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/gedeck/practical-statistics-for-data-scientists/tree/master/)

Excecute the notebooks in Binder: 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gedeck/practical-statistics-for-data-scientists/HEAD)

 This can take some time if the binder environment needs to be rebuilt. 

## R
Run the following commands in R to install all required packages
```
if (!require(vioplot)) install.packages('vioplot')
if (!require(corrplot)) install.packages('corrplot')
if (!require(gmodels)) install.packages('gmodels')
if (!require(matrixStats)) install.packages('matrixStats')

if (!require(lmPerm)) install.packages('lmPerm')
if (!require(pwr)) install.packages('pwr')

if (!require(FNN)) install.packages('FNN')
if (!require(klaR)) install.packages('klaR')
if (!require(DMwR)) install.packages('DMwR')

if (!require(xgboost)) install.packages('xgboost')

if (!require(ellipse)) install.packages('ellipse')
if (!require(mclust)) install.packages('mclust')
if (!require(ca)) install.packages('ca')
```

## Python
We recommend to use a conda environment to run the Python code. 
```
conda create -n sfds python
conda activate sfds
conda env update -n sfds -f environment.yml
```

## See also
- O'Reilly: https://oreil.ly/practicalStats_dataSci_2e
- Errata: http://oreilly.com/catalog/errata.csp?isbn=9781492072942
- The code repository for the first edition is at: https://github.com/andrewgbruce/statistics-for-data-scientists

-------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------

# "Practical Statistics for Data Scientists"
###### Peter Bruce & Andrew Bruce. [O'Reilly.] May 2017

O'Reilly has pages for the [book](http://shop.oreilly.com/product/0636920048992.do) and its [errata](http://www.oreilly.com/catalog/errata.csp?isbn=0636920048992). GoogleBooks appears to have a large part of the [book](https://books.google.co.uk/books?id=JtPTDgAAQBAJ&printsec=frontcover&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false). (I have the print version)

_"Statistical methods are a key part of of data science, yet very few data scientists have any formal statistics training. Courses and books on basic statistics rarely cover the topic from a data science perspective. This practical guide explains how to apply various statistical methods to data science, tells you how to avoid their misuse, and gives you advice on what's important and what's not."_

_"With this book, you’ll learn : "_

* Why **exploratory data analysis** is a key preliminary step in data science
* How **random sampling** can reduce bias and yield a higher quality dataset, even with big data
* How the principles of **experimental design** yield definitive answers to questions
* How to use **regression** to estimate outcomes and detect anomalies
* Key **classification** techniques for predicting which categories a record belongs to
* Statistical **machine learning** methods that “learn” from data
* **Unsupervised learning** methods for extracting meaning from unlabeled data

## Table of Contents
###### [condensed + numbered]
### 1. Exploratory Data Analysis
1. Elements of Structured Data
2. Rectangular Data
3. Estimates of Location
4. Estimates of Variability
5. Exploring the Data Distribution
6. Exploring Binary and Categorical Data
7. Correlation
8. Exploring Two or More Variables

### 2. Data and Sampling Distributions
9. Random Sampling and Sample Bias
10. Selection Bias
11. Sampling Distribution of a Statistic
12. The Bootstrap
13. Confidence Intervals
14. Normal Distribution
15. Long-Tailed Distributions
16. Student's t-Distribution
17. Binomial Distribution
18. Poisson and Related Distributions

### 3. Statistical Experiments and Significance Testing
19. A/B Testing
20. Hypothesis Tests
21. Resampling
22. Statistical Significance and P-Values
23. t-Tests
24. Multiple Testing
25. Degrees of Freedom
26. ANOVA
27. Chi-Square Test
28. Multi-Arm Bandit Algorithm
29. Power and Sample Size

### 4. Regression and Prediction
30. Simple Linear Regression
31. Multiple Linear Regression
32. Prediction Using Regression
33. Factor Variables in Regression
34. Interpreting the Regression Equation
35. Testing the Assumptions: Regression Diagnostics
36. Polynomial and Spline Regression

### 5. Classification
37. Naive Bayes
38. Discriminant Analysis
39. Logistic Regression
40. Evaluating Classification Models
41. Strategies for Imbalanced Data

### 6. Statistical Macine Learning
42. K-Nearest Neighbors
43. Tree Models
44. Bagging and the Random Forest
45. Boosting

### 7. Unsupervised Learning
46. Principal Components Analysis
47. K-Means Clustering
48. Hierarchical Clustering
49. Model-Based Clustering
50. Scaling and Categorical Variables


## Other Links
* [Author's GitHub repo](https://github.com/andrewgbruce/statistics-for-data-scientists) ...Code associated with the book "Practical Statistics for Data Scientists: 50 Essential Concepts"
