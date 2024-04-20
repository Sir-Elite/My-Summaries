### A few key points about data stored in SQL databases:
* Data in databases is stored in tables that can be thought of just like a bunch of Excel spreadsheets.
* All the data in the same column must match in terms of data type. The entire column is considered either quantitative, discrete, or as some sort of string. This means if you have one row with a string in a particular column, the entire column might change to a text data type. This can be very bad if you want to do math with this column!
* Consistent column types are one of the main reasons working with databases is fast, even with large databases.

### Most popular SQL statements to understand:
1. CREATE TABLE is a statement that creates a new table in a database.
2. DROP TABLE is a statement that removes a table in a database.
3. SELECT allows you to read data and display it. This is called a query.
