---
title: How to document a database
---
# How to document a relational database

## Overview
This artile provides basic guidelines for documenting relational databases using a PostgreSQL database as an example.

## Prerequisites
If you want to follow along with the examples in this article, you'll need to install the following:
- [PostgreSQL](https://www.postgresql.org/download/)
- [pgAdmin](https://www.pgadmin.org) or any other database administration tool that supports PostgreSQL.
- [Sample DVD rental database](https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/).

Also, if you have no experience with relational databases, you might want to learn some basics for better understanding of this article. For example:
- [What is a relational database?](https://cloud.google.com/learn/what-is-a-relational-database) by Google.
- [Relational database](https://en.wikipedia.org/wiki/Relational_database) on Wikipedia.  

## What is a database documentation?
Database documentation usually consists of:
- A database dictionary, which describes all tables that exist in a database (each table's columns, data types, keys, nullability). It can also describe views, stored procedures etc.
- An entity relationship diagram (which provides a high-level view of all tables and the relationships between them).

### Database dictionary


### Entity-relationship diagram


BELOW ARE SOME DRAFTS THAT MIGHT BE USEFUL

[Crow's foot notation](https://en.wikipedia.org/wiki/Entity–relationship_model#Crow's_foot_notation)

### Insert an image using JSX
For details, see [Static Assets](https://docusaurus.io/docs/static-assets).
<img src={require('@site/static/img/postgres_public.png').default} width="500" height="500"/>


## Database dictionary structure
Database dictionaries usually consist of the following sections. Click on a section name to go to a detailed description.
- Database overview
- Entity relationship diagram
- Tables
- Views (optional)
- Stored procedures (optional)

### Database overview
Provide general information about the database: name (both logical and physical if they are different), business purpose, important notes?

### Entity relationship diagram

### Tables
Each table description includes:
- Table name
- Table description (business or functional purpose)
- Indexes (optional)
- Column names (or fields)
- Column attributes:
    - Data type
    - Nullable (Yes/No)
    - Column description (business or functional purpose)

### Views (optional)

### Stored procedures (optional)
