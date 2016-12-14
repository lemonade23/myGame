create a folder
create folder js
create folder server
create folder client
create folder nodes_modules
create client/index.html empty
create app.js empty
install nodes : sudo get-install nodejs legacy-apt
install npm : sudo apt install npm
create the projet : npm init
install express : npm install express
install socket.io : npm install socket.io
install mongodb : sudo apt install mongodb-server
create folder data/db
start mongo : mongod --dbpath data --port 2001
entrer dans mongo : mongo
créer la bd mygame : use mygame
créer collections : db.createCollection('account');
créer collections : db.createCollection('progress');
créer user : db.account.insert({username:'bob', password:'bob'});
install mongojs : npm install mongojs


