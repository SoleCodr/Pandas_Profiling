# Pandas_Profiling
This repository shows the use of module pandas_profiling to automate the work for Exploratory Data Analysis.
To view notebook with rendered open this <a href = "https://nbviewer.jupyter.org/github/SoleCodr/Pandas_Profiling/blob/583af9f8dba19575905771b5ba62db5c9221c9c7/Pandas_profiling.ipynb"> Noteook </a>
### About Pandas_Profiling
It generates profile reports from a pandas `DataFrame`. The pandas `df.describe()` function is great but a little basic for serious exploratory data analysis. `pandas_profiling` extends the pandas DataFrame with `df.profile_report()` for quick data analysis.

For each column the following statistics - if relevant for the column type - are presented in an interactive HTML report:
* **Type inference**: detect the types of columns in a dataframe.
* **Essentials**: type, unique values, missing values
* **Quantile statistics** like minimum value, Q1, median, Q3, maximum, range, interquartile range
* **Descriptive statistics** like mean, mode, standard deviation, sum, median absolute deviation, coefficient of variation, kurtosis, skewness
* **Most frequent values**
* **Histogram**
* **Correlations** highlighting of highly correlated variables, Spearman, Pearson and Kendall matrices
* **Missing values** matrix, count, heatmap and dendrogram of missing values
* **Text analysis** learn about categories (Uppercase, Space), scripts (Latin, Cyrillic) and blocks (ASCII) of text data.
* **File and Image analysis** extract file sizes, creation dates and dimensions and scan for truncated images or those containing EXIF information.

## INSTALL IT BY :-

`pip install pandas_profiling`
