### 获取Docker image
docker pull luckyzune/jenkins

### 运行
docker container run -d -p 8080:8080 -v /var/run/docker.sock:/var/run/docker.sock luckyzune/jenkins:lts