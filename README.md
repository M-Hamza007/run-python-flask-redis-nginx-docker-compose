# Getting started with docker-compose, using python/flask, redis, and nginx as a reverse proxy

Compose is a tool for defining and running multi-container Docker applications. You use a Compose file to configure your application’s services. Then using a single command, you create and start all the services.

In this repo, there are 4 folders for python flask, redis, nginx for a reverse proxy, and another nginx folder to serve static pages. Each folder contains its respective Dockerfile, and in main folder there is a docker-compose file for the specification of the composed containers which includes the flask, redis, nginx (as a reverse proxy), and nginx static (to serve static page) containers.

Thorugh this project you can learn:
1. How to run multiple dockerfiles using one docker compose file,
2. Learn to use redis and nginx with python flask,
3. Dcokerize python flask, redis, and nginx,
4. Containerize python flask using redis and nginx, etc.

To run all the container:

1. Run `docker-compose build' to build the containers specified in the docker-compose file.

2. Run `docker-compose up` to start the containers (add -d to run them in the background. Then run `docker-compose stop` when done.)  

3. Browse to http://localhost:80 to see the response from the python flask.

4. Browser to http://localhost/static to see the static pages defined in nginx static container.
