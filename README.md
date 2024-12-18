## SQL_Challenge
---
# Employee Database SQL Analysis

## Table of Contents
- [Description](#description)
- [Data Files](#data-files)
- [Features](#features)
- [Installation](#installation)
- [Results](#results)
- [Observable Trends](#observable-trends)

---

## Description

**Employee Database SQL Analysis** is a project designed to analyze employee data using SQL queries and Python tools. The project combines SQL database management and data visualization to provide insights into employee salaries, department relationships, and management hierarchies.

This project uses PostgreSQL for database creation and management, and Python with pandas and matplotlib for further analysis and visualization.

---

## Data Files

The following CSV files are used to populate the SQL database and analyze the results:

| File Name              | Description                                        |
|------------------------|----------------------------------------------------|
| `departments.csv`      | Contains department ID and department names.      |
| `dept_emp.csv`         | Links employees to their respective departments.  |
| `dept_manager.csv`     | Identifies department managers.                   |
| `employees.csv`        | Contains detailed employee information.           |
| `salaries.csv`         | Contains salary data for employees.               |
| `titles.csv`           | Provides job titles for employees.                |
| `SQL_Challenge.sql`    | SQL script with all queries for analysis.         |
| `queries.sql`          | Additional SQL queries for data exploration.      |
| `table_schemata.sql`   | SQL script for creating table schemas.            |

---

## Features

- **Database Creation**:
  - Creates a PostgreSQL database and tables from the provided CSV files.
  - Imports and normalizes data into the database.

- **SQL Queries**:
  - Analyzes key relationships between departments, employees, and salaries.
  - Determines trends such as average salary, managerial roles, and title distribution.

- **Data Visualization**:
  - Utilizes Python to generate charts and graphs for insights.
  - Visualizes salary distributions, job titles, and department hierarchies.

---

## Installation

1. **Prerequisites**:
   - Python 3.x
   - Required libraries (if any) listed in `requirements.txt`.

2. **Setup**:
   - Clone this repository or download the project files.
     
   - Install dependencies (if needed):
     ```bash
     pip install -r requirements.txt
     ```
---

## Results

### Key Insights:

1.	Salary Trends:
   - The average salary varies across departments, with noticeable trends among job titles.
2.	Employee Distribution:
   - Certain departments have a higher concentration of employees compared to others.
3.	Managerial Analysis:
- Data reveals the tenure and departments of managers, highlighting leadership distribution.
---

## Observable Trends

1.	Salary Distribution:
   - There is a clear pattern in employee salaries based on job titles and department roles.
2.	Department Insights:
   - Some departments consistently employ more people and pay higher average salaries.
3.	Data Normalization:
   - Organizing data into separate tables allows efficient querying and relational analysis.
---