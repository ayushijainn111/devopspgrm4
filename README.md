# devopspgrm4

minikube start --driver=docker

minikube status

docker build -t ayushijainn111/app1-k8s:latest .

docker push ayushijainn111/app1-k8s:latest

kubectl apply -f deployment.yaml

kubectl apply -f service.yaml

kubectl get pods

kubectl get svc

kubectl scale deployment/hw-deployment --replicas=3

kubectl get deployment

kubectl get pods

kubectl port-forward svc/hello-world 5000:5000
