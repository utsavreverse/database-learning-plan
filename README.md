# Database Learning

## Introduction
1. [What is a Database?](https://youtu.be/hRulZhTtUTg)
2. [DBMS vs RDBMS](https://youtu.be/E9AgJnsEvG4)
3. [SQL vs NoSQL](https://youtu.be/Q5aTUc7c4jg)
4. [Relational Database Introduction, Tables, Rows and Columns](https://youtu.be/OqjJjpjDRLc)
5. [Keys in RDBMS](https://youtu.be/_UZLrD_R0T4)

## SQL
1. [What is SQL?](https://youtu.be/Zqo-qNNMmdA)
2. [Data types in SQL](https://youtu.be/btjcNSOUTOg)
    - [Datatypes of postgreSQL](https://www.postgresql.org/docs/current/datatype.html)<br>
Note that all the vendors (postgreSQL, mySQL etc) of SQL have their own data types, but there are some common data types that are supported by all vendors, for more referance it's always good idea to refer the documantation of that vendor.

3. **SQL Constraints**
    - [Intro](https://youtu.be/-8bYtApJNos)
    - [Examples](https://youtu.be/KqBiGOdce74)
    - [Primary and Foreign Key constraints](https://youtu.be/MR0PK0qkCD8)

4. **Relationships in RDBMS**
    - [Introduction](https://youtu.be/4q-keGvUnag)
    - [Practical Implementation examples](https://www.devart.com/dbforge/sql/studio/sql-relationships.html)

5. **Data Definition Language (DDL)**
    - [DDL Introduction](https://youtu.be/CSX0OlOYWps?si=phyfOeXsuvJ3eiHA)
    - [DDL CREATE](https://youtu.be/Jtai4ogSsB4)
    - [DDL ALTER](https://youtu.be/bp8DsBI6Oik)
    - [DDL TRUNCATE, DROP and RENAME](https://youtu.be/bp8DsBI6Oik)
    - [Practicle Tutorial](https://youtu.be/XfrgCK6BX5w)

6. **Data Manipulation Language (DML)**
    - [DML INSERT and UPDATE](https://youtu.be/w27gAgDQr_w)
    - [DML DELETE and SELECT](https://youtu.be/9lTuR0RfKz8)
    - [Aggregate Functions and different clauses](https://www.youtube.com/watch?v=RGIVS8RGBaI&list=PLhEsvHVW7qXrJS3OEB7pWqvclQF0FrZc1)<br>
    (please watch the whole playlist)
    - Practice Tasks [1](https://pgexercises.com/questions/basic/), [2](https://pgexercises.com/questions/updates/), [3](https://pgexercises.com/questions/aggregates/)

7. [Data Control Language (DCL)](https://youtu.be/QBN8H9CfYzs?si=681o3HbStg24eyBe)

8. **Joins and Subqueries in SQL**
    - [Joins](https://youtu.be/h4EQBAzW3m4)
    - [Subqueries](https://youtu.be/i5acg3Hvu6g)
    - Join vs Subquery [1](https://medium.com/@sanjuktabaruah5/sql-joins-vs-subqueries-a-comprehensive-comparison-039e6f4686a5), [2](https://asktom.oracle.com/ords/f?p=100:11:0::::P11_QUESTION_ID:66812779016023)
    - [Practice](https://pgexercises.com/questions/joins/)

9. [Cascade](https://www.scaler.com/topics/sql/cascade-in-sql/)

10. [Delete vs Soft Delete](https://www.milanjovanovic.tech/blog/implementing-soft-delete-with-ef-core)

## Transactions

1. [Transactions and ACID Properties](https://www.datacamp.com/blog/acid-transactions)
2. [Transaction Control Language (TCL)](https://youtu.be/acn8_F98ruk)
3. [Practical Implementation](https://neon.com/postgresql/postgresql-tutorial/postgresql-transaction)

## Indexing and Query Optimization
1. **Indexing**
    - [Introduction](https://youtu.be/BIlFTFrEFOI?si=xOmpMZ2kDgRwp4Ew)
    - [How to use Indexing](https://www.geeksforgeeks.org/sql/sql-indexes/)<br><br>
    Extra resources for reference : [1](https://www.youtube.com/watch?v=3G293is403I), [2](https://medium.com/@sofiasondh/what-is-index-in-sql-142c50983328)


2. [Query Optimization](https://www.geeksforgeeks.org/sql/best-practices-for-sql-query-optimizations/)
    - Extra resources for reference : [1](https://www.datacamp.com/blog/sql-query-optimization)

## Practical Backend Patterns
1. [Connection Pooling](https://www.geeksforgeeks.org/python/python-postgresql-connection-pooling-using-psycopg2/)

2. **N+1 Problem**
    - [Introduction](https://youtu.be/qPfAQY_RahA)
    - [n+1 problem in django](https://blog.appsignal.com/2025/07/09/how-to-avoid-nplus1-queries-in-django-python.html)

3. [Pagination](https://youtu.be/zwDIN04lIpc)

4. **Bulk Inserts**
    - Tutorial [1](https://medium.com/@askintamanli/fastest-methods-to-bulk-insert-a-pandas-dataframe-into-postgresql-2aa2ab6d2b24), [2](https://dev.to/josethz00/speed-up-your-postgresql-bulk-inserts-with-copy-40pk)
    - Extra resources for reference : [1](https://youtu.be/aQrQnNvJguA?si=e8ntUB7_kpZoGwfD), [2](https://hakibenita.com/fast-load-data-python-postgresql)

5. **Idempotency**
    - [First Article](https://medium.com/@krthiak/idempotency-49bed8f9d45c)
    - [Second Article](https://dagster.io/glossary/data-idempotency)
    - Extra resources for reference : [1](https://youtu.be/XAccGbtl3Z8?si=t2MWsXEpsxyAVUnp)