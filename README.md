#  GradeTracker Database

**GradeTracker** is a basic academic tracking system designed to store and manage:

- Student records
- Subject details
- Login credentials
- Marks and grading information

This README outlines how to initialize the database and describes the purpose of each SQL operation used in the setup.

---

# Aggregate Functions and Grouping in GradeTracker

This section explains the SQL commands used to perform aggregation, grouping, and filtering on grouped data in the GradeTracker database.

---

## Commands Overview

### 1. Use Database

- **Purpose:** Selects the `gradetracker` database to execute subsequent queries within the correct context.  
- **Used for:** Ensuring all SQL statements run against the intended database.

---

### 2. Aggregate Functions (`SUM()`, `AVG()`, `MAX()`, `MIN()`, `COUNT()`)

- **Purpose:** Perform calculations on numeric columns to produce summary statistics.  
- **Used for:**  
  - `SUM()` to calculate the total of values in a column.  
  - `AVG()` to find the average value.  
  - `MAX()` to find the maximum value.  
  - `MIN()` to find the minimum value.  
  - `COUNT()` to count the number of rows or records.

---

### 3. Use `GROUP BY` to Categorize Data

- **Purpose:** Organize rows into groups based on one or more columns.  
- **Used for:** Applying aggregate functions on each group separately, such as grouping marks by student.

---

### 4. Filter Groups Using `HAVING`

- **Purpose:** Filter grouped results based on conditions applied to aggregate values.  
- **Used for:** Selecting only those groups that meet specified criteria, for example, students with average marks above a threshold.

---

By mastering these commands, you can efficiently analyze and summarize student performance data in the GradeTracker system.

---
