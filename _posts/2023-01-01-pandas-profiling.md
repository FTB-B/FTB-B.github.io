---
title: "Pandas Profiling"
category: posts
excerpt: "Python EDA"
---

Pandas Profiling is an open-source Python library that generates interactive reports from pandas DataFrame objects. It's a fast and easy way to perform an exploratory data analysis (EDA) on a dataset.

In a single line of code, the library provides insights about your data including:
    
    1. Descriptive statistics - Provides basic information about the dataset like the number of variables, observations, missing values, duplicate rows, etc.
    
    2. Variable properties - Detailed information about each column/variable in the DataFrame such as data type, distinct values, missing values, mean, median, mode, standard deviation, minimum value, maximum value, quartiles, etc.
    
    3. Correlations - It will show the correlation between different variables in various formats (Pearson's, Spearman's, Kendall's, etc). It's beneficial when you want to understand the relationships between different variables.
    
    4. Histogram - Distribution of each variable is also presented in a histogram which makes it easy to understand the distribution of values for each column.
    
    5.  Heatmaps - These are useful to identify missing values and the correlation between different variables.
    
    6.  Sample of dataset - Displays the first and last rows of the DataFrame.

 
```python
    import pandas as pd
    from pandas_profiling import ProfileReport

    # Load a DataFrame
    df = pd.read_csv('your_dataset.csv')

    # Create the ProfileReport object
    profile = ProfileReport(df, title='Pandas Profiling Report', explorative=True)

    # Save the report as an HTML file
    profile.to_file("your_report.html")
 ```


