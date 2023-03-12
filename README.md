# Django Todo App

This is a simple Todo app built using Django.

## Starting the App

To start the app, follow these steps:

1. Clone the app to your local machine:
`git clone https://github.com/iSaacSigei/todoApp-Django.git`

2. Navigate to the `try2` directory:
`cd try2`

3. Run the Django development server:
`python3 manage.py runserver`


## Routes

The following routes are available:

- `GET /`: displays the list of todo items
- `POST /create/`: creates a new todo item
- `GET /<id>/`: displays details of a todo item
- `PUT /<id>/update/`: updates a todo item
- `DELETE /<id>/delete/`: deletes a todo item

The routes can be accessed using the corresponding view functions:

- `views.index`: handles the root route
- `views.createTask`: handles the create route
- `views.updateTask`: handles the update route
- `views.deleteTask`: handles the delete route
