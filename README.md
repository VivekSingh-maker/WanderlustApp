1.Overview

The "WanderLust Application" is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js), designed as a feature-rich as Airbnb. It enables users to explore a wide range of accommodations, view detailed property information, make secure bookings, and efficiently manage their own property listings, replicating the core functionalities of Airbnb to provide a seamless experience for both guests and hosts.

---------------------------------------------------------------------------------------------------

2.Features

User-side features

Signup

Login

Logout

Add new Place

Edit your Place

Delete your Place

Rating

Comments

 
Developer-side features

Form validations in frontend and backend

Fully Responsive Navbar

Use of 404 page for wrong urls

Relevant redirects

Redirect to main page after login

Routes protection

Middleware for verifying the user in backend

Use of different HTTP status codes for sending responses

Standard pratices followed

Followed MVC Architecture

Client-side Validation

Custom Error Handling

Validation for Schema

Handling Delete Places

Used Web Cookies and signed Cookies

Included success and error flash

Authentication

Authorization

Used Passport for configuring strategies and for encrypting and decrypting the password

Store Images and Files in Cloud 

---------------------------------------------------------------------------------------------------

3.Tools and Technologies

HTML

CSS

Bootstrap

JavaScript

Node.js

Express

EJS

Restful APIs

MongoDB

---------------------------------------------------------------------------------------------------

4.Dependencies

Following are the major dependencies of the project:

cloudinary

connect-flash

cookie-parser

dotenv

ejs

ejs-mate

express

express-session

joi

method-override

mongoose

multer

multer-storage-cloudinary

passport

passport-local

passport-local-mongoose

---------------------------------------------------------------------------------------------------

5.Dev-dependencies

Following are the major dev-dependencies of the project:

nodemon

concurrently

---------------------------------------------------------------------------------------------------

6.Prerequisites

Node.js must be installed on the system.

You should have MongoDB Database.

You should have a code editor (ex: VS Code)

---------------------------------------------------------------------------------------------------

7.Installation and Setup

Install all the dependencies.
       npm i “dependency-name”
       
Create a file named “.env” inside the backend folder. Add data from .env file and substitute your credentials there.

Start the application.
       nodemon app.js
       
Go to http://localhost:3000

---------------------------------------------------------------------------------------------------

8.Backend API

User:

/signup - GET

/signup - POST

/login - GET

/login - POST

/logout - GET

Listing:

/listings - GET

/listings - POST

/listings/new - GET

/listings/:id - GET

/listings/:id - PUT

/listings/:id - DELETE

/listings/:id/edit - GET

Review:

/listings/:id/reviews - POST

/listings/:id/reviews/reviewId - DELETE

---------------------------------------------------------------------------------------------------

9.Frontend Pages

/listings - Home Screen

/signup - Signup Page

/login - Login Page

/listings/new - Add a New Place

listings/:id/edit - Edit your Place

listings/:id/delete - Delete your Place

Listings/:id - Review the Place

---------------------------------------------------------------------------------------------------

10.UI Features

User Authentication: Users can sign up, log in, and log out securely. Passwords are hashed for security.

View Listings: Users can view detailed information about each accommodation, including photos, descriptions, amenities.

Add Listing: User can add new Place including Title, photos, descriptions, price, amenities.

Edit & Delete Listing: User can edit and delete Place which were created by user. User can’t edit and delete created by someone else.

Review Listing: User can also review the place.

Description after hover the Image: Users can view the description of a selected place by hovering over the image.

---------------------------------------------------------------------------------------------------

11.Npm scripts

npm i cloudinary: Cloudinary enables developers to efficiently manage, transform, optimize, and deliver images and videos through multiple CDNs.

npm i connect-flash: The flash is typically used in combination with redirects, ensuring that the message is available to the next page that is to be rendered.

npm i dotenv: Dotenv is a popular npm (Node Package Manager) package used in NodeJS applications to manage environment variables.

npm i joi: The most powerful schema description language and data validator for javascript.

npm i multer: Multer is a node.js middleware for handling multipart/form-data, which is primarily used for uploading files.

npm i passport: Passport is Express-compatible authentication middleware for Node.js.

npm i cookie-parser: cookie-parser is a middleware of Node JS used to get cookie data. To get cookie data in ExpressJS, req.cookies property is used. req.cookies is an object that contains cookies sent by request in JSON after parsing. Cookie Parser can get both unsigned and signed cookies.

---------------------------------------------------------------------------------------------------

12.Useful Links

Project Link

GitHub Repo: https://github.com/VivekSingh-maker/WanderlustApp

Hosted URL: https://wanderlustapp-h4hg.onrender.com/listings


Official Documents Link

npmjs Docs: https://www.npmjs.com/

MongoDb Docs: https://www.mongodb.com/docs/manual/introduction/

React.dev Docs: https://react.dev/learn


Download Link

Nodejs Download: https://nodejs.org/en/download/package-manager

VS Code Download: https://code.visualstudio.com/download

---------------------------------------------------------------------------------------------------

13.Contact

Email: vivekpcmsingh@gmail.com

Linkedin: https://www.linkedin.com/in/vivek-singh-a4ab1919




