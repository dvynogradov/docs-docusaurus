---
title: Documenting relational databases
---

# How to document relational databases
This article provides basic guidelines for documenting relational databases. It uses a [PosgreSQL](https://www.postgresql.org) database as an example. Nevertheless, these guidelines apply to all relational databases.

:::tip
If you are new to relational databases, see [What is a relational database?](https://cloud.google.com/learn/what-is-a-relational-database) by Google or [Relational database](https://en.wikipedia.org/wiki/Relational_database) on Wikipedia.
:::

 




## Step 1. Creating sample tables using PostgresSQL
If you're not interested, you can skip ahead to Step 2. Documenting the sample tables.
Let's create a sample database with a couple of tables that will serve as an example for our database dictionary.


## Create a new database

## Create tables

## ERD

DBeaver uses [IDEF1X](https://en.wikipedia.org/wiki/IDEF1X) notation by default, other notations are not supported as of this writing.
You can use other database modeling tools that support other notations. For example, [Crow's foot notation](https://en.wikipedia.org/wiki/Entity–relationship_model#Crow's_foot_notation) is widely used in database modelling.  
The ERD for our library tables may look as follows (IDEF1X notation).

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
