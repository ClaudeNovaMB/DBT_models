📚 The Collection of Data Models

1. Basic 🐣 (Beginner Level)

At this level, the focus is on fundamental dbt modeling concepts, basic SQL skills, and simple transformations.

Subcategories:
   
	•	Simple Selects: Basic SELECT queries that introduce users to dbt models.
		Example: Simple data retrieval from a single table.

	• 	Basic Transformations: Fundamental transformations like filtering (WHERE), aggregations (COUNT, SUM), and basic calculations.
		Example: Aggregating sales data or counting active users.

	• 	Renaming Columns & Aliasing: Simple renaming of columns for clarity or better naming conventions.
		Example: SELECT customer_id AS id, customer_name AS name FROM customers

	• 	Simple CTEs (Common Table Expressions): Introducing WITH statements to modularize SQL.
		Example: Using a CTE to simplify multi-step queries.

	• 	Basic Joins: Simple INNER JOIN or LEFT JOIN between two tables.
		Example: Joining customers with orders data.

2. Intermediate 🚀 (Intermediate Level)

Here, you’re introducing more advanced SQL techniques, slightly more complex transformations, and dbt features that help users build reusable models.

Subcategories:

	•	Multi-Table Joins: Performing more complex joins with multiple tables and UNION.
	 	Example: Joining customers, orders, and products tables.
   
	•	Window Functions: Implementing functions like ROW_NUMBER(), RANK(), and LEAD()/LAG() for row-based operations.
	    	Example: Ranking customers based on their total spend.
      
	•	Case Statements and Conditional Logic: Adding conditional logic using CASE WHEN clauses.
	    	Example: Categorizing customers based on order volume.
      
	•	Intermediate CTEs & Subqueries: Combining multiple CTEs or using subqueries for better modularization.
	    	Example: Using subqueries within JOIN clauses for more dynamic data.
      
	•	Derived & Surrogate Keys: Creating new unique keys from existing data, typically for modeling purposes.
	    	Example: Creating a unique identifier from multiple columns.

	Intermediate dbt Features:
	•	Refactoring & DRY (Don’t Repeat Yourself) Principles: Reusing code across multiple models.
	•	Using Macros: Introduction to writing simple macros to automate repetitive SQL patterns.

3. Advanced 🧠 (Advanced Level)
```
TBC
```




