# Docker Project

Docker practice in producing containerized applications with Alpine.

2 Containers:

Container 1:
- Simple Alpine container. (Building a Dockerfile).
- Install Node (Setting up container).
- Simple Node/express server to serve an index.html (Running a process and exposing a port).
- A displayed image is stored on the local machine (Docker-compose and volume mapping).

Container 2:
- Simple Alpine container. (Building a Dockerfile).
- Install Nginx. (Setting up container).
- Copy a nginx .config file from the local machine to the container. (Copying files across).
- Map the port of the serving container to port 1234, of my localhost (Docker-compose and service port mapping/service dependancies).

## To run

```bash
docker-compose up # --build
# open http://localhost:1234
# ^c to close or use <docker ps> then `docker kill <container-id>`
```
