## 📚 Online Bookstore SQL Project

This project demonstrates the design and querying of a relational database for an **Online Bookstore** using SQL. It includes table creation, data import (via CSV files), and a variety of SQL queries from basic to advanced analytics.


## 🗂️ Project Structure

 **Tables:**
  - `Books` – stores book details (title, author, genre, price, stock, etc.)
  - `Customers` – stores customer information (name, email, location, etc.)
  - `Orders` – records orders placed (customer, book, date, quantity, amount)

 **SQL Operations Covered:**
  - Table creation and foreign key constraints
  - Data import using `COPY` command
  - Basic queries (SELECT, WHERE, ORDER BY, etc.)
  - Aggregate functions (`SUM`, `AVG`, `COUNT`)
  - JOIN operations
  - Grouping and filtering (`GROUP BY`, `HAVING`)
  - Subqueries and advanced reporting


## ⚙️ Technologies Used

- SQL (PostgreSQL syntax)
- CSV for data import
- Any PostgreSQL-compatible RDBMS


## 📌 How to Use

1. **Set up PostgreSQL** on your system.
2. Open your preferred SQL client (like pgAdmin, DBeaver, or psql CLI).
3. Run the script:  
   'C:\Users\taman\Downloads\Online_Bookstore.sql';


📊 Key Queries in the Project
List books in a specific genre or published after a year

Filter customers by country

Show monthly orders and total stock

Calculate revenue, bestsellers, and customer activity

Advanced aggregations: total books sold by genre/author, top spenders, remaining stock

📁 Sample Data (via CSVs)
Books.csv

Customers.csv

Orders.csv

Ensure these files are available at the paths specified in the COPY commands, or update the paths accordingly.

💡 Sample Query
Find the top 3 most expensive books in the Fantasy genre:

SELECT * FROM books
WHERE Genre = 'Fantasy'
ORDER BY price DESC
LIMIT 3;


🤝 Contribution
Pull requests and improvements are welcome. If you use or enhance this project, feel free to star the repo and give credit!

📬 Contact
Author: Tamannya Mukherjee
Feel free to connect on LinkedIn(www.linkedin.com/in/tamannya-mukherjee-6193ab2a0) or GitHub(https://github.com/Tamannya) for feedback and collaborations.
