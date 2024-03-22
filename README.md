# Normalized Database to Dimensional Data Warehouse

## Project Overview

This project focuses on converting a normalized database consisting of two departments into a unified Dimensional Data Warehouse. The goal is to transform the data into a structure that facilitates efficient querying and analysis.

## Directory Structure

- `DBT Docs/`: Contains automatically generated documentation by dbt, showcasing the tables in the new data warehouse.
- `dbt_tree/`: Includes the tree structure from the DBT repository.
- `Proposed Model/`: Contains a detailed dimensional model prepared in Excel using state-of-the-art techniques, along with a proposed Entity Relationship Diagram (ERD).
- `Snowflake DataLoader SQL/`: Provides the SQL script to load the normalized data from an Object Store into Snowflake, which serves as the staging database.
- `Vertabello/`: Includes files related to Vertabello, a tool used to create ER diagrams and generate up/down scripts.

## Process Overview

1. Snowflake DB acts as the staging database, storing the normalized data.
2. DBT (Data Build Tool) is utilized to orchestrate the data manipulation process, transforming the normalized data into dimensional data.
3. Four business scenarios are executed, resulting in the creation of four Star Schemas and four One Big Tables.
4. The final dimensional data warehouse is also implemented using Snowflake DB.

## Key Features

- Conversion of normalized data into a dimensional model
- Implementation of four business scenarios with corresponding Star Schemas and One Big Tables
- Utilization of DBT for data manipulation and orchestration
- Automatically generated documentation using dbt for easy reference
- Detailed dimensional model and ERD created using Excel and Vertabello
- Snowflake DB serving as both the staging database and the final dimensional data warehouse

## Getting Started

To explore the project, navigate through the directories mentioned above. The `DBT Docs/` directory provides an overview of the tables in the data warehouse. The `Proposed Model/` directory contains the dimensional model and ERD for reference. The SQL script for loading data into Snowflake can be found in the `Snowflake DataLoader SQL/` directory.

Feel free to reach out if you have any questions.
