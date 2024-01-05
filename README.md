# Server-CloudMFJ

minikube start

minikube addons enable ingress
minikube tunnel

kubectl create namespace cert-manager

kubectl apply -f https://github.com/cert-manager/cert-manager/releases/download/v1.12.7/cert-manager.yaml

kubectl apply -f ./Server-CloudMFJ

 
