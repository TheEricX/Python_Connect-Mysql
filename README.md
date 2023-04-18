# Python Connect Mysql

## Used Python create engine to connect Mysql database

 - import pymysql
 - import sqlalchemy
 - sqlalchemy.create_database

## Input DF data into database

 - .to_sql()

## Used Pandas read database
 - pd.read_sql()
## Used Python update database
 - Method 1: First merge the new data with the original data in python, and then **use to_sql** to import it into the database to overwrite the original data
 -  Method 2: Use SQL statement INSERT INTO to append
 - Use  **cursor.excute('sql')**  to insert data
 (To avoid warning of without return)
