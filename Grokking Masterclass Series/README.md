# Grokking Relational Database Design: Masterclass Series

This repository contains a comprehensive set of study guides, practical code examples, and architectural challenges based on the book **Grokking Relational Database Design**. It is specifically tailored for .NET developers looking to bridge the gap between high-level C# application code and robust, high-performance SQL database architecture.

## Content Overview

The repository is organized into detailed study modules, each covering specific chapters of the database design lifecycle:

### Phase 1: Foundations

- **Chapter 1: Intro to Databases & SQL** – Tables, Rows, Columns, and Primary Keys.
- **Chapter 2: Related Tables** – Foreign Keys and the logic of table connections.
- **Chapter 3: Design Process** – Conceptual, Logical, and Physical design phases.

### Phase 2: Entity-Relationship (E-R) Modeling

- **Chapter 4: Entities & Attributes** – Defining "Nouns" and their properties (Simple, Composite, Derived).
- **Chapter 5: Relationships** – Cardinality (1:1, 1:M, M:M) and Crow's Foot notation.

### Phase 3: The Art of Normalization

- **Chapter 6: Normalization Part 1** – 1NF and 2NF: Eliminating repeating groups and partial dependencies.
- **Chapter 7: Normalization Part 2** – 3NF and BCNF: Eliminating transitive dependencies for the "Gold Standard."

### Phase 4: Implementation & Tuning

- **Chapter 8: Physical Design** – Indexing (B-Trees), Data Types, and Constraints.
- **Chapter 9: Views & Security** – Virtual tables and the principle of least privilege.
- **Chapter 10: Advanced Objects** – Transactions (ACID), CTEs, and Stored Procedures.
- **Chapter 11: Modern Apps** – Scaling, Caching (Redis), and Denormalization strategies.

### Phase 5: Maintenance & Future Trends

- **Chapter 12: Data Integrity & Recovery** – Backup strategies (RPO/RTO) and disaster recovery.
- **Chapter 13: NoSQL & Polyglot Persistence** – Integrating SQL with Document, Graph, and Key-Value stores.

## Practical Resources Included

- **SQL & .NET Cheat Sheet**: A quick-reference guide for SQL syntax and Entity Framework Core Fluent API mappings.
- **Final Mock Exam**: A 20-question comprehensive test to validate your understanding of all 13 chapters.
- **Production Checklist**: A "Best Practices" list for deploying databases to real-world environments.
- **Hands-on Challenges**: Includes a SQL "Mega-Store" audit and a C# Social Media architecture task.

## Getting Started for .NET Developers

The examples in this repository leverage:

- **.NET 8 / C# 12** features (Primary Constructors, Raw String Literals).
- **Entity Framework Core 8** for modern ORM mapping.
- **Dapper** for high-performance data access.
- **SQL Server** syntax for RDBMS-specific optimizations.

**Note**: This content is intended as a companion to the Grokking Relational Database Design textbook.
