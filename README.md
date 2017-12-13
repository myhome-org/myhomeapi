# myhomeapi

## Refer

* http://frostybay.com/articles/tcp-server-with-nodejs
* https://blog.yld.io/2016/02/23/building-a-tcp-service-using-node-js/#.Wi4IvLT1W9Z
* https://gist.github.com/creationix/707146

## Prerequisites

Install [Docker](https://www.docker.com/) on your system.

* [Install instructions](https://docs.docker.com/installation/mac/) for Mac OS X
* [Install instructions](https://docs.docker.com/installation/ubuntulinux/) for Ubuntu Linux
* [Install instructions](https://docs.docker.com/installation/) for other platforms

## Start
* Run `docker-compose up` to create and start the `app`, and `mongo` containers.
* POST http://localhost:3000/user with body-data: {"name": "", "email":"", password: ""}
* POST http://localhost:3000/login with body-data: {"name": "", "password": ""}
* GET  http://localhost:3000/api/v1/* with header x-access-token="your_access_token"
