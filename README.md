# maven-jib-plugin
Spring Boot Docker Create İmage

Create Docker Image

./mvnw compile jib:dockerBuild


Run Docker Image

docker run -p 8080:8080 helloworld-jib

