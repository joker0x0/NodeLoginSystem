# NodeLoginSystem
This is a simple login system using MongoDB and local strategy with NodeJS

Firstly, open mongod.exe on your computer
Secondly, go to http://127.0.0.1:3000/setup (or http://localhost:3000/setup) to make an admin account
Thirdly, use admin and pass as your credentials to login

You can make your own routing system and authenticate them using isLoggedIn() function as a second parameter in your routing function

Don't forget to use "npm install" to install all dependencies required for the project.

Hope this was useful :)

You may change few things for security like the session secret phrase and to make the password more dynamic instead of hard coding it in the application itself
