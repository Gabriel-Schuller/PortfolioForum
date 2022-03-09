# ForumAPI

## Story
This project contains a backend and a frontend part. The backend is a .Net Core API project meant to offer the backend functionality for a forum. The project contains 4 repositories, for all CRUD operations for Questions, Answers, Comments and Users. Searching any of those by a word is also implemented, along with checkups for the questions/comments/answers to be unique. Users also have a jwt token functionality added to them.
The Frontend intends to use the backend api to allow registration/login functionality with the creation of a jwt token, and show the questions that are found in the database managed by the backend api. Future implementations will include the ability to add questions and have them managed by users.

## What are you going to learn?

>How to create a web API

>Work with Entity Framework

>Work with AutoMapper

>Work with Jwt token on the backend side

>How to send a Coockie from the backend

>Work with different routes for the controller

>Work with Swagger

>Work with CORS / create cors Policies that will make the results available on the frontend side.

>Work with repository pattern

>Work with React states

>Work with Context API

>Work with MUI for the components/theme for the login/registration pages

>Work with Jwt token on the frontend side

>Work with React Router

>Work with axios for the GET/POST calls


## Tasks

1. Implement controllers for questions/answers
    - Controller will contain all CRUD operations
    - There will be cheeckups if the question/answer/comment is unique and nobody else wrote the specific question or part of it
    - All the controllers will implement search by id or word 
    - Calls t o the api with bad input will throw exceptions

2. Implement repository pattern
    - There will be a folder called Repository in the Service folder
    - This folder will implement the repository pattern for uses, questions, answers and comments and also a base repository for Adding, Deletion and Saving changes to 	the database
    - Repository will work in conjunction with Entity Framework

3. Use EntityFramework for creating a database and manage its entities
    - Project will use entity framework code first for creating tables for users. answers, questions and comments
    - There is a separation between entities/usermodels (can use AutoMapper)
    - Migrations will be used to keep track of changes 

4. Create a login/register page
    
    - There will be a login/register page that allows the user to perform those common actions by interacting with the backend api
    - The login page will automatically redirect the user to the homepage
    - The register page will automatically redirect the user to the homepage
    - Providing bad imput will keep the user on the specific page and indicate failure

5. Create a Navigation Bar
    - A navbar can be used to move the user around the website
    - Login/Register functionality are visible if the user is not logged in
    - In case the user is logged in, he will see a profile that shows the first letter of his username

6. Create a homepage that shows all questions found in the database managed by the backed
    - The "/" route shows a list of questions that are found in the database


## General requirements

None

## Pictures



![FileSeparation](Images/FileSeparation.PNG?raw=true "Title")

![Dependency Packages](Images/DependencyPackages.PNG?raw=true "Title")


