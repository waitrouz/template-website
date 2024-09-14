# template-website

This is an example of how to run a simple HTML/CSS/JS site on Akash.

Demo: https://k4s8horo5tcvh1kuli8475hqik.ingress.validatornode.com/

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
