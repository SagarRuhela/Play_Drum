## Docker

To build a docker image for the todo-list-app and run it inside a container execute

```sh
docker build -t <Image_name> .
```

To run your Docker Image

```sh
docker run -d -p 80:80 <Image_name> 
```
