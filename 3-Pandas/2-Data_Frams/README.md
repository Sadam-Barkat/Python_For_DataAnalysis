# DataFrames in Pandas

DataFrames are a key data structure in Pandas, designed for working with structured data. They are similar to tables in a relational database or spreadsheets, allowing for easy data manipulation and analysis.

## Key Features

- **2D Data Structure**: A DataFrame consists of rows and columns, making it easy to store and manipulate data.
- **Labeled Axes**: Each row and column can have labels, which improves data accessibility and readability.
- **Data Alignment**: Automatically aligns data based on labels, which simplifies operations.

## Creating a DataFrame

You can create a DataFrame from various data sources, including lists, dictionaries, or external files.

```python
import pandas as pd

# Creating a DataFrame from a dictionary
data = {
    'Name': ['Sadam', 'Hussain', 'Haris'],
    'Age': [25, 30, 35]
}
df = pd.DataFrame(data)
git clone https://github.com/Sadam-Barkat/2-Data_Frams.git
