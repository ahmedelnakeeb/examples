###flask-RESTful
http://flask-restful.readthedocs.org/en/latest/quickstart.html

install flask: https://github.com/irakasleibiltaria/flask-tutorial

```bash
# install flask-RESTful:
$ pip install flask-restful
# start helloworld.py:
$ python helloworld.py
# test:
$ curl http://localhost:5000
```
# start api.py:
```bash
$ python api.py
# GET the list
$ curl http://localhost:5000/todos
# GET a single task
$ curl http://localhost:5000/todos/todo3
# DELETE a task
$ curl http://localhost:5000/todos/todo2 -X DELETE -v
# Add a new task
$ curl http://localhost:5000/todos -d "task=something new" -X POST -v
# Update a task
curl http://localhost:5000/todos/todo3 -d "task=something different" -X POST -v
```