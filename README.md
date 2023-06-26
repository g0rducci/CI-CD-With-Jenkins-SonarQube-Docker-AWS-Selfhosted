# CI/CD-With-Jenkins-SonarQube-Docker-AWS-Selfhosted
CI/CD Pipeline using Jenkins, SonarQube, Docker and AWS Selfhosted EC2

## Technologies:
- Jenkins
- Docker
- SonarQube
- AWS EC2

- Source Code Twitter Dockerized App
- https://github.com/g0rducci/sample-twitter-app-docker

## Tasks:

### 1. Create three EC2 instances with a security group that allows all traffic from the internet.
### 2. Install Jenkins, SonarQube, and Docker to each EC2 instance respectively.
### 3. Connect Jenkins instance to SonarQube, Docker instances, and to itself also through SSH.
JENKINS TO JENKINKS
JENKINS TO SONARQUBE
JENKINS TO DOCKER
### 4. Make those SSH connections password-less generating an ssh-key and saving their IDs.
### 5. Install plugin - SSH2 Easy on Jenkins and set server.
### 6. Set server groups and server sites of Jenkins, SonarQube, and Docker.
### 7. Create a new job at Jenkins and add a git link for your repository with the branch you want to build and deploy.
### 8. Add build steps in configuring the pipeline to copy code from Jenkins workspace to SonarQube and Docker instance for analysis and deployment.


Creating EC2 Instances
If you are new to AWS, you can refer to this for creating your account on AWS.

Now, on the AWS dashboard click on "Launch a virtual machine"


Install Sonarqube

INSTALAR DOCKER DAEMON
https://docs.docker.com/engine/install/ubuntu/

nano docker-compose.up

DOCKER COMPOSE UP -D
https://github.com/SonarSource/docker-sonarqube/blob/master/example-compose-files/sq-with-postgres/docker-compose.yml

localhost:9000


este ID se pone en Jenkins
y el Token en secret text en Jenkins
sonar.projectKey=CI-CD-Pipeline
token
sqa_d3487e64d97469e9e6d408e7f36618807b3af54e
/////////////////////////
