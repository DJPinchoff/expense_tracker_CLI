##Command Line Database Expense Tracking App##

Launch School Course 180: Interacting with a Database in Code

Combines Knowledge of Ruby and PostgreSQL to create a command line application that persists expenses with a row id, date of creation, amount of transaction, and memo. 

It has the following features:

- help
- add transaction
- delete transaction
- delete all transactions
- search transactions
- list transactions

1. To install, download zip from button above. 
2. Uncompress the files into a directory.
3. Open terminal and ```cd``` into the correct directory.
4. Type ```createdb expenses``` to create the postgresql database.
5. Type ```psql expenses < schema.sql``` to load in the correct schema to the database.
6. Then type ```./expense <command>``` where <command> is one of the features listed above.
