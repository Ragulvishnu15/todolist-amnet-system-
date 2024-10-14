#ToDo-list

This project is a basic user management system that allows users to create, update, and delete user information using React and Redux for state management.

#Features
--------------------------
* User management (Add, Update, Delete users)
* Frontend built with React and Redux
* RESTful routes using react-router-dom
* Bootstrap for styling
* Backend integration (if needed for further API functionality)

#Technologies
-------------------
* Frontend: React, Redux, Bootstrap, React Router DOM
* State Management: Redux Toolkit
* Package Manager: npm/yarn
* CSS: Custom and Bootstrap CSS

#Prerequisites
--------------------------
Node.js installed (https://nodejs.org/en/)
npm or yarn installed (comes with Node.js)
Basic understanding of React, Redux, and JavaScript

#Installed Applications/Packages
-------------------------------------
* React (create-react-app)
* Redux (@reduxjs/toolkit, react-redux)
* React Router (react-router-dom)
* Bootstrap (bootstrap)

#Commands Installed
-------------------
npm install to install dependencies (e.g., Bootstrap, Redux, React Router)
npm start to start the frontend
npm run build to create a production build


#Backend Setup
---------------------
Create a Node.js Backend:
mkdir backend
cd backend
npm init -y

#Install dependencies:
-------------
npm install express mongoose cors

#Create server.js for API routes:
-----------
const express = require('express');
const app = express();
const cors = require('cors');

app.use(cors());
app.use(express.json());

// Sample route
app.get('/api/users', (req, res) => {
    res.send([{ name: "Jayaprabha", email: "jayaprabha28@gmail.com", id: 1 }]);
});

const PORT = process.env.PORT || 5000;
app.listen(PORT, () => console.log(`Server running on port ${PORT}`));

#Start the backend server:
------------------
node server.js

#Frontend Setup
Clone or Create a React App:
-----------------------
npx create-react-app frontend
cd frontend

#Install Necessary Packages:
----------------
npm install redux react-redux @reduxjs/toolkit react-router-dom bootstrap

#Structure Your Frontend Components:
---------------
src/
├── components/
│   ├── Home.js
│   ├── Create.js
│   ├── Update.js
├── App.js
├── index.js
├── UserReducer.js

#Bootstrap Styling:
----------------
import "bootstrap/dist/css/bootstrap.min.css";

Run Frontend:
--------------------
npm start

#How to Run the Application
#Backend :
------------------
cd backend
node server.js


#Frontend:
-----------------
cd frontend
npm install
npm start


#Access the Application:
-----------------
The React app should be running at http://localhost:3000, and the backend (if running) at http://localhost:5000.

#Screenshort Output
#Add user
![Screenshot 2024-10-14 203633](https://github.com/user-attachments/assets/6562d029-eab6-423a-9c77-e085c410c342)
#update home page
![Screenshot 2024-10-14 203648](https://github.com/user-attachments/assets/6509cd05-f915-4c58-ae33-8cf90a96ebc7)
#update
![Screenshot 2024-10-14 203708](https://github.com/user-attachments/assets/078c493e-faa3-4a57-aa44-86eb67738728)
#delete
#![Screenshot 2024-10-14 203802](https://github.com/user-attachments/assets/d6f9d8d2-37b9-4a76-a75b-77ffb1434a0a)
![Screenshot 2024-10-14 203605](https://github.com/user-attachments/assets/9d0920b6-f814-4401-844b-912efd0e8615)
