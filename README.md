# Chinook-Analysis
Chinook is a sample SQLite database which I used to perform some analysis.
This repository conatains the sample database and the code to the queries I wrote.

## Requirements 
To run SQL queries on your jupyter notebook, you first need to install ipython sql package by runing this line of code `! conda install -yc conda-forge ipython-sql`. 

To connect to the database you need to run the follwowing lines off code:
* %%capture
* %load_ext sql
* %sql sqlite: ///chinook.db

If you want to run the queries using pandas like I did, you can install python sqlite3 package using `pip install sqlite3` in your command line.

