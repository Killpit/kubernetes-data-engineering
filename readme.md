# Lessons learned from the project

## Kubernetes Troubleshooting

- **kubectl get namespaces**: gets all the namespaces in Kubernetes
- **kubectl create namespace <name>**: create kubernetes resources
- **kubectl apply -f <file-name> -n <namespace>**: create or update resources in a 
specific namespace in a Kubernetes cluster
- --namespace can be used when necessary
- **kubectl get serviceaccount <name> -n <namespace>**: retrieve information about a 
specific ServiceAccount in a specified namespace within a Kubernetes cluster 
- **kubectl describe serviceaccount <name> -n <namespace>**: provides detailed information about a 
specific ServiceAccount in a given namespace in a Kubernetes cluster.
- solved resource not found problem for now
- **kubectl get secret**: list secrets stored in a kubernetes cluster.
- **kubectl port-forward**: Forward one or more local ports to a pod
- **kubectl get pods**: gets the pods as resources (works with kubectl command)
- 