# ETL Project
Project Overview:

This project involved the design and implementation of a robust ETL (Extract, Transform, Load) pipeline to efficiently process raw data and make it readily available for analysis. The focus was on extracting data from diverse sources, transforming it into a structured format, and loading it into a SQL database for further exploration and reporting.

Key Technologies:

Python: The primary programming language used for data manipulation, transformation, and automation.
Pandas: A powerful data analysis and manipulation library in Python, utilized for creating and manipulating dataframes (tabular data structures).
SQL: The standard language for managing relational databases. Used here to define the database schema, create tables, and insert the processed data.
Python Dictionaries: Leveraged to store and manipulate structured data during the transformation phase.
Project Phases:

Extract:

Identified and accessed relevant data sources (e.g., CSV files, API endpoints, web scraping).
Extracted data from these sources using appropriate libraries and techniques (e.g., requests for APIs, BeautifulSoup for web scraping).
Loaded the raw data into Pandas DataFrames for further processing.
Transform:

Thoroughly cleaned the data, addressing missing values, inconsistencies, and outliers.
Performed data type conversions, aggregations, and calculations as needed.
Used Python dictionaries to map, filter, and restructure data elements.
Applied business logic and domain knowledge to derive meaningful insights from the raw data.
Load:

Designed a normalized database schema using SQL to ensure data integrity and efficiency.
Created the necessary tables in the SQL database.
Established a robust connection between the Python script and the database.
Loaded the transformed data from Pandas DataFrames into the SQL database.
Project Deliverables:

Campaign DataFrame: A structured table containing information about marketing campaigns (e.g., campaign ID, name, start date, end date).
Category DataFrame: A table storing categories associated with campaigns (e.g., category ID, name, description).
Subcategory DataFrame: A table capturing subcategories related to categories (e.g., subcategory ID, name, category ID).
SQL Database: A relational database containing the fully processed and structured data, ready for analysis and reporting.
ERD (Entity Relationship Diagram): A visual representation of the database schema, illustrating the relationships between tables and attributes.
ETL Pipeline: A well-documented Python script that automates the entire ETL process, ensuring data consistency and reproducibility.
