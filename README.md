# **Hello Nodejs, Docker, Kubernetes**

### Docker build 

```
$ docker build -t hello-node:v1 .
```

### Kubernetes Deployment

```
$ kubetctl create -f service-deployment.yaml
```

### Kubernetes StatefulSet

```
$  kubectl create -f service-statefulset.yaml
```