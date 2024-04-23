## Connect to container

```sh
 docker-compose exec mongodb bash
```
## Connect with mongosh

```sh
 mongosh "mongodb://root:root123@localhost:27017/?tls=false" // local
 mongosh "mongodb+srv://josuadmin:51oNQAv1vZAUGP5x@mongodb101.2goir4g.mongodb.net/" // nube aws
```

```sh
 show dbs
 show collections
```
```sh
  use("platzi_store")
  db.products.find()
```
