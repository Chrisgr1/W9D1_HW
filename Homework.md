Questions

1 What is responsible for defining the routes of the games resource?
helpers/create-router.js - restful routes - 

2 aWhat do you notice about the folder structure? Whats the client responsible for? 
- User input / interaction
- User details
- presentation + styling

b Whats the server responsible for?

3 What are the the responsibilities of server.js?
- seed data
- database

4 What are the responsibilities of the gamesRouter?
- it directs routes on the server within the games api

5 What process does the the client (front-end) use to communicate with the server?
- the webpack - client side React

6 What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
The second argument is "request init" - a method. In this game, the delete and post methods are used.


7 Which of the games API routes does the front-2 end application consume (i.e. make requests to)?
Post, delete, put

8 What are we using the MongoDB Driver for?
To connect the database which contains the games to the server which then connects to the client