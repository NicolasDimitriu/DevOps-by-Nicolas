# LAB 1

## Short Description
We will achieve creation a documented project on Node.js of a simple web server displaying a "Hello world!" message on a home page.

## Functionalities

1)Start a project
2)Initialize a Node.js package
3)Create a Node.js script
4)Create a web application using the Express package
5)Create a CHANGELOG.md file
6)Describe the project in a README.md file




## Installation Instructions


Install a text editor, for example Sublime text.
Install Git.
Install Node.js.
Open a command-line interface: Bash


## Initialize a Node.js package

We initialize a Node.js package running this command:npm init -y then we run : npm test

## Create a Node.js script

We create a file index.js with the following content:
str = "Hello Node.js!"
console.log(str)

We run the Node.js script in the terminal: node index.js
We run the NPM script with the command: npm start

## Create a web application using Express package

We Install the Express package : npm install express

We add this command  to  package.json:
"dependencies": {
    "express": "^4.17.1"
  }

We modify the index.js file so it van be accesed online.
Then we run the npm start script like in the previous step.
