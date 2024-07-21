MySQL Scripts Repository
This repository contains a series of SQL scripts for performing basic operations on a MySQL server. Each script is designed to manage and manipulate databases and tables, demonstrating common SQL tasks.

Directory Structure
SQL_introduction: Contains SQL scripts for various tasks.

###Scripts Overview
List Databases (0-list_databases.sql)

Lists all databases in the MySQL server.
Create a Database (1-create_database_if_missing.sql)

Creates the database hbtn_0c_0 if it does not already exist.
Delete a Database (2-remove_database.sql)

Deletes the database hbtn_0c_0 if it exists.
List Tables (3-list_tables.sql)

Lists all tables in a specified database.
Create First Table (4-first_table.sql)

Creates a table named first_table in the specified database with columns id and name.
Full Table Description (5-full_table.sql)

Prints the full description of the first_table.
List All Rows in Table (6-list_values.sql)

Lists all rows of the first_table.
Insert a New Row (7-insert_value.sql)

Inserts a row with id = 89 and name = Best School into first_table.
Count Records with Specific ID (8-count_89.sql)

Displays the number of records with id = 89 in the first_table.
Create Second Table (9-full_creation.sql)

Creates a table named second_table with columns id, name, and score, and populates it with predefined records.
List Records by Score (10-top_score.sql)

Lists all records from second_table ordered by score in descending order.
List Records with Score >= 10 (11-best_score.sql)

Lists all records from second_table with a score of 10 or more, ordered by score.
Update Score for Specific Record (12-no_cheating.sql)

Updates the score for the record with name = Bob to 10 in second_table.
Remove Low Score Records (13-change_class.sql)

Deletes all records with a score less than or equal to 5 from second_table.
Calculate Average Score (14-average.sql)

Computes the average score of all records in second_table.
Number of Records by Score (15-groups.sql)

Lists the number of records for each score in second_table, sorted by the number of records in descending order.
List Records with Non-Null Names (16-no_link.sql)

Lists all records from second_table with a non-null name, ordered by score in descending order.
