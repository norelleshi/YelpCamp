# Fullcampground Introduction
  Campground information exchange platform built with Node.js

### Features
* For All Pages*
  * RWD
  * Fuzzy Search
  * Flash messages (err or logout messages, etc.)
  * Error handling (handling the potential issues that may result in security concerns) 
  
* For Landing Page (login)
  * With being authenticated by login, users are allowed to create, edit or delete their own posts, reviews and profiles
  
* For Register Page (sign up) 
  * Avatar upload from local
  * Admin role (admin can manage all posts and reviews)
  * Lock register page if login

* For Index Page (display all campgrounds)  
  * Waterfall layout (alignment for multi sizes of images)
  * Order (the newest posts first)
  * Items' hover brightness
  * Display authors, rating results and prices along with the campground images
  
* For New Page (create a new campground)
  * Image Upload from local
  * Form filling out requirement
  
* For Show Page (show the detailed information of one specific campground)
  * Display location with Google Maps
  * Display time since post was created with Moment JS 
  * Edit & Delete feature (authors are allowed to edit or delete their own posts and reviews)
  * Review summary (display ratings' average score and voting number)
  * Add & edit the post and review on the same page and same position
  * CurrentUser's review first
  
* For User Profile Page
  * Email is set to private
  * Display the owner's campgrounds list
  * profile pic zoom up
  * Avatar will be removed if changing a new one
  
### Tools & Technologies

* Front-end 
  * HTML5
  * CSS3
  * JavaScript
  * jQuery
  * Bootstrap 4
  * Font Awesome
  * Google Fonts

* Back-end
  * NodeJS
  * ExpressJS
  * MongoDB
  * mongoose
  * Databasee Associations
  * Authentication
  * PassportJS
  * Authorization
  * multer and cloudinary
  * dotenv
  * Google Maps API
  * NPM
  * REST
  * Unix(Command Line) Commands
  * moment
  * body-parser
 
### Deployment
* Heroku
* [Click here to view the live demo](https://fullcampground.herokuapp.com/) <br>
  Login username: Guest <br>
  Login password: Guest123
 
