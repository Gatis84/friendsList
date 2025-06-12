# Friend's List API

This project is a simple RESTful API built with **Express.js** that allows you to manage a list of friends. You will be able to perform basic CRUD operations and secure the endpoints using authentication.

## Features

- Add a new friend with:
  - First Name
  - Last Name
  - Email
  - Date of Birth
- Retrieve friend details
- Update existing friend information
- Delete a friend from the list
- Authenticated access to all endpoints

## Learning Objectives

- Build a REST API using **Express.js**
- Design and implement CRUD endpoints
- Handle JSON data
- Secure API routes with authentication
    (authentication at the session level using JSON Web Tokens (JWT) for authorized access)
- Use tools like **cURL** and **Postman** for testing API endpoints

## Tools & Technologies

- Node.js
- Express.js
- Postman
- cURL

## Getting Started

1. Clone the repository
2. Install dependencies using `npm install`
3. Start the server using `node index.js` or `npm start` & `npm run start_auth` for `index_withauth.js`
4. Use Postman or cURL ("curl 'localhost:5000/user'","curl --request PUT/POST/DELETE 'localhost:5000/user/johnsmith@gamil.com?DOB=1/1/1971'", ..) to test the API

---

This project serves as a foundation for understanding backend development, API structure, and authentication in a Node.js environment.
