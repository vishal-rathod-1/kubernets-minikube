# ⚙️ Kubernetes Local Setup Cheat Sheet (Minikube + kubectl + Pod)

## 🐳 Docker Basics

docker --version  
docker ps  
docker images  
docker pull nginx  
docker run -d -p 8080:80 nginx  
docker stop <container_id>  
docker rm <container_id>  
docker rmi <image_id>

## 🚀 Minikube Commands

minikube start  
minikube status  
minikube dashboard  
minikube stop  
minikube delete  
minikube kubectl -- get pods  
minikube service <service-name>

## 📘 kubectl Essentials

kubectl version --client  
kubectl get nodes  
kubectl get pods  
kubectl get services  
kubectl describe pod <pod-name>  
kubectl logs <pod-name>  
kubectl apply -f <file>.yaml  
kubectl delete -f <file>.yaml  
kubectl delete pod <pod-name>



## ▶️ Deploy and Manage the Pod

kubectl apply -f pod.yaml  
kubectl get pods  
kubectl describe pod nginx-pod  
kubectl logs nginx-pod  
kubectl delete -f pod.yaml
