To make this work :

create this folders :

project
  -js
  -server
  -client
  -nodes_modules

INSTALL NODES
sudo get-install nodejs legacy-apt

INSTALL NPM
sudo apt install npm

CREATE PROJECT
npm init

INSTALL EXPRESS
npm install express

INSTALL SOCKET.IO
npm install socket.io

INSTALL MONGODB
sudo apt install mongodb-server
create folder data/db

ABOUT THE DATABASE
start mongo service: mongod --dbpath data --port 2001

TO MANUALLY USE MONGO
mongo
to create a databse : 'use mygame'
to create a table/collection : db.createCollection('account');
to do an insert : db.account.insert({username:'bob', password:'bob'});

TO USE MONGO IN THE GAME, WE NEED TO INSTALL MONGOJS :
npm install mongojs
