# mongodb-playground
 A Docker Compose project that spins up an instance of MongoDB with pre-propulated data in the database named `fruit`.
 
You can use this playground the experiment with executing queries in MongoDB.

To see all the documents in the `apples` collection run the following command from within the MongoDB shell:

```
db.apples.find()
```

To see all the documents in the `oranges` collection run the following command from within the MongoDB shell:

```
db.oranges.find()
```
 
# Installation

If you have the current verson of Docker Desktop installed, run the following command to get the playround up and running:

```
docker compose up
```

Otherwise, execute the following command if you have `docker-compose` installed.

```
docker-compose up
```

The access credentials are:

* username: `root`
* password: `password`

You'll be running MongoDB in a Linux container accessible via `localhost:27017`.

The project ships with a web client that is accessible at `http://localhost:8081`.
 
