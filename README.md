
# Installing Jenkins and create a multibranch pipeline
> [video 1](https://www.youtube.com/watch?v=pMO26j2OUME&ab_channel=TechWorldwithNana) |
[video 2](https://www.youtube.com/watch?v=tuxO7ZXplRE&ab_channel=TechWorldwithNana)


```bash
docker run -p 8080:8080 -p 50000:50000 -d -v /home/alb/dev/jenkins/jenkins_home:/var/jenkins_home jenkins/jenkins:lts
```

Cerco il log in base il container id in esecuzione
```bash
docker ps
docker logs f4009f7a33b2
```
Initial password
8c010ff3875e4d218603f83cabfda50d

User Jenkins:alb/alb# demo-app
