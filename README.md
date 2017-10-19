# spring-cloud-eureka-server

docker images -a
docker ps -a
docker rm
docker rmi
mvn clean package -Dmaven.test.skip docker:build
docker run -p 10000:10000 -t spring-cloud/eureka-server