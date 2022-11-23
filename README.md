# Chinook-Analysis
Chinook is a sample SQLite database which I used to perform some analysis.
This repository conatains the sample database and the code to the queries I wrote.

## Python Requirements 
To run SQL queries on your jupyter notebook, you first need to install ipython sql package by runing this line of code `! conda install -yc conda-forge ipython-sql`. 

To connect to the database you need to run the follwowing lines off code:
* %%capture
* %load_ext sql
* %sql sqlite: ///chinook.db

If you want to run the queries using pandas like I did, you can install python sqlite3 package using `pip install sqlite3` in your command line.

## R Requirments

* To connect to the database using R, you can install the RSQLite package with `install.packages("RSQLite")`
* You also need to install the DBI package to enable you run queries with R. run the command `install.packages("DBI")`.
* Finally you need the tidyverse group of packages so you can visualise your results using ggplot2. you can get it using `install.packages` too.

