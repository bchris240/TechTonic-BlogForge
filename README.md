# TechTonic-BlogForge

TechTonic-BlogForge is a CMS-style blog site where developers can publish articles, blog posts, and share their thoughts and opinions on various technical topics.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## Description

TechTonic-BlogForge is a full-stack web application built using Node.js, Express.js, Sequelize, and Handlebars.js. It follows the Model-View-Controller (MVC) architectural pattern for better organization and scalability of code. The application allows users to:

- Sign up, log in, and log out securely
- Create, edit, and delete blog posts
- Comment on blog posts
- View blog posts and comments

## Features

- User authentication using express-session and bcrypt
- MySQL database with Sequelize ORM for data management
- Dynamic HTML content rendering using Handlebars.js templates
- Responsive design for seamless user experience across devices
- Follows RESTful API conventions for routes and controllers
- Utilizes environment variables for configuration management

## Installation

To run the application locally, follow these steps:

1. Clone the repository:
   git clone <git@github.com:bchris240/TechTonic-BlogForge.git>
   
Navigate to the project directory:
cd TechTonic-BlogForge

Install the dependencies:
npm install

Set up the database:
Create a MySQL database
Configure the database connection in config/config.json

Run the application:
npm start
Access the application in your web browser at http://localhost:3000.

Usage
Visit the homepage to view existing blog posts and sign up or log in to create new posts or comment on existing ones.

Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

Credits
This application was developed by [Christopher Brown] (GitHub).
