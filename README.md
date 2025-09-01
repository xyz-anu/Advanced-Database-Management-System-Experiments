# Advanced Database Management Systems (ADBS) - Course Projects & Experiments

---

## Welcome to My ADBS Journey!

This repository contains a collection of experiments, assignments, and projects completed as part of the **Advanced Database Management Systems** course. Through this collection, I explored a wide range of database technologies, from relational databases and PL/SQL programming to XML, MongoDB, and PostgreSQL advanced features.

Whether you are a beginner or someone looking to deepen your database knowledge, this repository serves as a comprehensive guide to practical learning in database management systems.

---

# Table of Contents

- [Course Summary](#course-summary)  
- [Experiments Overview](#experiments-overview)  
- [Projects Showcase](#projects-showcase)  
- [How to Use This Repository](#how-to-use-this-repository)  
- [Contact](#contact)  

---

## Course Summary

Throughout this course, I learned and applied several crucial database concepts and technologies, including:

### Core Concepts & SQL

- **Relational Database Design:** Understanding entities, attributes, and relationships. Designing Entity-Relationship (ER) diagrams.  
- **SQL Programming:** Creating tables, inserting, updating, deleting data, and complex querying (joins, aggregate functions).  
- **PL/SQL Programming:** Writing **procedures**, **functions**, **triggers**, and **packages** for automated and dynamic database operations.  
- **Object-Relational Features:** Implementing user-defined types, inheritance, and nested tables in ORDBMS.  
- **Dynamic SQL & Embedded SQL:** Creating flexible and dynamic queries in PL/SQL and embedding SQL queries in application code (Java).  

### Advanced Topics

- **Database Links:** Setting up links between remote databases for distributed querying.  
- **XML in Databases:** Designing XML documents, Document Type Definitions (DTD), and XML Schemas. Writing **XQuery** and **XPath** expressions for querying XML data.  
- **NoSQL with MongoDB:** Performing CRUD operations, working with arrays, and executing aggregation pipeline queries in a document-based database system.  
- **PostgreSQL Specific Features:** Utilization of `SERIAL` type for auto-increment, JSONB data types, indexing strategies, and advanced joins (FULL OUTER JOIN).  

### Practical Skills Gained

- Designing structured and normalized databases.  
- Implementing real-time donor matching and dynamic heirloom management systems.  
- Utilizing embedded and dynamic SQL for improved database interfacing with applications.  
- Using MongoDB for schema-less data management and aggregate analysis.  
- Handling XML data storage, validation, and querying.  

---

## Experiments Overview

### PL/SQL Programming

- Writing **procedures** to automate data manipulations (insert, update, delete).  
- Defining **functions** for reusable database logic.  
- Implementing **cursors** to iterate over query results.  
- Creating **triggers** for data validation and integrity enforcement.  
- Managing **sequences** for automatic primary key generation.  
- Exploring **packages** for modular programming.  
- Executing **dynamic SQL** commands for flexible database operations.  

### ORDBMS (Object-Relational DBMS)

- Defining **user-defined types** and **nested attributes** for complex data modeling.  
- Implementing **type inheritance** for employee classifications (full-time and part-time).  

### XML and XQuery

- Constructing **well-formed XML documents** to represent structured data.  
- Defining **DTD and XML Schema** for XML validation.  
- Querying XML datasets using **XQuery and XPath** expressions for real-world queries on catalogs, menus, and botanical data.  

### MongoDB

- Creating **databases and collections** in MongoDB.  
- Implementing **CRUD operations** with BSON document structure.  
- Working with **arrays** in MongoDB documents: inserting, updating, slicing, and deleting elements.  
- Performing **aggregation frameworks** for group-wise computations like sum, average, max, and min values.  
- Writing regex queries for pattern matching on document fields.  

### Embedded SQL & Java

- Writing Java programs embedding SQL queries to connect, query, update, and delete database records.  

---

## Projects Showcase

### 1. Blood Donation Management System (Using PL/SQL & Oracle)

- **Objective:** Facilitate quick matching between blood donors and requests based on **blood group compatibility**, location, and donation recency.  
- **Database Design:** Relational tables for *Donor*, *Blood_Type*, *Request*, and *Match_Log*.  
- **Key Features:** Stored procedures for donor detail update, donor listing by blood group, request status checks, and marking requests fulfilled.  
- **Tools:** PL/SQL procedures, triggers, and reporting queries simulating real-time blood allocation.  

---

### 2. Family Heirloom Management System (Using PostgreSQL)

- **Objective:** Track historical family heirlooms, ownership history, appraisal reports, current owners, and resolve disputes.  
- **Database Design:** Tables for *Family Members*, *Heirlooms*, *Ownership History*, *Appraisal Reports*, and *Disputes*.  
- **Key Highlights:** Use of PostgreSQL **SERIAL type**, JSONB for story data, foreign key constraints, and complex joins.  
- **Operations:** Insert, update, delete commands with focus on ownership transfer and dispute tracking.  

---

## How to Use This Repository

1. **Browse Experiments Folder:** Experiment-wise SQL and PL/SQL scripts with explanations.  
2. **Explore Projects Folder:** Complete project scripts and reports with ER diagrams and sample data.  
3. **Run Scripts:** Use an Oracle or PostgreSQL environment for SQL/PLSQL scripts and MongoDB for NoSQL scripts.  
4. **Learn by Example:** Inspect code for creating types, procedures, triggers, and dynamic queries.  
5. **Adapt for Your Needs:** Modify scripts for your database scenarios or educational purposes.  

---

## Contact

- **Creator:** Anushka Harshavadan Nevgi  
- **LinkedIn:** [[Anushka Nevgi](https://www.linkedin.com/in/anushka-nevgi/)]  
- **Email:** anushkanevgi2910@gmail.com  

---

Thank you for exploring my Advanced Database Systems repository!  
Feel free to fork, star, or raise issues for any questions or suggestions.

---

*Keep learning and happy querying!*  
**- Anushka H. Nevgi**

