MERN STACK BLOGGING WEBSITE

Welcome to the MERN Stack Blogging Website! This project is a full-stack blogging application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack.
TABLE OF CONTENTS
    Introduction
    Features
    Prerequisites
    Getting Started
        Setting up MongoDB
        Setting up the Backend
        Setting up the Frontend
    Running the Application
    Usage

INTRODUCTION
 A basic blogging platform where users can create, view, edit, and delete blog posts. They can also navigate in between pages.
Login using username and password. Users can also signup if no account available. 
An access token is generated after login to store activity.
Blogs are distributed in various categories(sports, music, fashion, movies, Tech). Users can select whichever category they want.
Users can also change the image displaying with their blog. 
Comments can also be done or deleted.
PREREQUISITES
    Node.js and npm installed
    MongoDB installed locally or a MongoDB Atlas account
    Material UI account

Getting Started
npm create-react-app

Setting up MongoDB
If you haven't already, sign up for a MongoDB Atlas account or install MongoDB locally. I used mongoose to run.

Setting up the Backend

Navigate to the backend directory:
cd server

Install dependencies:
npm install

Configure the environment variables:
Create a .env file in the backend directory and add the following:
    PORT=8000
    MONGODB_URI=your_mongodb_uri
    SECRET_KEY=your_secret_key
    Replace your_mongodb_uri and your_secret_key with your MongoDB connection string and a secret key for JWT authentication.

Setting up the Frontend
Navigate to the frontend directory:
cd client

Install dependencies:
npm install

Configure the environment variables:
    REACT_APP_API_URL=http://localhost:8000

Running the Application
Start the backend server:
npm start

Start the frontend development server:
npm start

Visit http://localhost:3000 in your web browser to see the application running.

FUTURE SCOPE
Integrating the website with Alan AI to record and save audio Podcasts. 

PREVIEW
![2024-01-29](https://github.com/HiyahgniS/Blog/assets/112013342/7090c93e-4020-46ea-a9bd-cf44fe6cbe4e) 
![2024-01-29 (1)](https://github.com/HiyahgniS/Blog/assets/112013342/58680333-2401-4d6f-8455-ab9e6df0d858)
![2024-01-29 (2)](https://github.com/HiyahgniS/Blog/assets/112013342/1870245b-3fcd-44fa-9994-adc142cdc14f)



