# Jenkins Blueocean
Run Jenkins in docker-compose

## Start
```
docker-compose up -d
```

1. Browse to http://localhost:8080  
![Unlock Jenkins](https://i.imgur.com/AKI7lWg.png)

2. Get administrator password  
```
docker-compose logs jenkins
```  
![Imgur](https://i.imgur.com/aFNXw4E.png)


## Reference
* [Running Jenkins in Docker [jenkins.io]](https://www.jenkins.io/doc/book/installing/#downloading-and-running-jenkins-in-docker)