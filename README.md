# super_market

📊 Supermarket Sales Analysis using Pandas
This project demonstrates how to perform comprehensive data analysis using Pandas in Python. It involves cleaning, transforming, analyzing, and visualizing supermarket transactional data.

📌 Key Pandas Operations Covered
This analysis project highlights a range of operations using the Pandas library:

1. 📥 Data Loading
pd.read_csv() to import data

Understanding data structure with .head(), .tail(), .info(), .describe()

2. 🧼 Data Cleaning
Checking for missing values with .isnull().sum()

Converting data types (e.g. pd.to_datetime(df['Date']))

Removing duplicates

Renaming columns for consistency (df.rename())

3. 📐 Data Transformation
Creating new columns (e.g. Hour, Weekday, Revenue)

Parsing dates and times (dt accessor)

Changing column data types (astype())

4. 🔎 Filtering and Selection
Conditional filtering using boolean indexing (df[df['Gender'] == 'Female'])

Multi-condition filtering with & and |

Column selection using df[['City', 'Total']]

5. 📊 Grouping and Aggregation
groupby() to calculate metrics like average sales, quantity, and gross income by:

City

Product Line

Gender

Payment Method

Aggregation functions: .mean(), .sum(), .count(), .agg()

6. 📈 Sorting and Ranking
Sorting results using .sort_values()

Finding top-N categories with .nlargest() / .nsmallest()

7. 🔁 Pivot Tables
Creating Excel-style pivot tables using pd.pivot_table()

8. 🪄 Data Visualization (Optional with Pandas)
Using .plot() with Matplotlib backend

Example plots:

Sales trends over time

Product line comparison

Revenue by customer type

9. 🧾 Exporting Results
Save cleaned or summarized data with .to_csv()

