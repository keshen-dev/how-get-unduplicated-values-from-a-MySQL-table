# how get unduplicated values from a MySQL table
To get unduplicated values from a MySQL table, you can use the DISTINCT keyword in your query. Here's an example:

```
SELECT DISTINCT column_name FROM table_name;
```
Replace column_name with the name of the column you want to retrieve unduplicated values from, and table_name with the name of the table you want to query.

For example, if you have a table named users with a column named email, and you want to retrieve all unique email addresses, you can use the following query:

```
SELECT DISTINCT email FROM users;
```
This will return a list of all unique email addresses from the users table, with any duplicate email addresses removed.
