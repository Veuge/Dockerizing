# Docker DEV container for nodejs applications with Hot module replacement

## TO RUN
### Requirements
1. docker and docker-compose cli
2. A nodejs application setup, package.json file.

### Steps
1. Copy the Dockerfile and docker-compose.yml to the root directory of your nodejs app.
2. From the command line run (make sure to not have any other process running in port 8080): 
```bash
$ docker-compose build
$ docker-compose up
```
3. Open [http://localhost:8080/](http://localhost:8080/)
4. In your host, modify the code. The HMR will update automatically the browser and show the latest changes.

## RESOURCES
[NodeJS guide for docker](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)
[Lessons from Building a Node App in Docker](http://jdlm.info/articles/2016/03/06/lessons-building-node-app-docker.html)