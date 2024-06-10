### Create Datasets with SQL (Part 2)
The repo has 1) to_analyze has the questions  2) You will find the db_diagram 3) Actual db with data (market.db)  4) Notebook (Questions.ipynb)

In the notebook, we will be using duckdb as our DBengine.  Moving out of sqlite - (left outer join only restriction is no more), we are progressing. (More to talk abt duckdb later) .    
We connect to market_db, using duckdb , as if it is a duckdb's database, fire SQL queries, and return data as a pandas dataframe (for display purposes).
