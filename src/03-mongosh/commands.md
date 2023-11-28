## Connect to container

```sh
docker compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://admin:admin@atlasdemo.qkwnvwu.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("ecommerce")
db.productos.find()
```

```sh
use("ecommerce")
exit
```
