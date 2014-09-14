# Sails-Neo4j Adapter

#### Installation

**First:**

        cd into your project folder


**For install salis-neo4j:**

        npm install --save-dev sails-neo4j

    
*This should install the latest version*


**Then:**

Edit with your favourite text editor the file  *config/adapters.js**

**Add 'neo4j' adapter under *module.exports.adapters* section:**


    "neo4j": {
        "module": "sails-neo4j",
        "debug": true,
        "protocol": "http://",
        "port": 7474,
        "host": "localhost",
        "base": "/db/data/"
     }

####This is all! Now you are ready to start!####
	

If you have any questions:
[![Gitter chat](https://badges.gitter.im/natgeo/sails-neo4j.png)](https://gitter.im/natgeo/sails-neo4j)
