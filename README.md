# Deployment

kubectl create deploy prometheus-springboot --image brainupgrade/prometheus-springboot:simple
kubectl expose deploy prometheus-springboot --port 80 --target-port 8080