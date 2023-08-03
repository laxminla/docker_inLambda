# docker_inLambda

commands to create docker image inside lamda function

-sudo service docker start
//to start the docker service docker ps
// To see docker process sudo docker build -t laxmi-ecr-repo .
// To build docker image sudo docker run -p 9000:8080 laxmi-ecr-repo:latest 
// Run docker container docker tag laxmi-ecr-repo:latest 388328004932.dkr.ecr.us-east-1.amazonaws.com/laxmi-ecr-repo:latest
//tags//optional sudo docker push 388328004932.dkr.ecr.us-east-1.amazonaws.com/laxmi-ecr-repo:latest 
//push the image to repo
