# pouchdb-todo-docker
Dockerized pouchdb todo app - see [todo github repo](https://github.com/nickcolley/getting-started-todo)


Clone repo, then run _docker-compose up_ This will start up two containers:

* couchdb configured for CORS, accessible at [localhost:5984](localhost:5984) (todos db at [localhost:5984/_utils/database.html?todos](localhost:5984/_utils/database.html?todos))
* one with pouchdb todo app accessible at [localhost:8000](localhost:8000) that synchronize with couchdb instance 


