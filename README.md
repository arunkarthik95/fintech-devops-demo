# fintech-devops-demo

docker run --pull=always -d -p 8080:80 arun213/fintech-devops-demo

This runs a static site, for Sonic's dating profile. GitHub actions have been setup to push a new image to DockerHub when new commits are made. 

To kill containers: docker rm -f $(docker ps -a -q)

GitHub Action from: https://github.com/marketplace/actions/build-and-push-docker-images

DockerHub repository: https://hub.docker.com/repository/docker/arun213/fintech-devops-demo
