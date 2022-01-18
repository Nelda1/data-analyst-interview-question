# Business Data Analyst Interview Question 

## Introduction

A startup called Rocket Spark wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The Marketing  Team is particularly interested in understanding what songs users are listening to. 
They'd like a Business Data Analyst to provide insights and analytics into the data they have.This exercise has been setup to test your SQL knowledge and Analytical skillsets.
## Files

The project includes 2 files:


1. `queries.ipynb` this file contains all the questions the rocket spark has for you and where you are going to fill in corresponding sql queries.
2. `README.md`  provides an introduction  and all you need to know abount this practical test.

## Database Schema

**Note** The database called `rocket_spark` is postgres RDMS that has all the tables and data for you to begin this exercise.It is star schema that has been modeled and optimized for analytics.
`songplays` is the fact table and while `users, artists, songs, time` are dimensions tables.  

### Tables in the Database

1. `users`  holds all the names of users using the music app

Column Name  | Column Type
------------- | -------------
user_id  | integer
first_name  | character varying
last_name   | character varying
gender      | character varying
users       | character varying
level       | character varying

2. `artists` 

Column Name  | Column Type
------------- | -------------
artist_id   | character varying
name        | character varying
location    | character varying
latitude    | character varying
longitude   | character varying

3. `time`

Column Name  | Column Type
-------------| -------------
start_time  | timestamp without time zone
hour        | smallint
day         | smallint
week        | smallint
month       | smallint
year        | smallint 
weekday     | smallint+

4. `songplays`

Column Name  | Column Type
------------- | -------------
song_play_id | integer
start_time   | character varying
user_id      | character varying
level        | character varying
song_id      | character varying
artist_id    | character varying
session_id   | integer
location     | character varying
user_agent   | character varying

5. `songs`

Column Name  | Column Type
------------- | -------------
song_id     | character varying
title       | character varying
artist_id   | character varying
year        | smallint
duration    | double precision


#### Instructions

Steps to complete this exercise:

1. The `queries.ipynb` notebook has a predefined script that connects to a remote postgres database which contains all the data you need to carry out this exercise.
3. Run the first two cells to open connection to the `rocket spark` database.
4. There are five questions: respond to all the questions  with sql queries and python scripts that will be tested to assess your response.
5. Once you are done  run the last cell to close connection to the database

#### Expections

1. Ensure your all your sql statements are running without any errors.
2. Insert comments where neccesary to justify and explain your approach.
3. Make use of Subqueries, Aggregations, Conditionals, JOINS,  SQL functions and any other SQL(DML) where neccesary and relevant to the question being asked.
4. Note for some questions you may need to write more than one sql statement to arrive to the answer and feel free to show all of those steps in your notebook.
5. Use any workspace of your choice -- jupyter notebooks , googlecolab, pycharm etc however once your are done push your work to your github repository where your work can be accessed.
6. **_Optional_** Visualize your data using matplotlib,pandas and any other libraries


  ****************************************** **Good Luck** ******************************************