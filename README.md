# SQL cheatsheet

## Manipulation  
# SQL cheatsheet

## Manipulation  

```
CREATE TABLE celebs (id INTEGER, name TEXT, age INTEGER);
```

This `CREATE` statement creates a new table in the database named `celebs`. You can use the `CREATE` statement anytime you want to create a new table from scratch.

1. `CREATE TABLE` is a clause that tells SQL you want to create a new table. 


2. `celebs` is the name of the table. 


3. `(id INTEGER, name TEXT, age INTEGER)`is a list of parameters defining each column in the table and its data type. 

- `id` is the first column in the table. It stores values of data type `INTEGER`
- `name` is the second column in the table. It stores values of data type `TEXT`
- `age` is the third column in the table. It stores values of data type `INTEGER`



Add a row to the table. In the code editor type

```
INSERT INTO celebs (id, name, age) VALUES (1, 'Justin Bieber', 21);
```

To view the row you just created, under the `INSERT` statement type `SELECT * FROM celebs;`.

This `INSERT` statement inserts new rows into a table. You can use the `INSERT` statement when you want to add new records.

1. `INSERT INTO` is a clause that adds the specified row or rows. 
2. `celebs` is the name of the table the row is added to. 
3. `(id, name, age)` is a parameter identifying the columns that data will be inserted into. 
4. `VALUES` is a clause that indicates the data being inserted. 
`(1, 'Justin Bieber', 21)` is a parameter identifying the values being inserted.

- `1` is an integer that will be inserted into the `id` column
- `'Justin Bieber'` is text that will be inserted into the `name` column
- `21` is an integer that will be inserted into the `age` column



```
SELECT name FROM celebs;
```

`SELECT` statements are used to fetch data from a database. Here, `SELECT` returns all data in the `name` column of the `celebs` table.

1. `SELECT` is a clause that indicates that the statement is a query. You will use `SELECT` every time you query data from a database. 
2. `name` specifies the column to query data from. 
3. `FROM celebs` specifies the name of the table to query data from. In this statement, data is queried from the `celebs` table. 

You can also query data from all columns in a table with `SELECT`.

```
SELECT * FROM celebs;
```

`*` is a special wildcard character that we have been using. It allows you to select every column in a table without having to name each one individually. Here, the result set contains every column in the `celebs` table.

`SELECT` statements always return a new table called the *result set*.


## Queries  

## Aggregrate Functions  

## Multiple Tables
## Queries  

## Aggregrate Functions  

## Multiple Tables

