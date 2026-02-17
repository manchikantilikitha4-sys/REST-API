# REST-API
This project develops a RESTful API using Flask to efficiently manage user data. It implements CRUD operations through GET, POST, PUT and DELETE methods, allowing creation, retrieval, updating and deletion of user records. The API ensures structured communication between client and server and is tested using Postman or Curl for proper functionality and reliability.
To create an effective README.md for your project, you should organize the information so that anyone (including your future self) can understand and run the task easily.This project is a simple RESTful API built with Python and Flask. It manages a mock database of users and demonstrates core backend concepts like routing, data serialization (JSON), and handling different HTTP methods

 FLASK REST API PROJECT OVERVIEW 
Features:
In-Memory Storage: Uses a Python dictionary to store user data (ID, Name, Email).
GET All Users: Fetches the complete list of users in JSON format.
DELETE User: Removes a specific user from the list using their unique ID.
Debug Mode: Automatically restarts the server when code changes are detected.

Technical Setup:
 Environment: Python 3.11.
 Dependencies: Flask.
 Install via: py -m pip install flask.
 Server Address: The application runs locally at http://127.0.0.1:5000.

How to Use
Start the Server: Run the command py "rest api.py" in the terminal.
Access Data: Open your browser and navigate to http://127.0.0.1:5000/users.
Stop the Server: Press CTRL+C in the terminal.
