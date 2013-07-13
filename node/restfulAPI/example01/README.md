###node-restful
Example from:
http://benaugarten.com/node-restful/

CURL examples:
https://stripe.com/docs/api#charges \
http://curl.haxx.se/docs/httpscripting.html

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
Registers the following routes:

GET /resources
GET /resources/:id
POST /resources
PUT /resources/:id
DELETE /resources/:id
```
```bash
$ curl http://localhost:3000/resources
$ curl http://localhost:3000/resources -d title="koxme" -d year="1980"

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
