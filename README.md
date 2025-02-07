# bootdev_kubernetes
Boot.dev Kubernetes course

minikube start

minikube dashboard --port=63840

kubectl port-forward synergychat-web-567fb566bf-bszgv 8080:8080

kubectl apply -f app-ingress.yaml

kubectl proxy

minikube tunnel -c