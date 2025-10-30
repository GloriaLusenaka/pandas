# pandas
This is a pandas crash course to get you started
Pandas is an open-source library providing high-performance, easy-to-use data structures and data analysis tools for Python.

## Key Features
DataFrame: Primary data structure (like a spreadsheet)

Series: 1D labeled array

Data manipulation:
Filtering, grouping, merging

Handling missing data

Time series functionality

I/O operations: Read/write CSV, Excel, SQL, and more

Basic Operations
Importing
python
import pandas as pd
Creating DataFrames
python
# From dictionary
data = {'Name': ['Alice', 'Bob'], 'Age': [25, 30]}
df = pd.DataFrame(data)
Reading Data
python
df = pd.read_csv('filename.csv')
df = pd.read_excel('filename.xlsx')
Common Operations
python
df.head()        # First 5 rows
df.info()        # Data types and missing values
df.describe()    # Statistical summary
df['column']     # Select column
df[df['age'] > 25]  # Filter rows
Installation
bash
pip install pandas
Perfect for data cleaning, transformation, and analysis tasks!

