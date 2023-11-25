# docker_tuts

Check this link - https://docs.google.com/document/d/1yGTV2E64A9Vd0WnS92Bg-cSuxf3B0sTboFCWUn-DfbE/edit?usp=sharing 

- What is Docker?
What is container?
Docker vs Virtual Machine
Docker Installation
Main Commands
Debugging container
Developing Containers
Docker Compose - Running Multiple services
Dockerfile - Building own docker image
Private Docker repo
Depoying containerized app


```bash
# Run the first Redis container (using host port 6379)
docker run -d -p 6379:6379 --name redis1 redis:5.0

# Run the second Redis container (using host port 6380)
docker run -d -p 6380:6379 --name redis2 redis:6.0


```

```bash

docker logs container_id

```
