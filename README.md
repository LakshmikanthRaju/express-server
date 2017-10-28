Express generator
	npm install express-generator -g
	express node-express-gen
	npm install, npm start

Mongo DB
	install mongodb
	move to 'mongodb' folder
	run: mongod --dbpath=data , to start db
	Open another cmd and run: mongo -> to get interactive mongo command prompt

Initial Mongo DB Commands
	db
    use conFusion
	db
	db.help()
	db.dishes.insert({ name: "Uthapizza", description: "Test" });    
    db.dishes.find().pretty();