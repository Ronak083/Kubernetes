Make sure Kind & Kubectl are installed in it + Docker Desktop is required to use Kind (Kubernetes inside Docker) 
```yaml
kind create cluster --config clusters.yml --name localcluster
```
How to verify:
```yaml
 kubectl get nodes
 kubectl get pods -A
```
Else use AWS
```yaml
 eksctl create cluster \
                 --name learningcluster \
                 --nodes=2 \
                 --node-type=t3.small \
                 --region=us-east-1 \
                 --version=1.33
```
