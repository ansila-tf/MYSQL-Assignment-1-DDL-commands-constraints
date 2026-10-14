# Employee Database Management System

## About the Project
This project demonstrates the creation and management of an Employee Database using MySQL. It covers database creation, table creation, modifying table structures, applying constraints, renaming tables and columns, and deleting database objects.

## Database Name
`employee`

## Tables Created
The database includes three tables:

- **departments** – Stores department ID and department name.
- **location** – Stores location ID and location name.
- **employees** – Stores employee ID, employee name, gender, age, date of joining, designation, department ID, location ID, and salary.

## SQL Operations Performed
- Created and selected a database using `CREATE DATABASE` and `USE`.
- Created tables using `CREATE TABLE`.
- Added a new column using `ALTER TABLE ADD`.
- Modified a column's data type and size using `ALTER TABLE MODIFY`.
- Dropped a column using `ALTER TABLE DROP COLUMN`.
- Renamed a column using `ALTER TABLE RENAME COLUMN`.
- Renamed tables using `RENAME TABLE`.
- Removed all records using `TRUNCATE TABLE`.
- Deleted tables and databases using `DROP TABLE` and `DROP DATABASE`.
- Recreated tables with constraints.

## Constraints Used
- `PRIMARY KEY` – Uniquely identifies each record.
- `AUTO_INCREMENT` – Automatically generates ID values.
- `NOT NULL` – Prevents empty values in specified columns.
- `UNIQUE` – Prevents duplicate values.
- `CHECK` – Ensures the employee age is at least 18.
- `DEFAULT` – Sets the date of joining to the current date when no value is provided.
- `ENUM` – Restricts gender values to `M` or `F`.
- `FOREIGN KEY` – Establishes relationships between employees, departments, and locations.

## Data Types Used
- `INT`
- `VARCHAR`
- `ENUM`
- `DATE`
- `DECIMAL`

## Tools Used
- MySQL
- MySQL Workbench (or any compatible MySQL client)


