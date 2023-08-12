---
title: Database dictionary
---
# Database dictionary
This article describes how to create a database dictionary for a relational database.
Relational databases store data in tables. The goal of the database dictionary is to provide a detailed description for each table in the database - its purpose, structure, and attributes. The attributes include table columns (also called fields), column descriptions, and constraints.

## Collect data
Option 1
If you have access to the database, you can reverse engineer the database schema to have an overview of all tables in the database. The reverse engineered schema should provide the information like table name, columns, data types, and constraints. 
One thing you can't reverse engineer is the table's purpose. Sometimes, the purpose is clear when you look at the table. If not, ask a subject matter expert (SME) for clarification.

Option 2
If you don't have access to the database, ask a SME or a database administrator to retrieve the information you need.