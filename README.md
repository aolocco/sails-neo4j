Sails-Neo4j Adapter; 



First:
cd into your project folder

For install salis-neo4j:
npm install --save-dev sails-neo4j
this should install the latest version

Then:
edit with your favorite text editor config/adapters.js

Add 'neo4j' adapter under "module.exports.adapters" section:

"neo4j":
{ "module": "sails-neo4j", 
  "debug": true, 
  "protocol": "http://", "port": 7474,
  "host": "localhost", 
  "base": "/db/data/" }

Now you are ready to start!


For now if you have any questions:
[![Gitter chat](https://badges.gitter.im/natgeo/sails-neo4j.png)](https://gitter.im/natgeo/sails-neo4j)
