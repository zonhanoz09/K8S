# K8S

kubectl rollout restart deployment platform-depl

kubectl apply -f platforms-depl.yaml
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.0.0/deploy/static/provider/cloud/deploy.yaml

kubectl create secret generic mssql --from-literal=SA_PASSWORD="pa55w0rd!"
kubectl apply -f mssql-plat-depl.yaml

kubectl get pvc
kubectl get storageclass
kubectl get ingress 
kubectl get pods --namespace=ingress-nginx
kubectl get services --namespace=ingress-nginx   

kubectl delete -f platforms-np-srv.yaml
