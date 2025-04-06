# 📘 About this project
This project was developed as part of the Database Systems module in my Master's program in Computing & Information Systems. 
It was completed in collaboration with two teammates, focusing on setting up database schema and providing access methods to this database in the form of SQL queries and views. 

## 📂 Coursework Specifications

### Tasks:
- Creating a conceptual schema in the form of an ER or UML diagram.
- Deriving a relational schema from the ER diagram.
- Normalising the relations.
- Implementing this schema by using SQL in Oracle.
- Populating the database with a set of typical data. The data should be significant but manageable.
- Defining specialised views which are appropriate to various sub-groups of users.
- Defining SQL queries which could be used as canned queries for naive users.


###  Database Application Requirements:
**1. Resources List:**
- Track physical resources: books, eBooks, and electronic devices (laptops, tablets, eBook readers), including records of:
  + Physical location for items (shelf number and floor number). eBooks: No physical location, but digital copies limit simultaneous access
  + Class numbers for physical books, except for devices and eBooks).
  + Number of copies

**2. Members List:**
- Track library members including staff and students including:
  + Details of overdue fines owed by each member
  + Membership status and whether they have been suspended due to overdue fines
    
**3. Loan & Reservation:**
Design and implement a relational design that supports:
- Different loan periods for different member types:
  + Students: Max 5 items borrowed at once.
  + Staff: Max 10 items borrowed at once.
- Reservations principles:
  + If a resource is unavailable, a reservation is created.
  + Multiple reservations can exist for a single resource.
  + When an item becomes available, the earliest reservation is notified.
  + If a member cannot take up the offer within 3 days or declines 3 times, the reservation is canceled.
• Records track of:
  + All current reservations and failures to take up offers on reserved items when they become available.
  + Loans, including whether they are overdue.
  + A record of previous loans to help in identifying popular resources.


## 🧠 Key Skills: 
### Achieved 29/30 mark
1. **Relational Database Design**: understanding of entity-relationship (ER) modelling, relational schema, and normalisation to avoid redundancy and maintains data integrity.
2. **Database Implementation**: crafted successful SQL queries for creating TABLES and VIEWS, retrieve data based on requirements and going above and beyond by incorporating TRIGGERS to enhance database functionality and maintain data integrity
3. **Teamwork & Collaboration**: developed effective communication and coordination with teammates by dividing tasks, sharing ideas, and collective problem-solving to achieve project milestones.


### 📊 View Project Results in above Respository:
1. **`database-conceptual-model.pdf`**: This file includes the conceptual ER diagram/model, offering a high-level view of the system's entities and their relationships. It serves as the foundational blueprint for the database, clearly outlining key components such as resources, members, loans, and reservations.
2. **`database-relational-schema.pdf`**: This document contains the relational schema derived from the ER diagram, detailing the specific tables, attributes, and relationships. It illustrates how the entities from the conceptual model have been translated into a structured relational format, ensuring the database's integrity
3. **`database-queries.sql`**: This file includes all SQL queries, including those used for setting up the database on Oracle Live SQL and for data retrieval for users (e.g., checking resource availability, overdue loans, active reservations...).
