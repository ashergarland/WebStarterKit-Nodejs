WebStarterKit-Nodejs
====================

This is a starter kit for building Nodejs web applications. It handles all the tedious setup process for you so you can quickly get started building your web application. 

## Technologies:
* Server - NodeJS
* Web Framework - ExpressJs
* Database - MongoDB
* Mongoose - MongoDB NodeJs framework
* Handlebars - HTML templator 
* Procfile - Used for deploying to Heroku

## Installation
1. Clone the repo and change it's name to the name of your application
  * git clone https://github.com/ashermccall/WebStarterKit-Nodejs.git your-application
2. Open terminal -> go to directory where you cloned the repo
3. Delete the .git file
  * Mac
    * rm -rf .git
  * Windows
    * RMDIR .git
4. Initialize this repo as your own new github repo for your application
  * Mac
    * Github GUI: https://help.github.com/articles/how-do-i-add-repositories/
    * Command Line: https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/#platform-mac
  * Windows
  	* Github Gui: https://help.github.com/articles/adding-repositories-with-github-for-windows/
  	* Command Line: https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/#platform-windows
5. run: npm install
6. run: node app.js
7. Open browser and go to: http://localhost:3000/

If you see Hello World then the installation was (probably) successful.