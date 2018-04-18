1. Types of data
    a. string
    b. integer
    c. date
    d. float
    e. float

2. A text file works well if you only need to conduct a simple word search on a data set. A database is ideal when your data needs to be manipulated and queried in a more complex way.

3. SQL is a declarative language, whereas other programming languages are procedural. This means that a programmer doesn't need to write out instructions re: how the database should execute queries. A programmer only needs to give SQL the query parameters and the database will find the most efficient way to return the results.

4. The database system organizes data into distinct units, allowing a user to easily search for information. SQL commands give users the flexibility to aggregate relevant data to answer questions.

5. A **table** is the largest organizational unit in a database. It's made up of rows and columns and is used to store and organize data. A **row** represents each individual record stored in a database. For example, a record consists of all data associated with an individual user ID. A **column** represents the different types of values stored for each record (i.e., username, email). A **value** is any piece of data stored in the database. For example, each email address in a database represents a value.

6. Three data types that can be used in a table are: strings, integers, and floats.

7. English descriptions of queries:
    a. Return all date and amount columns from the Payments table.

    b. Return all amounts from the Payments table where the amount value is greater than 500.

    c. Return all rows from the Payments table where the payee value is equal to 'Mega Foods'.

8. SQL queries for the `users` table.
    a. SELECT email, sign-up date FROM users WHERE name = 'DeAndre Data';
    b. SELECT userid FROM users WHERE email = 'aleesia.algorithm@uw.edu';
    c. SELECT * FROM users WHERE userid = 4;
