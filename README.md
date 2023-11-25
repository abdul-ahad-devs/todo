This is a basic To Do Application developed using React JS and Express JS.

In order to run the frontend, please follow these steps:
- checkout to todo-app-frontend folder
- run `npm install && npm start`. The frontend will run automatically at http://localhost:3000.

In order to run the backend, please follow these steps:
- there must be an empty database created inside PGAdmin with the name `todo_app`.
- update your local database credentials inside `db-connection.ts` file in `todo-app-backend` folder
- checkout to todo-app-backend folder
- run `npm install && npm run start`. The backend will run automatically at http://localhost:8080.
- run `npm test` to execute all unit tests
