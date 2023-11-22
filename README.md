# AirBnB Clone - MySQL

## Team Members
- Solomon Odunusi
- Chidera Obuegbe

## Project Overview
This project aims to create an AirBnB clone using Python, Object-Oriented Programming (OOP), SQL, and SQLAlchemy. The goal is to implement a back-end system with MySQL as the database, allowing users to interact with the application seamlessly.

## Project Timeline
- **Start Date:** Nov 17, 2023 6:00 AM
- **End Date:** Nov 23, 2023 6:00 AM
- **Checker Release:** Nov 18, 2023 6:00 PM

## Environment Variables
- **HBNB_ENV:** Running environment (dev or test).
- **HBNB_MYSQL_USER:** MySQL username.
- **HBNB_MYSQL_PWD:** MySQL password.
- **HBNB_MYSQL_HOST:** MySQL hostname.
- **HBNB_MYSQL_DB:** MySQL database name.
- **HBNB_TYPE_STORAGE:** Type of storage (file or db).

## Learning Objectives
- Implement Unit Testing in a large project.
- Understand and use *args and **kwargs.
- Handle named arguments in a function.
- Create and configure a MySQL database.
- Map Python Classes to MySQL tables using SQLAlchemy.
- Handle two different storage engines in the same codebase.
- Utilize environment variables for configuration.

## File Structure
```
.
├── models/
│   ├── base_model.py
│   └── ... (other model files)
├── tests/
│   ├── test_models/
│   │   ├── test_base_model.py
│   │   └── ... (other test files)
│   └── ...
├── sql_scripts/
│   ├── create_database.sql
│   └── ... (other SQL files)
├── README.md
└── ... (other project files)
```

## How to Run Tests
```bash
python3 -m unittest discover tests
```
To test file by file:
```bash
python3 -m unittest tests/test_models/test_base_model.py
```

## How to Execute SQL Scripts
```bash
mysql -u <username> -p <password> < create_database.sql
```

## Code Style
Ensure your code follows PEP 8 guidelines. Use the following command to check:
```bash
pycodestyle <filename>
```

## Resources
- [cmd module](link-to-cmd-module)
- [SQLAlchemy tutorial](link-to-sqlalchemy-tutorial)
- [How To Create a New User and Grant Permissions in MySQL](link-to-mysql-tutorial)
- [Python3 and environment variables](link-to-python-env-tutorial)
- [MySQL 8.0 SQL Statement Syntax](link-to-mysql-syntax)
- [Learning Objectives](link-to-learning-objectives)
