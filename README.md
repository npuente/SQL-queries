# SQL-queries
## Introduction
This repository contains examples of SQL queries, which is an extension of Project 3 from the [Business Analytics Nanodegree](https://www.udacity.com/course/business-analytics-nanodegree--nd098) from Udacity. The [Chinook](https://github.com/npuente/SQL-queries/blob/master/chinook.db) database belongs to a music store and follows the following entity relationship diagram:
![alt text](https://github.com/npuente/SQL-queries/blob/master/Images/erd.png?raw=true)
The first 4 queries belong to the aformention project, however more complex queries were added aftewards.

## Results of the queries from the Udacity Project
The queries to obtain the following results can be seen in the following [link](https://github.com/npuente/SQL-queries/blob/master/Queries). They were coded using the [DB Browser for SQLite](http://sqlitebrowser.org/). The methodology used consists on developin a query whose results would answer a particular question. The data obtained will then be used to obtain a visualization that can be analyzed. This visualization is built in Excel using an extracted csv file for each query that can be found [here](https://github.com/npuente/SQL-queries/tree/master/data_from_queries).

### Query 1: What Sales Reps has the biggest number of accounts?
![alt text](https://github.com/npuente/SQL-queries/blob/master/Images/q1.png?raw_true)

Georgianna Chisholm has the most accounts with 15.
After the drop from 15 to 11 the amount of accounts is pretty even. While I am only showing the top 10 here when I ran the query without a limit Brandie Riva, Hilma Busick, and Arica Stoltzfus also had 10 accounts.
Note: the name of the Sales Reps was concatenated on a single data field using Excel, but this could be done directly on the query using the CONCAT function.

### Query 2: How many Sales Reps are there per Region?
![alt text](https://github.com/npuente/SQL-queries/blob/master/Images/q2.png?raw_true)

There are 21 reps in the Northeast, there are 10 reps in the Southeast and West, and there are 9 reps in the Midwest.

### Query 3: Which Accounts had the largest smallest order?
![alt text](https://github.com/npuente/SQL-queries/blob/master/Images/q3.png?raw_true)

CBS’s had the largest smallest order of $8648.07
These accounts do not waste the companies time with small orders.

### Query 4: What region had the highest total order amount?
![alt text](https://github.com/npuente/SQL-queries/blob/master/Images/q4.png?raw_true)

The Northeast had the highest total order amount at $7,744,405.36.

## Results of advanced queries (using subqueries).
### Query 5: What is the most popular music Genre for each country?
This is the least obtained:

![alt text](https://github.com/npuente/SQL-queries/blob/master/Images/q5.png?raw_true)

### Query 6: What are the track that have a song length longer than the average song length?
There are 494 songs with a length longer than the average song length. These are the first results

![alt text](https://github.com/npuente/SQL-queries/blob/master/Images/q6.PNG?raw_true)

### Query 7: Who is customer that has spent the most on music for each country?

