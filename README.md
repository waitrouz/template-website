# template-website

This is an example of how to run a simple HTML/CSS/JS site on Akash.

Demo: https://e9jheis2plf9f313tdfek5f76g.ingress.akash-palmito.org/

## Build and host the Docker image
To deploy on Akash you need a docker image. Build a docker image from the Dockerfile and push it to Docker Hub.

Example:
```
# Change below to your user/repo
docker build -t user/repo:release-v0.1.0 .
docker push user/repo:release-v0.1.0
```

Update deploy.yaml to use your user/repo.

## Deploy on Akash
Use [Akash Console](https://console.akash.network/) to deploy your image.
