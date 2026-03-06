# Experiment-10
# Aim
Study of Pandas Library.
# Theory
1. Pandas is a powerful Python library used for data analysis and data manipulation. It helps work with structured data (tables, spreadsheets, CSV files, etc.) easily.
2. Main data structures in pandas-Pandas mainly provides two data structures:Series-A Series is a one-dimensional labeled array (similar to a column in a table) and DataFrame-A DataFrame is a two-dimensional table with rows and columns (like Excel).
3. Features of Pandas-easy data cleaning, handling missing values, data filtering and sorting, reading files (CSV, Excel, JSON), statistical analysis and fast data processing.
4. Applications of Pandas-data analysis, machine learning preprocessing, financial data analysis, scientific research and business analytics.
5. The keyword as pd creates a short alias pd, which is used to access pandas functions easily.Itstores in the series, and pandas automatically assigns index values 0, 1, 2, 3.
6. Create DataFrame-This is a comment in Python used to describe the purpose of the code. Comments are not executed.
7. df = pd.DataFrame(data)-This creates a DataFrame from the dictionary using the pandas library and stores it in the variable df.
8. df.shape-This displays the shape of the DataFrame, i.e., the number of rows and columns (rows, columns).
9. df.ndim-This shows the number of dimensions of the DataFrame. A DataFrame has 2 dimensions (rows and columns).
10. df.size-This returns the total number of elements in the DataFrame (rows × columns).
11. df.columns-This displays the names of all columns present in the DataFrame.
12. df.dtypes-This shows the data type of each column, such as integer, float, or object (string).
13. df["Name"]-This command accesses the “Name” column from the DataFrame and returns it as a Series.
14. df.head() – Displays the first 5 rows of the DataFrame by default.
15. df.tail() – Displays the last 5 rows of the DataFrame by default.
16. df.loc[0] – It is used to access and display the row with index label 0 from the DataFrame. loc is used to access specific rows.
17. df.iloc[1,1] – It is used to access the element located at the 2nd row and 2nd column of the DataFrame using integer position indexing.
18. df["Grade"] = [...] – This command adds a new column named "Grade" to the DataFrame and assigns the given values to each row.
19. df.iloc[0,1] = 81 – This command modifies the value at the 1st row and 2nd column of the DataFrame to 81 using integer position indexing.
20. df.drop("Grade", axis=1, inplace=True) – This command removes the column "Grade" from the DataFrame permanently (axis=1 means column, inplace=True updates the original DataFrame).
21. df.drop("Grade", axis=1, inplace=True); df – This command removes the "Grade" column from the DataFrame (axis=1 for column) and displays the updated DataFrame.
22. new_df = df.drop("Name", axis=1); display("the new column is:", new_df) – This command creates a new DataFrame by removing the "Name" column from df and then displays the resulting DataFrame.
23. Statistical operations- Mean- gives the mean of all values, Max- gives the maximaum value of the column and Min- gives the minimum value of the column.
24. df[df["Marks"]>80]-This command is used for filtering i.e to get information whose marks are more than 80.
# Conclusion 
In pandas, using Python, data can be easily organized, analyzed, and manipulated using structures like Series and DataFrame, making it a powerful tool for efficient data handling and analysis.
