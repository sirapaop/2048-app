--- first time in aws ---

chose ubuntu in aws

install docker https://medium.com/@srijaanaparthy/step-by-step-guide-to-install-docker-on-ubuntu-in-aws-a39746e5a63
install minikube https://www.linuxtechi.com/how-to-install-minikube-on-ubuntu/
minikube start
git clone
cd 2048-app/2048/2048/k8s
kubectl apply -f
kubectl get all
create port 30001
kubectl port-forward svc/my-mini-app-service 30001:80 --address 0.0.0.0 &
run browser
--- second time --- run on aws

minikube start

cd 2048-app/2048/2048/k8s

kubectl apply -f .

kubectl get all

kubectl port-forward svc/my-mini-app-service 30001:80 --address 0.0.0.0 &
