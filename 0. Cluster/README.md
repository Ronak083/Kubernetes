Make sure Kind & Kubectl are installed in it + Docker Desktop is required to use Kind (Kubernetes inside Docker)
 kind create cluster --config clusters.yml --name localcluster

Check:
 kubectl get nodes
 kubectl get pods -A
 
