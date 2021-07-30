**enable the ingress controller**
```
minikube addons enable ingress
```

**kubectl apply commands in order:**
```
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo-deploy.yaml
kubectl apply -f mongo-configmap.yaml
kubectl apply -f mongoexpress-deploy.yaml
kubectl apply -f ingress.yaml
```

**kubectl get commands:**
```
kubectl get pod
kubectl get pod --watch
kubectl get pod -o wide
kubectl get service
kubectl get secret
kubectl get configmap
kubectl get all
kubectl get ingress
```

**adding domain name to /etc/hosts**
```
sudo vi /etc/hosts
<ingress-ip-addess>    mongoingress.com
```

