

Task 1: Database Setup and Schema Design

#Domain: Library Management System
This project creates a database schema for a library to manage books, members, and issue_date.

 #Schema
 
Books: Stores book details (Book_ID, Book_Name, Author_Name).
Members: Stores member details (Member_ID, Member_Name, Email).
Book_issued: Tracks Book_issued (Book_issued_ID, Book_ID, Member_ID, Book_issue_Date).
Relationships: One-to-many between Books and Book_issued, Members and Book_issued.

#Files

- 'schema.sql': SQLscript to create the database and tables.
- 'ER_DIAGRAM_PNG.png': ER diagram of the schema.
- README.md : Briefly describe what Task 1 is about (a database schema for a Library Management System).

 #How to Run
 
1. Install MySQL Workbench.
2. Run 'schema.sql' to create the database.
3. View 'ER_DIAGRAM_PNG.png' for the schema design.
