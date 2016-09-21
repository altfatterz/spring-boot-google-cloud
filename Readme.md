Spring Boot Hello World app running on [Google Cloud](https://cloud.google.com/) using the [Flexible Environment](https://cloud.google.com/appengine/docs/flexible/java/dev-java-only) (in Beta, Java 8 Runtime, Docker support)

1. Install [Google Cloud SDK](https://cloud.google.com/sdk/)
2. Install [Docker](https://docs.docker.com/engine/installation/)
3. $ git clone https://github.com/altfatterz/spring-boot-google-cloud
4. $ cd spring-boot-google-cloud
5. $ mvn package docker:build
6. $ cd target/docker
7. $ gcloud app deploy
