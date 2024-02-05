# Data-Engineering-Assessment

Data Engineering Assessment Coding Challenge

## Coding Challenge Objective

The objective of this coding challenge is to have a measure of the coding expertise and usage of good practices for Data Engineering.

The challenge is the following:

## API

By using following API:

Base URL: https://jsonplaceholder.typicode.com

- GET   /users
- GET   /posts
- GET   /posts/1
- GET   /posts/1/comments
- GET   /comments?postId=1

A usage example could be: GET https://jsonplaceholder.typicode.com/posts

### 1. Database Design and SQL DDLs

Create the SQL statements to create the tables of a database that will store the data from the API, it can be on any Relational Database (MySQL, Postgres or any other)

### 2. ETL Development

By using any Programming Language, read the data from the API endpoints, do neccesary transformations and load it into the database, you can use any framework or library (spark, hadoop, pandas or any other)

### 3. SQL Queries

Write the sql statements for:

1. Retrieve the userId that made most comments on all the Posts
2. Retrieve the number of comments per Post
3. Retrieve the longest post comment made on all the posts

### Deliverables

The deliverables should be the followings:

1. On a file named as "blog_post.sql", will be the SQL statements of 1.
2. On a folder named as "blog_post_etl", will be the coding files of 2.
3. On a file named as "blog_post_queries.sql", will be the queries of 3.

