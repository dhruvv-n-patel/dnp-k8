Basic setup for helm - kubernetes

helm create mychart

helm install --dry-run --debug . --generate-name

helm install example .

helm repo update

helm list

helm add all

helm uninstall example

For minikube User

minkube start

minikube ip

minikube service <your-servicename> --url

minikube addons enable ingress

minikube tunnel

kubectl get ingress
