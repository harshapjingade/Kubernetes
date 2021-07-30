**kubectl apply commands in order:**
```
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo-deploy.yaml
kubectl apply -f mongo-configmap.yaml
kubectl apply -f mongoexpress-deploy.yaml
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
```

**kubectl debugging commands**
```
kubectl describe pod <podname>
kubectl service <servicename>
kubectl logs <deploymentname>
```

**give a URL to external service in minikube**
```
minikube service mongo-express-service
```
