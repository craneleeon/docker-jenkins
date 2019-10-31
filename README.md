# Jenkins image with preinstalled docker kubectl, kubetpl

## Run with command

```Bash
docker run --rm -p 8080:8080 -p 50000:50000 -v `pwd`/home:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock craneleeon/jenkins:latest
```

