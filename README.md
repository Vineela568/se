minikube start --driver=docker
minikube start --driver=docker
minikube kubectl -- get pods -A
minikube dashboard
kubectl version --client
3.	minikube update-check
4.	minikube update
//start 
minikube start
kubectl create deployment mynginx --image=nginx

if already created then 

kubectl set image deployment/myngnix nginx=nginx:latest
 kubectl get deployments
 	kubectl get pods
  	kubectl describe pods
    kubectl expose deployment mynginx --type=NodePort --port=80 --target-port=80
    kubectl scale deployment mynginx --replicas=4
kubectl get service myngnix
kubectl port-forward svc/mynginx 8081:80

    docker pull jasonrivers/nagios:latest
    docker run --name nagiosdemo -p 8888:80 jasonrivers/nagios:latest
