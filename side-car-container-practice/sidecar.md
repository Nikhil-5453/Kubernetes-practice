This is a sample sidecar application with a main app container and a BusyBox sidecar.

Application code: server.js, package.json
 - We’ll use a simple Node.js app that serves HTTP requests.

Build a DockerImage and push into DockerHub
commands:
```

 docker build -t <your-dockerhub-username>/sidecar-demo:v1 .
 docker push <your-dockerhub-username>/sidecar-demo:v1

```

