# Introduction:

We are adding functionality and style to a ToDo App, as laid out in the Objectives below.

The foundation of this project was a simple ToDo app built using MVC Architecture; with "authorization" implemented so that folx can sign up, customize & personalize the app. 

---

> Be sure to add that lovely star 😀 and fork it for your own copy

---

# Objectives

Our primary goals are:
- to enable the user to assign ToDo tasks to other users, without the use of a relational database.

- to style the app so that it's easier to use, more aesthetically pleasing, and visually suited to real world use cases.   

---
# Progress Towards Objectives

[x] Began the project by brainstorming our idea for added functionality and improvements.
[x] Added a dropdown/dialog box to the main page, which populates with all current registered users (/todos.ejs).
[x] Added an async function for a put request that allows users to to assign todo tasks, by updating the userID of a it  (assignTodo() in /main.js; controllers/todos.js)
[x] Styled the app so that it's easier to use and more aesthetically pleasing.
[x] Added images and styling suitable for real world use cases

[x] Ensured functionality of dropdown box
[x] Ensured compatibility of new code with database 
[] Ensured functionality of new put request function

---

# Who is this for? 

- This repo is for anyone looking for a start on adding group functionality to a simple ToDo app, without using a relational database.
- It's also for those looking for help with the various aspects of building a node app with some complex features (intermediates and beginners with a little more experience).

---

# Packages/Dependencies used 

bcrypt, connect-mongo, dotenv, ejs, express, express-flash, express-session, mongodb, mongoose, morgan, nodemon, passport, passport-local, validator

---

# Install all the dependencies or node packages used for development via Terminal

`npm install` 

---

# Things to add

- Create a `.env` file and add the following as `key: value` 
  - PORT: 2121 (can be any port example: 3000) 
  - DB_STRING: `your database URI` 
 ---
 
 Have fun testing and improving it! 😎


