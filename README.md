# PostgreSQL-SQLServer-SQLAlchemy-Pyodbc
This repository contains the following files:

• **sql_report.ipynb**: A Jupyter Notebook that shows how to connect to a PostgreSQL database using Python to perform some SQL queries to answer specific questions. How to upload a data base to the cloud (in "render.com") and how to install "PostgreSQL" VSCode extension to perform SQL queries are also shown.

"sql_report.ipynb" is inside notebooks folder.

• **postgreSQL_sqlalchemy_example.py**: A Python script to connect to a PostgreSQL database, make a query by using a python variable, retrieves data from a table, and appends new data to it. The Python library "sqlalchemy" is used.

• **pyodbc_sqlserver_example.py**: Simple example of connection to a DB by using SQLServer, pyodbc and Python. The query result is saved in an excel file.

• **sqlalchemy_sqlserver_example.py**: Simple example of connection to a DB by using SQLServer, sqlalchemy and Python. The query result is saved in an excel file.

Finally,

- Folder "reports" contains the first version of the "sql_report.ipynb" in PDF format.

- Folder "images" contains some images used in "sql_report.ipynb".

## 🚀 How to run locally
1. Clone this repository:
```
git clone https://github.com/arteaga7/PostgreSQL-SQLServer-SQLAlchemy-Pyodbc.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env && source env/bin/activate && pip3 install -r requirements.txt
```
3. Run "notebooks/sql_report.ipynb".
