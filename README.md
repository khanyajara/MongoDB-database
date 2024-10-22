Initiating Mongo shell

To Initiate or start Mongo shell type the following command :

 mongosh

Creating a database

To create or switch to CodeTribe dataBase use the following command :

use CodeTribe


To create collections named Facilitators, Trainees and Projects  use the following commmands:

 db.createCollection('Facilitators')

 db.createCollection('Trainees')

 db.createCollection('Projects')



 To insert Data into the Facilitators database type in the following commands :

 db.Facilitators.insertOne({name:"KB", location:"Kimberley", course: "backend development"})



  To insert Data into the Trainees database type in the following commands :

db.Trainees.insertOne({name:"khanya", location:"Kimberley", facilitator:"KB"})



  To insert Data into the Projects database type in the following commands :

  db.Projects.insertOne({name:"khanya", course: "backend development", lesson:"Mongodb commands"})