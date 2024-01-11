## Comandos Shell

#### iniciar docker-compose
```sh
docker-compose -f docker-compose -d
```

#### conectarse al contenedor
```sh
docker-compose exec mongodb bash
```

####


## Comando Mongo
```sh
mongosh "mongodb://root:root@localhost:27017/?authMechanism=DEFAULT"
mongosh "mongodb+srv://mongo-learning:mongoadmin123.@mongodb101.8x9hwuy.mongodb.net/test"
```


```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```
