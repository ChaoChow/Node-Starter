local-api-server
================

local api server to use with various project to provide local data when external services are not available

Setup
================
1.) Go to https://nodejs.org/en/download/ and download the version of node for your machines OS
    -   "npm" stands for node package manager and is used to download and install other node dependencies. Npm comes installed when you install node. 
    -   To test your installation run "node -v" or "npm -v" in terminal


2.) Clone this project from git


3.) Navigate to this project in your command/terminal run
$ npm install
    -   Should be the same on windows


4.) To start the server while in the project directory in command/terminal run
$ node server.js
    -   In this case server.js is the main file for the project, if you rename server.js to something else reference that new file with the same above command.
    -   You must manually restart your server by running the above command whenever you want to update your server with the latest code. If you dont want to deal with that see the below tool nodemon

5.) Nodemon is a tool that watches your project directory and automatically restarts node whenever it sees and file changes. To install nodemon run the following command while in project directory
$ npm install nodemon


6.) If you install nodemon, to start the server you just run the following command
$ nodemon server.js 


