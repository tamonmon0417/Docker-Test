$ docker build -t myimage .
$ docker run -d -p 5000:5000 myimage
$ curl http://localhost:5000
