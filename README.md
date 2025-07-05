# Bank Database Management System

A SQL-based relational database system designed to manage core banking operations using **PostgreSQL**. This project demonstrates strong database design principles, including ER modeling, normalization, and the use of DDL/DML queries to build and interact with the system.

---

##  Features

- **ER Modeling**: Designed a comprehensive Entity-Relationship (ER) diagram to represent core banking entities and their relationships.
- **Normalization**: Transformed the ER model into a normalized relational schema to reduce redundancy and ensure data consistency.
- **PostgreSQL Implementation**: Created the full schema using DDL scripts and populated it with realistic sample data.
- **Optimized SQL Queries**: Wrote complex SQL queries to perform essential banking operations efficiently.
  
---

##  Project Files

- `ER_Diagram.pdf` – Entity-Relationship diagram of the system
- `Relational_Schema.pdf` – Table-wise schema with keys and attributes
- `Normalization_Proofs.pdf` – Step-by-step conversion to 1NF, 2NF, and 3NF
- `DDL_Scripts.sql` – Scripts to create tables and constraints
- `INSERT_Scripts.sql` – Sample data for testing and demonstration
- `Queries.sql` – Collection of essential and advanced banking queries

---

##  Example Queries Include:

- Retrieve all customers with active accounts
- Show recent transactions for a given account
- Calculate total balance across accounts
- Get branch-wise account statistics
- Join operations across customer, account, and transaction tables

---

##  Database Design Philosophy

The database was designed with the following goals in mind:
- Clear mapping from real-world banking concepts to relational schema
- Minimal redundancy using normalization
- Efficiency and clarity in data retrieval
