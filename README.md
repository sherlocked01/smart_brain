# Smart Brain
A face recognition app created with React.js, Node.js and PostgreSQL.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Features](#features)

## General info
This is an application with a sign-in and registration portal which is capable of detecting one or several faces using Clarifai API and can be extended as an application to get the basic information about a person, for instance, in some conference.

## Technologies
Project is created with:
* React version: 17.0.0
* Node version: 16.3.0

## Features
#### Registration and Sign-in portal:
The user can register himself by entering his name, email and password. If he has registered before, he can directly sign in. 

![Optional Text](../master/smart_brain_frontend/src/components/Logo/Register.png)
#### Home Page:
As the user registers, he gets directed to home page that contains his name with the total entries he has made till date, a search bar and a sign out button.

![Optional Text](../master/smart_brain_frontend/src/components/Logo/HomePage.png)

As he enters the url and clicks on the detect button, the image appears with a box around the face of the person and the entry count increases by one. 

![Optional Text](../master/smart_brain_frontend/src/components/Logo/FaceDetection.png)
