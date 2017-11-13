kubectl create -f nginx-dep.yaml
kubectl create -f nginx-svc.yaml

kubectl create -f redis-dep.yaml
kubectl create -f redis-svc.yaml

# Delete

kubectl delete -f nginx-dep.yaml
kubectl delete -f nginx-svc.yaml

kubectl delete -f redis-dep.yaml
kubectl delete -f redis-svc.yaml

# Service
minikube service redis --url