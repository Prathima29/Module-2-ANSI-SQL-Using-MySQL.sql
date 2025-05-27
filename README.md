Community Event Portal – SQL Database Project
This project sets up a relational database for a Community Event Portal using MySQL. It models core entities like users, events, sessions, registrations, feedback, and resources. A collection of analytical SQL queries is also included to generate useful insights from the data.

📁 Database: cognizant
📦 Schema Overview
Users – Stores user information.

Events – Contains event details and the organizer (user).

Sessions – Describes individual sessions within events.

Registrations – Tracks user registrations to events.

Feedback – Stores ratings and comments from users about events.

Resources – Stores associated files or links for events.

⚙️ Setup Instructions
✅ Prerequisites
MySQL Server (or any MySQL-compatible tool like MySQL Workbench)

SQL execution environment

🚀 Steps to Run
Create and Use Database

sql
Copy
Edit
CREATE DATABASE cognizant;
USE cognizant;
Create Tables
Run the provided SQL statements under the "CREATE TABLE" section to define the schema.

Insert Sample Data
Use the "INSERT INTO" statements to populate tables with sample data.

Run SQL Queries
Execute the analytical queries to extract insights and test the database.

📊 Analytical SQL Queries
This project includes 25+ SQL queries addressing practical questions such as:

Upcoming events per user

Event feedback ratings

Inactive users

Overlapping sessions

Resource uploads per event

Top contributors and more

Each query is self-contained and labeled for easy navigation.

📌 Example Queries
Q1: List of upcoming events registered by users in their city.

Q10: Identify events with registrations but no feedback.

Q15: Detect overlapping sessions in the same event.

Q24: Compute average session durations for events.

🔍 Use Cases
This schema and query set can be used for:

Training on ANSI SQL (MySQL flavor)

Practicing advanced joins, aggregations, and filters

Simulating community portal reporting needs

Interview preparation

📄 License
This project is free for educational and personal use.

