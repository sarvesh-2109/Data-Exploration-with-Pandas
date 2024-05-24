# Data Exploration with Pandas.ipynb

This Jupyter notebook contains Python code for data exploration using the Pandas library. The notebook was originally created in Google Colab.

## Overview

- The dataset used in this notebook is "salaries_by_college_major.csv".
- The notebook explores various aspects of the dataset, including data cleaning, analysis, and visualization.

## Contents

1. **Loading the Dataset**: The notebook starts by loading the dataset into a Pandas DataFrame.
2. **Exploratory Data Analysis**:
   - Displaying basic information about the dataset such as shape, column names, and missing values.
   - Viewing the first and last few rows of the dataset.
3. **Data Cleaning**:
   - Dropping rows with missing values to create a clean DataFrame.
4. **Analysis**:
   - Identifying college majors with the highest and lowest starting median salaries.
   - Calculating the salary spread for mid-career salaries and identifying majors with the lowest and highest risk.
   - Identifying majors with the highest potential salary (90th percentile).
5. **Grouping and Aggregation**:
   - Grouping the data by a categorical variable ('Group') and performing aggregation to calculate the mean of numeric columns within each group.

## Code Explanation

The Python code in this notebook performs the following tasks:
- Loading the dataset using Pandas `read_csv()` function.
- Data cleaning by dropping rows with missing values.
- Calculation of statistics such as minimum, maximum, and mean salaries.
- Sorting and filtering the data to identify specific categories or trends.
- Grouping the data by a categorical variable and performing aggregation operations.

The code is well-commented and organized into sections, making it easy to understand and follow.

## Usage

You can run this notebook in any Python environment that supports Jupyter notebooks, such as Google Colab, JupyterLab, or Jupyter Notebook. Simply upload the dataset file and execute the code cells to perform data exploration and analysis.

```python
# Execute the code cells in the notebook to perform data exploration with Pandas
