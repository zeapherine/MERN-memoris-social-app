# Memories

 [Live site](https://memoriesbank.netlify.app)

![Memories](https://i.ibb.co/VqYGh26/memoriesbank.png)

## Introduction

This is a code repository for FullStack Mern Social media site.

Using React, Node.js, Express & MongoDB. - from start to finish. The App is called "Memories" and it is a simple social media app that allows users to post interesting events that happened in their lives. This app is build by functional component.
(This app is just for learning purposes and new features might be added later on. )
(application in development)

State Management : Redux. </br>
Authentication : JWT and Google oAuth. </br>
Frameworks and Libraries: React, Express, Mongoose. </br>
middlewares: Redux-thunk for async actions,

# LOGIN ID for testing

       username: johnwick@gmial.com
       password: 123

       or create your own user account.

       or login with google (google login doesn't save the email in the backend.

## Features :

-Search Post by Name and Tags. </br>
-Like, create, delete, edit post after login (protected routes) </br>
-Comments. </br>
-Custom Sign In and Google OAuth sign in. </br>
-Pagination.</br>
-recomendation based on tags.

# Host plateform :

## Client : Netlify

## Server : Heroku

## Database : MongoDB Atlas

(site might load slow since it is hosted in free tier)

Setup:

- run `npm i && npm start` for both client and server side to start the app
- create .env file and:
- add `CONNECTION_URL` for mongoDB in server.js in server.
- add `PORT` for api endpoint in api.js in client.
- add `GOOGLE_CLIENT_ID` in Auth component in client.

TODO: rename post message, refactor reducers, add some cool memories, maybe clickable tags, fix update functionality
TODO: Add comment section
TODO: Add live chat features
TODO: Redo the UI Design
