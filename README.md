# ToDo_List

This is a Todolist web application that uses ejs templating for front-end and uses Node.js and Express for backend. The todo items are stored on a MongoDB database. Initially when you open the application you see three by default added items and you can add more items by adding yourselves and when you add an item a post route is triggered which creates a database item and stores it inside the relevant database. Each route URL has its own database created which stores separate data. You can just access a new route and then create a todolist for that specific route and I used Lodash npm package to format all routes.

Body-parser npm package is used to access the form body values from the ejs template to create a new item. Then I used data.js which has two methods inside which are used to generate the current formatted date and day.

HOW TO RUN: You can either download the files, and then run "npm install" inside the installation directory to install all the npm packages used within the application and then open a new terminal window and run the MongoShell command "mongod" and then inside the first window run the command "node app.js" to run the app. You can also access the application at : https://thawing-garden-63532.herokuapp.com/

Here is a Preview:
[link to todolist!](https://thawing-garden-63532.herokuapp.com/)
