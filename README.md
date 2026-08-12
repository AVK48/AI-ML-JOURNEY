# Pandas Basics (`pandas1.ipynb`)

## Overview
This notebook is part of my Machine Learning Engineer journey. It serves as an introductory guide and reference for basic data manipulation and analysis using the **Pandas** library in Python. 

## Topics Covered
Throughout this notebook, the following core Pandas concepts are explored:

*   **Loading Data:** Reading data from CSV files using `pd.read_csv()` and handling different parsing parameters like `sep`, `usecols`, and `dtype`.
*   **Data Inspection:** Getting a quick look at the dataset using `.head()`, `.tail()`, and understanding its structure with `.shape`, `.columns`, `.index`, and `.dtypes`.
*   **Data Structures:** Differentiating between Pandas two main data structures: `DataFrame` (2D) and `Series` (1D).
*   **Creating DataFrames:** Building a DataFrame from scratch using a standard Python dictionary.
*   **Data Selection:** Subsetting specific columns and extracting specific Series from a larger DataFrame.
*   **Basic Statistics:** Applying quick statistical summaries using `.mean()` and `.describe()`.
*   **Data Filtering:** Querying the DataFrame using:
    *   Relational operators (`>`, `==`, `!=`)
    *   Logical operators for multiple conditions (`&` for AND, `|` for OR)
    *   The `.isin()` method and its negation (`~`) to filter by a list of values.
*   **Data Sorting:** Organizing and ordering the dataset using `.sort_values()` (both ascending and descending).

## Prerequisites
To run or experiment with this notebook, you will need:
*   Python 3.x
*   Pandas (`pip install pandas`)
*   Jupyter Notebook or Google Colab

## Getting Started
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/AVK48/AI-ML-JOURNEY.git](https://github.com/AVK48/AI-ML-JOURNEY.git)
