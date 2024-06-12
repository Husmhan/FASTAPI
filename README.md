**Developing an API server with FastAPI**

This invoolves integrating  a database into the application using SQLAlchemy with FastAPI, which allow users to interact with the database through the API server. 

This means that the create, read, update, and delete operations in your server can now be directly linked to a database, storing or retrieving data as needed.

Here's a brief description of what each file will do in tut3 folder.

* __init__.py is used to indicate the directory should be treated as a Python package. Nothing is here.

* controllers.py will define our helper functions that carry out the CRUD operations.

* database.py contains our database connection code.

* models.py stores our database objects for SQLAlchemy to use.

* requirements.txt is used to enter the dependencies that will be installed.

* schemas.py will define our data structures for Python to use.

Run the following command in the tut3 directory to initialise your virtual environment in the venv/ directory.

In the tut3 directory, run the API server with the following commanuvicorn app.main:app --reload
