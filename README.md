# XivTech
This is my Kubernetes DevOps Hiring Assignment. I have created a sample html file. This application is deployed using a deployment and is made available in the internet through a service.

The below are my commands

Get the nodes: 
``` kubectl get nodes```

Create the deployment and service:

``` kubectl apply -f deployment.yaml```

``` kubectl apply -f service.yaml```

Port forward the service to view the app

``` kubectl port-forward svc/hello-world-service 8080:80```
