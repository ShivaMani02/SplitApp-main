## Introduction
This is a side project I've been working on. A full stack expense spliting app - splitwise clone made using the MERN stack (MongoDB, Express, React & Nodejs), specially designed to split group expense between friends. With this application, you can add your expense details and get an whole expense analytics feature - Group Balance, Monthly amount spend, Catagory wise expense spending graph etc.

## Key Features
- Create user groups and track group expense 
- Keep track of shared expenses and settle your corresponding balances in a convenient and personalized way. 
- Get Analytical graphs to understand your expenditure trend 
- Multiple user registration.
- Authentication using JSON web token (JWT) 

## Demo
Check out the video tutorial on **Dev. Shivansh Vasu** channel:
- [YouTube Channel](https://www.youtube.com/@shivanshvasu/videos)


## Technologies used
This project was created using the following technologies.

#### Frontend

- React JS
- Redux (for managing and centralizing application state)
- Axios (for making api calls)
- Material UI (for User Interface)
- Gravitar (for user profile picture)

#### Backend

- Express
- Mongoose
- JWT (For authentication)
- bcryptjs (for data encryption)

#### Database
MongoDB

## Configuration and Setup
In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine. 
- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)
- Split your terminal into two (run the client on one terminal and the server on the other terminal)

In the first terminal
```
$ cd client
$ npm install (to install client-side dependencies)
$ npm start (to start the client)
```

For setting up backend
- cd create a .env file in the root of your directory.
- Supply the following credentials

```
PORT=3001
MONGODB_URI=
ACCESS_TOKEN_SECRET=

```
Create your mongoDB connection url, which you'll use as your MONGODB_URI

Provide some random key in ACCESS_TOKEN_SECRET or you could generate one using node enter the below command in the terminal to genrate a random secret key 

In the second terminal (*in the project root directory (back-end))

```
$ npm install (to install server-side dependencies)
& npm start (to start the server)
```
