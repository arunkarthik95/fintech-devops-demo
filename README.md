# fintech-devops-demo

docker run -d -p 8080:80 arun213/fintech-devops-demo

docker rm -f $(docker ps -a -q)

This runs a static site. GitHub actions have been setup to push a new image to DockerHub when new commits are made. 
