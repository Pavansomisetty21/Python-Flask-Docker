# Python Flask Docker

Build the image using the following command

```bash
$ docker build -t .
```

or

```bash
$ docker build -t image_name .
```

Run the Docker container using the command shown below.

```bash
docker run -it -d -p 5000:5000 --name container_name image_id
```

or


```bash
$ docker run -d -p 5000:5000 simple-flask-app
```

The application will be accessible at http:127.0.0.1:5000 the use the ip `http://<host_ip>:5000`

Instead of last step go to docker desktop and go to image in that add  container with port 5000 and run


then the application is accessible at port 5000
