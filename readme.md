# slide - 3
https://drive.google.com/file/d/1ZQn4Q4DG9UyybOYUdY8USEFBTb0xo2DL

In this module, you’ll learn the fundamentals of PostgreSQL. From installing tools like pgAdmin and Beekeeper Studio to understanding key data types (Integer, Boolean, Character, Date, UUID), you’ll build a strong base. You’ll also practice creating and dropping databases/tables, applying constraints, and exploring different insert methods.

By the end, you’ll be ready to structure and manage data confidently in PostgreSQL.

## 44-1 intro to SQL
- The language we use to talk with databases - aka  Structured Query Language
- We wil use postgres and communicate using sql
- SQL Is declarative languageYou tell the database what you want, not how to do it. (database will manage it)
- lets see a sql statement
![alt text](img.png)
```
SELECT name FROM students WHERE age > 18 
```
- Tell step by step is `Imparative` but SQL is `declarative`
