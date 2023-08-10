# Kubernetes Test Project 

## Creating a pod using MongoDB

## How to run

### Copy the following commands in the terminal to create pod
* kubectl apply -f mongo-secret.yaml
* kubectl apply -f mongo.yaml
* kubectl apply -f mongo-configmap.yaml
* kubectl apply -f mongo-express.yaml

### Show all information of pod and verify it's running
* kubectl get pod -o wide

### Check if service was created
* kubectl get service


* NOTE: mongo-secret.yaml file not uploaded, you will have to create one to run this project
