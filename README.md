The commands that we used in this project:

- pd.read_csv - To import the CSV file in Jupyter notebook
- head() - It shows the first N rows in the data (by default, N=5)
- shape - It shows the total no. of rows and no. of columns of the dataframe
- df.isnull( ).sum( ) - It detects the missing values from each column of the dataframe.
- fillna() - To fill the null values of a column with some particular value
- value_counts - In a column, it shows all the unique values with their count. It can be applied to a single column only.
- isin() - To show all records including particular elements
- apply() - To apply a function along any axis of DF

Tasks:

1. Data Cleaning  - Find all Null Values in the dataset. If there is any null value in any column, then fill it with the mean of that column.
2. Value Counts - Check what are the different types of Make are there in our dataset. And, what is the count (occurrence) of each Make in the data ?
3. Filtering  - Show all the records where Origin is Asia or Europe.
4. Removing unwanted records  - Remove all the records (rows) where Weight is above 4000.
5. Applying function on a column - Increase all the values of 'MPG_City' column by 3.
