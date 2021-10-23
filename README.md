NoSQL: Social Network API
## Description
MongoDB is a popular choice for many social networks due to its speed with large amounts of data and flexibility with unstructured data. This API was built for a social network using Express.js for routing, a MongoDB database, and the Mongoose ODM. 

## Acceptance Criteria
```
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia Core for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia Core
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```
## Technologies Used:
- JavaScript
- Node
- Express
- Mongoose

## Installation

- Install all the dependencies by typing code: npm i
- Download and install MongoDB
- Use the below command to start the server: npm start
- Use Insomnia Core to test API routes 

## Mock-Up

The following animations show examples of the application's API routes being tested in Insomnia Core.

The first animation shows GET routes to return all users and all thoughts being tested in Insomnia Core:

![Homework Demo 01](./Assets/18-nosql-homework-demo-01.gif)

The second animation shows GET routes to return a single user and a single thought being tested in Insomnia Core:

![Homework Demo 02](./Assets/18-nosql-homework-demo-02.gif)

The third animation shows the POST, PUT, and DELETE routes for users being tested in Insomnia Core:

![Homework Demo 03](./Assets/18-nosql-homework-demo-03.gif)

The final animation shows the POST and DELETE routes for a user’s friend list being tested in Insomnia Core:

![Homework Demo 04](./Assets/18-nosql-homework-demo-04.gif)

## Demo
-Link to Demo:
https://watch.screencastify.com/v/WIa0ELVyJhl7ECuFj9xk OR
https://drive.google.com/file/d/12oYe8sAztTcP7n2T_B8pCvQwF0Nt-92F/view 
## Example
- Users API Route  : http://localhost:3001/api/users/ or http://localhost:3001/api/users/{SPECIFIC ID}
- Thoughts API Route:http://localhost:3001/api/thoughts/ or http://localhost:3001/api/users/{SPECIFIC ID}
- Reactions API Route: http://localhost:3001/api/thoughts/{SPECIFIC ID}/reactions

## Usage
This API is used for the social network website 
## License
This project is licensed under the MIT license.