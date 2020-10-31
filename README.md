<img src="https://i.imgur.com/XNZPngy.pngg" alt="drawing" width="300"/>

## Notelor - Notepad Application: https://notelor.herokuapp.com/
#### Technology Used : Python (Flask) and Sqlite3

# sqlite
SQLite is a C library that provides a lightweight disk-based database that doesn’t require a separate server process and allows accessing the database using a nonstandard variant of the SQL query language. Some applications can use SQLite for internal data storage. It’s also possible to prototype an application using SQLite and then port the code to a larger database such as PostgreSQL or Oracle.
To use the module, you must first create a Connection object that represents the database. Here the data will be stored in the example.db file:

import sqlite3
conn = sqlite3.connect('example.db')

# Flask startup and configuration
Like most widely used Python libraries, the Flask package is installable from the Python Package Index (PPI). First create a directory to work in (something like flask_todo is a fine directory name) then install the flask package. You'll also want to install flask-sqlalchemy so your Flask application has a simple way to talk to a SQL database.

I like to do this type of work within a Python 3 virtual environment. To get there, enter the following on the command line:

$ mkdir flask_todo
$ cd flask_todo
$ pipenv install --python 3.6
$ pipenv shell
(flask-someHash) $ pipenv install flask flask-sqlalchemy

# Installation

Clone Repository Process : https://help.github.com/en/articles/cloning-a-repository

### Make sure you have installed Python v3 or higher:

Python: https://www.python.org/downloads/
Pip: https://pip.pypa.io/en/stable/installing/

### Go to root of project and run:
```bash
pip install -r requirements.txt
```

# Usage

#### **Run App**
Go to project directory and run following command in terminal.
```bash
Flask run
```

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
