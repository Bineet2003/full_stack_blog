running backend:
go inside backend folder,
type "npm i" //  it will install the backend  package
type "npm start" //it will start the server

running frontend:
go inside frontend folder,
type "npm i" //  it will install the frontend package
type "npm start" //it will start the react app


In this version i changed backend\controllers\blogController.js and frontend\src\client\pages\BlogDetails.js
I fixed the issue of that when there is a comment of user who is deleted the site crashes when i open blog containing the comment of the deleted user. Now it shows that the comment was given by a deleted user.
