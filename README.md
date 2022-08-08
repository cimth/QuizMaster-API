API description of QuizMaster
=============================

With QuizMaster you can create and play quizzes where you have to select 1 of 4 answers.

This project contains the API description of QuizMaster. 
This API description is written in OpenAPI / Swagger specification and summarizes all endpoints of the QuizMaster 
backend.


## Backend and frontend

You can find the QuizMaster backend, based on Spring Boot, inside the following repository:
https://github.com/cimth/quizmaster_backend

The frontend, created with Angular, is located within the following repository:
https://github.com/cimth/quizmaster_frontend


## Admin Token

For doing POST, PUT and DELETE requests which lead to modifying the backend's database, you have to provide
an Admin Token in the Authorization header of your request. 
This token is re-created on each startup of the application and will be printed on the console. 
Thus, only the admin of the server can modify the database.

For more information look up the above linked backend repository.