
<h1><p style="text-align: center;">Exploratory Data Analysis (EDA) Project</p></h1> 

***
# Descriptions :
- A ``.json`` file containing a dataset consisting of 15919 rows and 54 columns is provided.
- This dataset, scraped from the on-line car trading company in 2019, contains many features of 9 different car models.
- The features (variables) of this dataset are too messy and distored.

# Step-by-step actions?
- Reading the ``.json`` file and assigning the dataset into a ``DataFrame`` using ``pandas``.
- Applying all aspects of the **EDA process** to the dataset.
    - Fix corrupt data formats,
    - Dealing with outlier and missing values,
    - Leaving the columns/rows that I find unnecessary as a result of my analysis,
    - To use visualization tools while doing all these operations.
- As a result, making the dataset ready to provide an appropriate input to ML models.
- Saving the cleaned dataset to a ``.csv`` file.

# Need to Study :
- ``.str.method``,
- ``.contains()``,
- ``.extract()``,
- ``.to_datetime()``,
- ``.get_dummies()``,
- ``.add_prefix()``,
- ``.sample()``,
- `regex`,
- ``.to_numeric()``,
- ``.isin()``,
- ``.corr()``.
