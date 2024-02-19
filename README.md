--- first time in aws ---

chose ubuntu in aws

1. install docker https://medium.com/@srijaanaparthy/step-by-step-guide-to-install-docker-on-ubuntu-in-aws-a39746e5a63
2. install minikube https://www.linuxtechi.com/how-to-install-minikube-on-ubuntu/
3. minikube start
4. git clone
5. cd 2048-app/2048/2048/k8s
6. kubectl apply -f
7. kubectl get all
8. create port 30001
9. kubectl port-forward svc/my-mini-app-service 30001:80 --address 0.0.0.0 &
10. run browser

    
--- second time --- 
run on aws

1. minikube start
2.cd 2048-app/2048/2048/k8s
3.kubectl apply -f .
4. kubectl get all
5. kubectl port-forward svc/my-mini-app-service 30001:80 --address 0.0.0.0 &
