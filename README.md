# K8s-LetsEncrypt Tutorial

## First set up a working NGINX cluster for any specific domain of yours or follow my YouTube video to set this up on Minikube and expose the service to the outside work using ngrok

## Set up CertManager

```
kubectl create namespace cert-manager
kubectl apply --validate=false -f https://github.com/jetstack/cert-manager/releases/download/v0.12.0/cert-manager.yaml

```


### Wait till all the pods are up and running

```
kubectl get pods -n cert-manager
```
