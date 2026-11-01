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


## Problem 3: Comparing Species Using t-Tests

### Sources used for this problem

- Introduction to T-tests (https://www.datacamp.com/tutorial/an-introduction-to-python-t-tests?utm_cid=23340058065&utm_aid=192632748929&utm_campaign=230119_1-ps-dscia~dsa-tofu~python_2-b2c_3-europe_4-prc_5-na_6-na_7-le_8-pdsh-go_9-nb-e_10-na_11-na&utm_loc=1007850-&utm_mtd=-c&utm_kw=&utm_source=google&utm_medium=paid_search&utm_content=ps-dscia~europe-en~dsa~tofu~tutorial~python&gad_source=1&gad_campaignid=23340058065&gbraid=0AAAAADQ9WsFAHLMdsp2EXS7FTS3rwzL2M&gclid=CjwKCAjwo5bXBhAEEiwAkgpgXL_XVQTyDAK5U5FDqEveBlGUD7Kxbu0MjP-U3EsS8QobQLEn0qaE0RoCHIwQAvD_BwE)

- T-Statistic: https://www.datacamp.com/tutorial/t-statistic

- P-Value: https://numiqo.com/tutorial/p-value

- scipy packcage: https://docs.scipy.org/doc/scipy/reference/stats.html

- Statistic support: https://online.stat.psu.edu/stat100/Lesson10

- Table result: https://www.geeksforgeeks.org/python/how-to-make-a-table-in-python/