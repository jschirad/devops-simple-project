# devops-simple-project



### First chapter

Setup Jenkins Server

```
docker pull jenkins/jenkins_latest

docker run -d -v jenkins_home:/var/jenkins_home -p 8080:8080 --restart=on-failure jenkins/jenkins:latest

localhost:8080 

docker exec -i -t [ CONTAINER NAME ] cat /var/jenkins_home/secrets/initialAdminPassword   

```