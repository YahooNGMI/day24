# server

The backend Express server written in Node.JS for our app. 

## tasks 
 1. A `.post` route create a new user
 2. a `.get` route to get all users.

 ## architecture 

 1. We want to save all the users to a file, permanently, so if the server restarts, they are saved. this means we need to, on server start, load that file, and every time a user is created, edit the file.