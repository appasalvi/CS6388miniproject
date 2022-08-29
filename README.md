### Mini-Project

The WebGME project inclues 4 petrinet models


1. Free Choice

In Free Choice PetriNet each transition has unique set of inplaces. 	

2. Marked Graph

In a marked graph every place has one and only one outplace and one inplace transition

3. State Machine

In a State Machine each transition has exactly one of each inplace and outplace.

4. Workflow

In a Workflow PetriNet has exactly one source place and one sink place.


### To run the app


1. Start MongoDB in the directory:
`"C:\Program Files\MongoDB\Server\4.4\bin\mongod.exe" --dbpath .\mongodb-data`
There is a batch file that run it. You should modify the path to your MongoDB installation.

2.`npm install`

3.`npm install webgme`

4.`npm start`

Point the broswer to:

http://localhost:8080

5. Import the seed from src/seeds directory

6. Use the simulator in the panel to simulate each model. Fireable transitions have a green border. Unfireable transitions have a red border.

7. Did not get to complete a classification
