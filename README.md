# burger
This is hw assignment 14 for U of U bootcamp

This application is built using node, handlebars, and JS. 
It stores user input via mysql, using heroku as a dynamic host.

The directory structure is as follows:

├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    ----Partials
        ----burger-block.handlebars
    └── layouts
        └── main.handlebars

You can view the application here: https://radiant-refuge-10719.herokuapp.com/

And github repo here: https://github.com/jonvictory/burger