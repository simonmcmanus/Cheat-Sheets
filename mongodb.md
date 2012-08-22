mongo events --eval "db.dropDatabase();"


Show all in collection events:

db.events.find().pretty()