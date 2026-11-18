---
title: "Connecting to Databases"
label: ch-03
description: "Sabor Miami outgrows its spreadsheets, and trucks, events, customers and orders now live in a database."
---

# Connecting to Databases

:::{important}
Preview: this chapter is being written. Here is what it will cover.
:::

## Purpose

Sabor Miami outgrows its spreadsheets, and trucks, events, customers and orders now live in a database. You will reconnect what you know about tables, keys and SQL to Power BI, connect to the Sabor Miami database, run a short SQL statement from Power BI, and check that the loaded tables and relationship lines look right.

## Learning objectives

By the end of this chapter you will be able to:

- Explain what a database holds that a flat file does not, and name a primary key and a foreign key in two Sabor Miami tables.
- State the four things Power BI needs to connect (server, database, user name, password) and what a missing connector looks like.
- Connect Power BI Desktop to the Sabor Miami database and load more than one table from the Navigator.
- Run a SELECT statement with WHERE and ORDER BY from Power BI and explain when to filter at the source.
- Check row counts and look in Model view for relationship lines.

## In this chapter

1. **Why a database?** A database keeps related tables together and lets them point at each other through keys.
2. **Keys and relationships: the part you already know.** The primary key names a row; the foreign key is that name written in another table.
3. **Connect Power BI to MySQL.** Server, database, user, password, and a connector installed first. If any piece is missing, the door stays shut.
4. **Ask the database a question: SQL inside Power BI.** Filter at the source when you know exactly what you need; filter in Power Query when you want every step visible.
5. **Choose tables, load, and look at the model.** Load the tables the question needs, check the row counts, and look in Model view for relationship lines.

## Try This ideas

Each section ends with a short "Try This" activity. A few of the ideas:

- **Why a database?** From a paper receipt, sort the facts into "belongs with the truck" and "belongs with the order". Draw three boxes and name the key that links them.
- **Keys and relationships: the part you already know.** In the data dictionary, find the primary key of Trucks and the foreign key in Orders that points to it. Say in a sentence why the truck name makes a poor key.
- **Connect Power BI to MySQL.** Open the MySQL window and say what each box asks for. Say what you would check first if the connection failed. Do not save a password.
- **Ask the database a question: SQL inside Power BI.** Run `SELECT * FROM` one table. Add a WHERE, then an ORDER BY. Compare the Power BI row count with the count your SQL tool reports for the same statement.
- **Choose tables, load, and look at the model.** Load three related tables. Open Model view and describe what you see. Did lines appear? If not, which key would you connect first?

The chapter closes with a longer capstone Try This (about 18 minutes): load the Sabor Miami database.

## Resources

Microsoft Learn pages for this chapter:

- [Get Data in Power BI (training module)](https://learn.microsoft.com/en-us/training/modules/get-data/)
- [Create and Manage Relationships in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-create-and-manage-relationships)
- [Power Query MySQL database connector](https://learn.microsoft.com/en-us/power-query/connectors/mysql-database)
- [Import data from a database using native database query](https://learn.microsoft.com/en-us/power-query/native-database-query)
- [Data sources in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-data-sources)
