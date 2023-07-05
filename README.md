# Passport Login Page

This code provides a simple implementation of user authentication and registration using Node.js, Express, PassportJS, and EJS templating engine.

## Features

* User registration with hashed passwords using `bcrypt`.
* User authentication using PassportJS local strategy.
* Session management using `express-session`.
* Flash messages using `express-flash`.

## Installation
To install this project, follow these steps:

* Clone the repository using `git clone https://github.com/YoungKing-Joshua/Passport-Login_Page.git`.
* Install the dependencies using npm install.
* Rename the .env.example file to .env and update the values with your own environment variables.
* Start the server using npm run devStart.

## Usage
Once the server is running, you can access the login page at `http://localhost:3000/login`. From there, you can register a new user or login with an existing user. After logging in, you will be redirected to the dashboard page where you can view your personal information.

If you attempt to access the dashboard page without logging in, you will be redirected to the login page.
