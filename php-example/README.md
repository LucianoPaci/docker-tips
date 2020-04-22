# Build single container

```
docker build -t <name-for-container> <directory>

docker build -t hello-world .
```

# Run container

- Listening to Port 80 of the HOST
- Sending requests to Port 80 of the container

```
docker run -p <hostPort>:<containerPort> <name-for-container>

docker run -p 80:80 hello-world
```
