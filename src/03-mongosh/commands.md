# Connect to container

```sh
docker-compose exec mongodb bash
```

# Connect with mongosh

```sh
mongosh "url local o atlas"
mongosh "mongodb+srv://elvisadmin:43A62a3EDqKgYf2j@mongodb101.0bvok.mongodb.net/"
mongosh "mongodb://root:password@localhost:27017/?tls=false"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```