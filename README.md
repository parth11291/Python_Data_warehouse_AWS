# Python_Data_warehouse_AWS
Data warehousing project template using Python in AWS framework.

Hello everyone,

I am sharing template of one of my Data Warehousing Project using python in AWS framework. I wont be sharing dataset for this Project for privacy issues but you will get to see Entities and their Attributes in Fact table and Dimensional table. 

Tech stack: 

Data lake: s3 (Source data) 
Staging table: Redshift 
Data warehouse: Redshift (Destination)

(1) dwh.cfg  : we will be creating config file with all those AWS keys and parameters.

(2) create_tables.py  : this python file would be creating and droping tables.

(3) sql_query.py  : this pyhton file will be having all those sql query for creating table schemas, staging table schemas,
                    dimentional table schema and insert into queries with python variable.
                  
(4) etl.py  : we will be loading data into tables using all those variable we have created in sql_query.py file.
