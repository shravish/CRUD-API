# CRUD-API
A CRUD API is an interface that exposes the four fundamental database operations: Create, Read, Update, and Delete. These operations allow clients to interact with data stored in a database or other data store through an API, enabling them to add, retrieve, modify, and remove information. 

Here's a more detailed version
### Create: 
Allows clients to add new data to the database or system.
### Read: 
Enables clients to retrieve data from the database.
### Update: 
Allows clients to modify existing data in the database.
### Delete: 
Allows clients to remove data from the database.

These CRUD operations are often mapped to HTTP methods in RESTful APIs, such as POST for Create, GET for Read, PUT or PATCH for Update, and DELETE for Delete. 

Here’s a simple CRUD API using FastAPI and SQLite with SQLAlchemy for database interactions. FastAPI is modern, fast (high-performance), and easy to use.

### Requirements:
Install dependencies with:
```
pip install fastapi uvicorn sqlalchemy
```

### Run the API:
```
uvicorn main:app --reload
```
