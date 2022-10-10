# :memo: To Do List

- React Application

- Functionalities:

:cloud: Login, Logout, Signup
 <img width="714" alt="signup" src="https://user-images.githubusercontent.com/106992258/194888031-f219aa0e-bd25-4930-8eb0-76f8147b09d5.png">
<img width="725" alt="login" src="https://user-images.githubusercontent.com/106992258/194888065-bef2301b-e226-404e-b7dc-546bbbaa5488.png">


:cloud: Search, Add, Delete, Edit items
<img width="722" alt="to_do_list" src="https://user-images.githubusercontent.com/106992258/194890254-bd92f458-c758-4f91-a60d-82422f4d8f42.png">


### Install frontend Packages

`cd frontend`
`npm install @reduxjs/toolkit react-redux axios bootstrap react-bootstrap react-dom react-icons react-router-dom`

### Install backend Packages

`cd backend`
` npm install bcrypt cors dotenv express jsonwebtoken jwt-decode knex passport passport-jwt pg`

### Setup frontend .env

- in /frontend , set 1 variable in .env
  `REACT_APP_BACKEND = http://localhost:8000`

### Setup backend .env

- in /backend , set 4 variables in .env
  `DB_NAME = YOUR DATABASE NAME`
  `DB_USERNAME = YOUR DATABASE USERNAME`
  `DB_PASSWORD = YOUR DATABASE PASSWORD`
  `JWT_SECRET = YOUR JWT_SECRET`

### Setup for backend DB connect

- set up dummy data, run:
  `knex migrate:latest`
  `knex seed:run`

### Start the App:

`npm start`

### Account information

:bust_in_silhouette: login account: a
:key: login password: a
