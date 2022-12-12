# Mongo (3.2) Cheat Sheet

[Docs](https://www.mongodb.com/docs/v3.2/)


## Find

```sh
db.collection.find({_id: ObjectId("sha")}).pretty()
```

## Update

Update one key of a document.

```sh
 db.repos.update({_id: ObjectId("sha")}, { $set: { key: value }})
```
