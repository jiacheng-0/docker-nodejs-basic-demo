# Docker + Node.js

Dockerize a Node.js app.

Watch the full [Docker video](https://youtu.be/gAkwW2tuIqE) on YouTube or read the [Docker Tutorial](https://fireship.io/lessons/docker-basics-tutorial-nodejs/) on Fireship.io.

## Source

https://fireship.io/lessons/docker-basics-tutorial-nodejs/

# Screenshots

## Build

![](Pasted%20image%2020250406002235.png)

![](Pasted%20image%2020250406002521.png)

## Run

![](Pasted%20image%2020250406003249.png)

## Validate

![](Pasted%20image%2020250406003257.png)

# Commands

## Build

```
docker build -t jiacheng111/nodejs-demo-app:1.0 .
```

## Run

```
docker run --rm -p 5000:8080 jiacheng111/nodejs-demo-app:1.0
```

- **`--rm`**: This is the key flag. It tells Docker to automatically remove the container's file system when the container exits.

## Validate

- go to http://localhost:5000


# Version with bullseye (no vuls)

## Build

```
docker build -t jiacheng111/nodejs-demo-app:1.1 .
```

## Run

```
docker run --rm -p 5000:8080 jiacheng111/nodejs-demo-app:1.1
```