# Database Design
Objective:
In this task, you will design a database for a Library Management System. You will create three 
diagrams: a conceptual model and logical model. The goal is to apply the principles of database 
design learned in class to a real-world scenario.
Scenario:
You have been hired to design a database for a library. The library needs to track books, 
members, loans, and publishers. The system should support the following functionalities:
1. Track Books: Store information about books, including title, author, ISBN, publisher, 
publication year, and genre.
2. Manage Members: Store information about members, including name, address, phone 
number, and email.
3. Track Loans: Track which books are borrowed by which members, along with the loan 
date and due date.
4. Manage Publishers: Store information about publishers, including name, address, and 
contact information.
5. Generate Reports: The system should be able to generate reports on overdue books, 
popular genres, and member activity.

-----------------------------------------------------------------------------------------------

Task Breakdown:

### **Conceptual Model (ER Diagram)**

• Entities: Identify the major entities (e.g., Books, Members, Loans, Publishers).

• Relationships: Define the relationships between entities (e.g., a member can borrow 
multiple books, a book can have one publisher).

• Attributes: List the key attributes for each entity (e.g., Book attributes: Title, Author, 
ISBN).

• ER Diagram: Create an Entity-Relationship (ER) diagram to visually represent the entities 
and their relationships.

Deliverable: A conceptual model in the form of an ER diagram with entities, relationships, and 
attributes clearly labeled.

-----------------------------------------------------------------------------------------------

### **Logical Model**

• Tables: Convert the entities from the conceptual model into tables.

• Columns: Define the columns for each table, including data types (e.g., VARCHAR, 
INTEGER, DATE).

• Primary Keys: Identify the primary key for each table.

• Foreign Keys: Define foreign keys to establish relationships between tables.

• Normalization: Ensure the design is normalized to at least Third Normal Form (3NF).

• Logical Diagram: Create a logical model diagram showing tables, columns, primary keys, 
and foreign keys.

Deliverable: A logical model diagram with tables, columns, primary keys, and foreign keys 
clearly defined.

-----------------------------------------------------------------------------------------------

### **Sample Data:**

To help you design the database, here is some sample data for the Books, Members, Loans, 
and Publishers tables:

## Books Table

| BookID | Title                        | Author           | ISBN           | PublisherID | Publication Year | Genre     |
|--------|------------------------------|------------------|---------------|-------------|------------------|-----------|
| 1      | The Great Gatsby             | F. Scott Fitzgerald | 9780743273565 | 1           | 1925             | Classic   |
| 2      | To Kill a Mockingbird        | Harper Lee       | 9780061120084  | 2           | 1960             | Fiction   |
| 3      | 1984                          | George Orwell   | 9780451524935  | 3           | 1949             | Dystopian |
| 4      | Pride and Prejudice          | Jane Austen     | 9780141439518  | 4           | 1813             | Romance   |
| 5      | The Catcher in the Rye       | J.D. Salinger   | 9780316769488  | 5           | 1951             | Fiction   |


## Members Table

| MemberID | Name          | Address                     | Phone      | Email                  |
|----------|--------------|-----------------------------|------------|------------------------|
| 1        | John Doe      | 123 Main St, Springfield   | 555-1234   | john.doe@example.com   |
| 2        | Jane Smith    | 456 Elm St, Springfield    | 555-5678   | jane.smith@example.com |
| 3        | Alice Johnson | 789 Oak St, Springfield    | 555-9101   | alice.johnson@example.com |
| 4        | Bob Brown     | 321 Pine St, Springfield   | 555-1122   | bob.brown@example.com  |
| 5        | Carol White   | 654 Maple St, Springfield  | 555-3344   | carol.white@example.com |

## Loans Table

| LoanID | MemberID | BookID | LoanDate   | DueDate    |
|--------|---------|--------|------------|------------|
| 1      | 1       | 1      | 2023-10-01 | 2023-10-15 |
| 2      | 2       | 2      | 2023-10-02 | 2023-10-16 |
| 3      | 3       | 3      | 2023-10-03 | 2023-10-17 |
| 4      | 4       | 4      | 2023-10-04 | 2023-10-18 |
| 5      | 5       | 5      | 2023-10-05 | 2023-10-19 |

## Publishers Table

| PublisherID | Name                | Address                               | ContactInfo         |
|------------|---------------------|---------------------------------------|---------------------|
| 1          | Scribner            | 123 Publisher Lane, New York         | info@scribner.com  |
| 2          | HarperCollins       | 456 Publisher Ave, Chicago          | info@harpercollins.com |
| 3          | Signet Classics     | 789 Publisher Blvd, Boston          | info@signet.com    |
| 4          | Penguin Classics    | 321 Publisher Rd, London           | info@penguin.com   |
| 5          | Little, Brown and Co.| 654 Publisher St, Los Angeles       | info@littlebrown.com |


## The Solution

![Database Design](https://github.com/user-attachments/assets/96bba9a0-d971-4ca5-a962-7c3fd87b7e01)
