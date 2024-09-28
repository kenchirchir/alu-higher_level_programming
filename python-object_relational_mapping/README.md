Python Object-Relational Mapping Project


Introduction
This project bridges the worlds of Databases and Python. You will use MySQLdb to connect to a MySQL database, execute SQL queries, and then transition to using SQLAlchemy, an Object-Relational Mapper (ORM), to abstract database storage operations into Python objects. This project is designed to help you understand how to work with databases in Python, and the power of ORM in simplifying data manipulation.

Scripts Overview
0-select_states.py: Lists all states from a specified MySQL database.
1-filter_states.py: Lists all states starting with 'N'.
2-my_filter_states.py: Filters states by user input.
3-my_safe_filter_states.py: Securely filters states by user input to prevent SQL injection.
4-cities_by_state.py: Lists all cities from the database.
5-filter_cities.py: Lists all cities of a specified state.
6-model_state.py: Defines a SQLAlchemy model for the states table.
7-model_state_fetch_all.py: Fetches all state objects using SQLAlchemy.
8-model_state_fetch_first.py: Prints the first state object in the database.
Tasks
Each script corresponds to a task outlined in the project description. The tasks are designed to gradually build your understanding of how to interact with a database using both direct SQL queries and ORMs.
