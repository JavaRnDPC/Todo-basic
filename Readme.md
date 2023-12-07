Create a Django REST framework project with a single model for a Todo item. The Todo item should have the following fields:

Title (CharField)
Description (TextField)
Completed (BooleanField)
Due_Date (DateTimeField - automatically set on creation)
Create the necessary serializers and views to perform the basic CRUD operations (Create, Read, Update, Delete) for the Todo model.

Your API should support the following endpoints:

List all Todos

Endpoint: /api/tasks/
HTTP Method: GET
Retrieve a single Todo by its ID

Endpoint: /api/tasks/<id>/
HTTP Method: GET
Create a new Todo

Endpoint: /api/tasks/
HTTP Method: POST
Update a Todo by its ID

Endpoint: /api/tasks/<id>/
HTTP Method: PUT
Delete a Todo by its ID

Endpoint: /api/tasks/<id>/
HTTP Method: DELETE
Ensure that you include proper error handling and validation in your code. You can use Django REST framework's serializers and views to simplify this task.