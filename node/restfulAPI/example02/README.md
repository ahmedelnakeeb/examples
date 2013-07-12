Example from:
http://benaugarten.com/blog/2013/01/31/restful-a-better-rest-api-using-node-dot-js-with-express/

###install
```bash
$ npm install
```
###start
```bash
$ node index.js
```
###curl
```bash
$ curl http://localhost:3000/xxxx
$ curl http://localhost:3000/xxxx -d title="koxme" -d year="1980"

$ curl http://localhost:3000/resources/51dfc8f592d06b1b11000003
```
###mongodb:
```bash
start mongodb server:
$ mongod

mongodb client:
$ mongo
> help
> show dbs
> use resources
> db.resources.find()
...
```