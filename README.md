# spring-eureka-docker
Spring (Boot) Eureka Server with Docker Containerization

Maven Packaging: mvn clean package 

Maven Docker build: mvn clean package dockerfile:build -DdockerImageTags=latest

Maven Docker Push Image to Docker Hub: Maven Docker build: mvn clean package dockerfile:push -DdockerImageTags=latest
