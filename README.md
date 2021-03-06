# freecodecamp-api-projects
RESTful API built with MongoDB, Node.js, and Express for [freeCodeCamp](https://www.freecodecamp.org/learn) APIs and Microservices Certi.

## Table of Contents
* [Introduction](#introduction)
* [Project Samples](#demos)
* [Technologies](#technologies)
* [Features](#features)

## Introduction
This project is a result of my learning the backend basics with FreeCodeCamp APIs and Microservices. Demoing API tests, Node and Databases

## Demos
To complete some sample work I've built five small node.js apps, live demos below. Note the tester can also clone repo and run npm start to run on the local machine. 
* [Timestamp Microservice](https://api-test2022-1.herokuapp.com/timestamp)
* [Request Header Parser Microservice](https://api-test2022-1.herokuapp.com/whoami)
* [URL Shortener Microservice](https://api-test2022-1.herokuapp.com/url-shortener)
* [Exercise Tracker Microservice](https://api-test2022-1.herokuapp.com/exercise-tracker)
* [File Metadata Microservice](https://api-test2022-1.herokuapp.com/file-metadata)

## Technologies
Technologies I used for this project:
* Node.js
* Express.js 
* with NoSQL Database 
* APIs

## Features
### Timestamp Microservice
Timestamp Microservice parses timestamp in milliseconds or date string from the API endpoint and returns returns a JSON with timestamp and date.

### Request Header Parser Microservice
Request Header Parser Microservice gets the IP address, preferred languages, and system info of the client's device.

### URL Shortener Microservice
URL Shortener Microservice allows to post url and receive a shortened URL which could be copied. Visiting the shortened URL will redirect to the original link.

### Exercise Tracker Microservice
Exercise Tracker Microservice allows to create user, to add an exercise to any user, to get user's exercise log optionally for selected period.

### File Metadata Microservice
File Metadata Microservice allows to submit a form object that includes a file upload, on submit receive JSON with file's name, type and size.
