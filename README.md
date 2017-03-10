# seek-assessment-backend
GDP Test Interview Backend System

## Requirement
* Latest node.js server (v6.9.1)
* A MySql DB server

## How to setup
1. Clone the project
2. Create a new database name `seek` with mysql db server
3. Import `init.sql` file
4. Run `npm install` or `npm i`
5. Run `npm start` to start the server
6. Visit `localhost:3000`

## How to use
1. Go to `localhost:3000` and you will see a menu page.
2. Choose the menu, and it will direct you to the listing page of the management type you have chosen.
3. You are allow to create, edit, delete on Advertisement, Rules and Privilege.
4. You are not allow to do any action on Customer, except you can assign them privileges (in Privilege Management).
