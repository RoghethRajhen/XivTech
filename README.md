# XivTech
This is my Kubernetes DevOps Hiring Assignment. The below are my commands

Get the nodes: 
``` kubectl get nodes```

Create the deployment and service:

``` kubectl apply -f deployment.yaml```

``` kubectl apply -f service.yaml```

Port forward the service to view the app

``` kubectl port-forward svc/hello-world-service 8080:80```
