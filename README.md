
**Project goals** 
This project takes data fcolected from a streaming service's logs, puts it into PostgreSQL tables, and then runs an ETL process to evaluate the specific data the company is looking for. 

**Files** 
The file called create_tables.py and the file called sql_queries.py create and drop the tables, as well as instering the data into the ETL pipeline. 

ETL.ipynb is a notebook to help me write the code for ETL.py, which executes the ETL process. 

test.ipnyb contains tests for the process to check for errors. 

mefirst.ipnyb exists simply to run create_tables.py and create the connection to the database. 

**Running the scripts**

mefirst.ipnyb runs first, and then the kernel is ready and create_tables.py runs.  

