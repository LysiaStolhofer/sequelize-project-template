# Sequelize-project-template

_Create your own Sequelize-Template._

--------------------------------------------------------------------------------------------------------------------------------------
## Instructions

  1) Create a new local MYSQL database called 'todolist', but don't create any tables.
  2) Notice how there are no config or models folders?
  3) In terminal, run `npm i`
  4) In terminal, run `npm i --save-dev sequelize-cli` 
  5) In terminal, run `npm i -g npx`  (You'll only have to do this once, ever, on this machine).
  6) In terminal, type in the following commands (hit enter after each): 
     1) `npx sequelize init:models`
     2) `npx sequelize init:config`
  7) Step 6 should have created a config and a models folder for us. Navigate to the config folder, open `config.json`, and modify as per        instructor's instructions to use .env file.
  8) Navigate to the models folder and create a new file called `todo.js`. Along with instructor, create a Todo model with columns for          "text" (DataTypes.STRING), and "complete" (DataTypes.BOOLEAN).
  9) Navigate to the server.js file and require all of our models by requiring the models folder. Save this to a variable and name it "db".
  10) Sync the models by running db.sequelize.sync() after we start the express server.
  11) In your terminal, run `npm run watch`. Check MYSQL Workbench to see if a Todos table was created.  If so, you were successful. If           not, check your terminal for any errors.
  12)  Now let's complete the `routes/api-routes.js` file to make the app work.
-------------------------------------------------------------------------------------------------------------------------------------
## Features :computer:

 - Sequelize
 - JavaScript
 - Api Routes
---------------------------------------------------------------------------------------------------------------------------------------
## Structure 

- :file_folder: .vscode
  - :page_facing_up: launch.json
  - :page_facing_up: settings.json
- :file_folder: config
  - :page_facing_up: config.json
- :file_folder: models
  - :page_facing_up: index.js
  - :page_facing_up: todo.js
- :file_folder: public
  - :file_folder: css
    - :page_facing_up: style.css
  - :file_folder: js
    - :page_facing_up: view.js
  - :page_facing_up: api-routes.js
- :page_facing_up: .DS_Store
- :page_facing_up: .eslintc.js
- :page_facing_up: .gitignore
- :page_facing_up: .jsdoc.json
- :page_facing_up: README.md
- :page_facing_up: package-lock.json
- :page_facing_up: package.json
- :page_facing_up: schema.sql
- :page_facing_up: server.js
--------------------------------------------------------------------------------------------------------------------------------
:earth_americas: Coming soon!
