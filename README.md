### CMD

 **Mongodb** 
```
mongodb://127.0.0.1/?replicaSet=bigchain-rs
sudo mongod --replSet=bigchain-rs
```

 **Rethinkdb** 
```
r.db('bigchain').table('bigchain').count()
r.db('bigchain').table('backlog').count()
r.db('bigchain').table('votes').count()
r.db('bigchain').table('backlog').withFields('id').changes()
```