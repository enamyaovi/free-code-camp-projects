# Learn SQL by Building a Student Database: Part 1

![Status](https://img.shields.io/badge/project-active-brightgreen)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Used-blue)
![Bash](https://img.shields.io/badge/Bash-Scripting-lightgrey)
![freeCodeCamp](https://img.shields.io/badge/freeCodeCamp-Project-9cf)

This project is part of my ongoing journey to become a Back End Engineer. It was completed as part of the **freeCodeCamp Back End Development** track and served as a valuable introduction to both **PostgreSQL** and **Bash shell scripting**.

The main objective was to design a relational database in PostgreSQL and populate it using data from a CSV file via a Bash script. Although I was more familiar with MySQL, this project helped me bridge into PostgreSQL and gain confidence writing Bash scripts.

I also discovered that many foundational concepts from Python, such as loops and conditionals were transferable to shell scripting. The syntax was different, and I occasionally fell back into Python habits, but I eventually adapted through practice and referencing community resources. This hands-on, project-based approach made the learning process more rewarding.

---

## Project Structure

```bash
Student_database_project/
├── courses.csv        # Sample course data
├── insert_data.sh     # Bash script to populate the database
├── README.md          # Project documentation
├── students.csv       # Sample student data
└── students.sql       # SQL script to create tables and schema
```

---

## Technologies Used

- PostgreSQL
- Bash shell scripting
- CSV (Comma-Separated Values)
- SQL (DDL & DML)

---

## How to Run This Project

1.  Make sure you have **PostgreSQL** installed and running.

2. Run the SQL script to create the database schema:
    ```
      psql -U your_username -f students.sql
    ```
3. Run the Bash script to populate the database:
    ```
    bash insert_data.sh
    ```

⚠️ Update the database name and user credentials in the script if needed

## Key Learning Highlights
- Creating relational tables with PostgreSQL

- Writing Bash scripts to automate database imports

- Translating Python logic into shell scripting

- Handling CSV data via command-line

- Troubleshooting using psql, echo, and error outputs
