# Eat-Da-Burger
Burger logger with MySQL, Node, Express, Handlebars and a homemade ORM!!

OVERVIEW

Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.

Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page.

The app will store every burger in a database, whether devoured or not.

Directory structure:

.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   ├── assets
│   │   ├── css
│   │   │   └── burger_style.css
│   │   └── img
│   │       └── burger.png
│   └── test.html
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars

TECHNOLOGIES USED:

MySQL, Node, Express,Express-Handlebars and a homemade ORM 
jQuery,HTML,css,javascript.
We npm install and save all these packages.
All the dependencies are shown in package.json, which we created using npm init in our terminal.

