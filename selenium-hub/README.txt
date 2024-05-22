
cd C:\Data\github\kubernetes-examples

kubectl apply -f .\selenium-hub


cd C:\Data\github\kubernetes-examples\selenium-hub

kubectl apply -f selenium-hub-deployment.yaml
kubectl apply -f selenium-hub-service.yaml
kubectl apply -f selenium-node-chrome-deployment.yaml
