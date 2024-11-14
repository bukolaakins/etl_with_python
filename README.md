# etl_with_python
 
This project implements an ETL pipeline using Python to integrate and process data into a data warehouse hosted on PostgreSQL. 

The data is sourced from CSV files, which are first loaded into a staging table for temporary storage and cleaning. After the data is processed and transformed, it is then loaded into the main tables of the data warehouse for further analysis and reporting.