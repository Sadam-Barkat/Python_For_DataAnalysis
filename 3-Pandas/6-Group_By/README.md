# Group By in Pandas

This section focuses on the `groupby` method in Pandas, which allows you to group data based on one or more columns and perform operations on these groups.

## Key Features

- **Group Data**: Aggregate data based on one or more columns.
- **Apply Functions**: Perform calculations on grouped data.

## Grouping Data

You can group data using the `groupby()` method.

```python
import pandas as pd

# Sample DataFrame
data = {
    'Category': ['A', 'B', 'A', 'B', 'A'],
    'Values': [10, 20, 30, 40, 50]
}

df = pd.DataFrame(data)

# Grouping by 'Category'
grouped = df.groupby('Category')
git clone https://github.com/Sadam-Barkat/6-Group_By.git
