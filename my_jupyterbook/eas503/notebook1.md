# Creating a Normalized Database (3NF)

## Introduction

I am going to demonstrate how I normalized a dataset into a database designed in Third Normal Form (3NF). Using Python libraries like `pandas` and `sqlite3`, I transformed a dataset of mobile phone specifications into a fully normalized SQLite database. This approach enhances data integrity, consistency, and scalability for future analyses and querying.

---

## Step 1: Importing Libraries and Data

```python
import pandas as pd
import numpy as np

df_csv = pd.read_csv('mobile_prices.csv')
```

### What I Did:
- I used `pandas` and `numpy`, which are essential for data manipulation.
- The `read_csv` function allowed me to load the data from a CSV file (`mobile_prices.csv`) into a pandas DataFrame for easier processing.

