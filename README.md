# Drink Safe LoopBack

The project is generated by [LoopBack](http://loopback.io).

To build this: (RUN ALL COMMAND PROMPTS AS ADMIN TO AVOID ERRORS)

  Install [mongoDB](https://www.mongodb.org/downloads#production).

  Install [nodemon](https://github.com/remy/nodemon) globally
    $ npm install nodemon -g
    
  Install [python](https://www.python.org/ftp/python/2.7.10/python-2.7.10.msi) (<3.0) 

run
  $ npm install -g strongloop
  $ npm install -g gulp

start project (run the following from the project directory)
  $ npm install
  $ npm start

api explorer:
  http://localhost:3000/explorer/

creating new LoopBack models:
  $ slc loopback:model
  ... follow the prompts


Configuring mongo DB
 navigate to the mongo/bin   folder
	$ mongod --dpath C:\ { project path } \project\data
