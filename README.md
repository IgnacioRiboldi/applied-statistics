# applied-statistics
Repository for Applied Statistics module - ATU
This project is written in a Jupyter Notebook, using Python Language and some of their packages that are mentioned below.

## Packages that have to be installed:

%pip install pandas scikit-learn numpy matplotlib

## Problem 1 Import iris Data Set

On this problem I am using sklearn to import iris data set and then pandas to load, organise and analyse the data.

After I use matplotlib to create the histogram.

### Sources used for this problem

Iris data set
https://scikit-learn.org/stable/api/sklearn.datasets.html

https://scikit-learn.org/1.4/auto_examples/datasets/plot_iris_dataset.html

How to import URL 
https://www.w3schools.com/python/ref_requests_get.asp

Build a Histogram with Mayplotlib
https://www.w3schools.com/python/matplotlib_histograms.asp

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.hist.html



## Problem 2: Petal Length and Petal Width

Pearson correlation: I used pearsonr() to measure the relationship between petal length and petal width.

Scatter plot: I used Seaborn's regplot() to visualise the relationship and its regression line.

Species comparison: I used groupby() to calculate the correlation for each species separately.

The overall correlation was approximately 0.96, showing a strong positive relationship. However, the correlations were lower when analysing each species separatel

### Sources used for this problem
- [Scikit-learn – Iris dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html)
- [SciPy – Pearson correlation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.pearsonr.html)
- [Seaborn – Regression plots](https://seaborn.pydata.org/tutorial/regression.html)