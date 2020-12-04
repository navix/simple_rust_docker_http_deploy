```
$ docker build -t registry.gitlab.com/navix/dhub/depl_test .
$ docker push registry.gitlab.com/navix/dhub/depl_test
$ docker run -p 8008:8008 registry.gitlab.com/navix/dhub/depl_test
```
