# Hello World from Alpine
This Dockerfile allows you to create an image based on Alpine Linux that displays the message "Hello world from Alpine!".<br>

## Docker
1. Build the Image<br>
`docker built -t hello-world-alpine current folder`<br>
2. Create a tag<br>
`docker tag hello-world-alpine docker-username/repository-name:tag-name`<br>
3. Push the Image<br>
`docker push docker-username/repository-name:tag-name`<br>


>**Note:**  This image displays the message for only 1 hour. Be cautious when using this in Kubernetes pods, as they may terminate after the sleep period ends.

