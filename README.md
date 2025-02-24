# Task-Manager-API
Objective: Build a RESTful API with Express and Mongoose to manage tasks in a MongoDB collection.

Tasks
Define a Task schema with fields like title, description, status (e.g., "Pending", "Completed"), and dueDate.
Set up the following API endpoints:
POST /tasks: Add a new task to the database.
GET /tasks: Retrieve all tasks.
GET /tasks/:id: Retrieve a specific task by ID.
PUT /tasks/:id: Update task details by ID.
DELETE /tasks/:id: Delete a task by ID.
Test the API endpoints using Postman or Thunder Client.
Use filters to query tasks based on their status or dueDate.
Handle basic errors, such as invalid task IDs or missing fields.
