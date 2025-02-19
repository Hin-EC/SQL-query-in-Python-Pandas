# SQL-query-in-Python-Pandas

This project demonstrates how to run SQL queries using **Python Pandas**. The project is a conceptual guide where we simulate SQL query operations in Pandas DataFrames. It follows the traditional SQL query sequence, which includes the steps:

- **FROM** and **JOIN**
- **WHERE**
- **GROUP BY**
- **HAVING**
- **SELECT**
- **DISTINCT**
- **ORDER BY**
- **LIMIT** and **OFFSET**

The project contains a Jupyter notebook file that explains each SQL step, along with code examples and illustrations.

## Project Overview

In this project, I used **Pandas** to replicate various SQL operations on datasets. The goal is to show how these SQL operations can be achieved without an actual SQL database by using Pandas' DataFrame capabilities. The project is aimed at helping those familiar with SQL but new to Python and Pandas see the similarities between SQL and Python data manipulation.

## Features

- **SQL Query Simulation**: Simulate SQL queries using Pandas.
- **Data Filtering**: Use `WHERE` and `HAVING` to filter data.
- **Grouping**: Implement `GROUP BY` and aggregate data.
- **Sorting**: Sort results using `ORDER BY`.
- **Limit**: Use `LIMIT` and `OFFSET` for pagination.
- **Distinct Selection**: Perform distinct selections with `DISTINCT`.


## SQL Steps Covered

### 1. **FROM and JOIN**

- Learn how to load data and join multiple dataframes using Pandas' `merge()` method.

### 2. **WHERE**

- Apply conditional filtering to DataFrames similar to the `WHERE` clause in SQL.

### 3. **GROUP BY**

- Use `groupby()` to group data by specific columns and perform aggregation functions such as `sum()`, `mean()`, etc. This simulates SQL's `GROUP BY` clause, where you can group the data based on one or more columns and then apply aggregate functions to each group.

### 4. **HAVING**

- After performing a `GROUP BY` operation, use the `HAVING` condition to filter the results based on the aggregated values. In SQL, the `HAVING` clause is used to filter grouped data after the aggregation, whereas in Pandas, you can apply a filter **after** grouping and aggregation using conditions on the aggregated results. The key distinction is that in SQL, the `WHERE` clause is applied **before** `GROUP BY`, while in Pandas, filters can be applied **before** or **after** the `groupby()`, depending on the specific use case.



### 5. **SELECT**

- Select specific columns from the DataFrame, mimicking the `SELECT` operation in SQL.

### 6. **DISTINCT**

- Extract unique values from columns using `drop_duplicates()` in Pandas.

### 7. **ORDER BY**

- Sort the DataFrame rows using `sort_values()` to replicate SQL's `ORDER BY` clause.

### 8. **LIMIT and OFFSET**

- Use `head()` and `iloc[]` to limit the number of rows and offset the results.

## Illustration

Here’s a screenshot illustrating how SQL queries are translated to Pandas operations:
![image](https://github.com/user-attachments/assets/6aae0ab7-194c-42b5-90ba-5488d64cd5a9)



## Requirements

- **Python** (3.x recommended)
- **Pandas** library
- **Jupyter Notebook** or compatible notebook environment

