# goalMaker

GoalMaker is an app that helps users to manage their goals. The users will be asked to create and login to their account. Once the user credential is authenticated, 
the app will authorize the user by generating a 48 hours expirable JSON format web token. The authorized user is able to perform actions such as creating, viewing, 
and deleting goals. On the frontend, redux was used to manage the state of the goals. When users make changes to their goals, changes can be seen instantly. 
On the backend, express.js provides routing components that manage user requests with different application’s endpoints. In addition, mongoose helps with the 
connection of MongoDB database and data modeling. RESTful API was implemented to handle the HTTP requests from the client-side server and responses from the backend server. 
This project focuses on the use of M(mongodb)E(express)R(react.js)N(node.js) tech stack, user authentication and authorization using jsonwebtoken, and error and response handling.
