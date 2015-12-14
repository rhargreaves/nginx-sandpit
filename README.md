# nginx-sandpit
NGINX Experiments

# Installation
Build the docker image:

```
$ docker build -t nginx .
```

# Usage
Run the docker image:

```
$ docker run -p 80:80 -e FOO=bar nginx
```

Test NGINX:

```
$ curl -v http://localhost/hellolua
```

