# Project-2 Crowdfunding_ETL

The project goal is to create an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. The transformed data can be used to create an ERD and a table schema, using CSV files. 

Contributors:

Ali Parvez
Shruti Deshpande

Project Details :
The project's data(excel format) is cleaned and processed using Python libraries
1.Pandas to read the data from the input files. 
2.Numpy
3.Regex
4.Json

The Data relationships are shown through ERD using QuickTBD, PostgreSql .

Files to run the project:

ETL_Mini_Project_ShrutiD_ParvezA.ipynb file 
campaign.csv
category.csv
contacts.csv
subcatgory.csv
crowdfunding_db_schema.sql - erd schema sql
crowdfunding_erd.png
given resource files: contacts.xlsx and crowdfunding xlsx


Steps to execute the project:

The starter Jupyter file may be run in Jupyter or Visual Studio. File will do the following :

1.Create the Category and Subcategory DataFrames:
Data is exported and transformed using  crowdfunding.xlsx, crowdfunding_info_df is created. The category & subcategory is split in two columns .The data for the two dataframes is then exported to category.csv,subcategory.csv.

2.Create the Campaign DataFrame
Data is exported and transformed using the data from crowdfunding.xlsx, campaign_df is created.The data is then exported to campaign.csv

3.Create the Contacts DataFrame
Data is exported and transformed using the data from contacts.xlsx. Using Option 1 of python dictionary method, data is extracted to create contact_info_df. The
data is ordered and exported to contacts.csv 

Steps to create Crowdfunding Database in PostgreSql :
Database is crowdfunding_db

1. login to PgAdmin and create a database crowdfunding_db.

2. Create table schemas using the query in file crowdfunding_db.sql. Refer the Quick DBD schema file  QuickDBD-Crowdfunding Schema

3. Run the queries in the file crowdfunding_db.sql in the sequence with the alter table queries .

4. Import the four csv files. (extracted above).

5. Check the if the files have successfully imported and data is loaded in tables using the Select queries . 

6. Database schema as a Postgres file named crowdfunding_db_schema.sql

Database is crowdfunding_db.







