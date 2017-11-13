kubectl create -f nginx-dep.yaml
kubectl create -f nginx-svc.yaml

# Delete

kubectl delete -f nginx-dep.yaml
kubectl delete -f nginx-svc.yaml