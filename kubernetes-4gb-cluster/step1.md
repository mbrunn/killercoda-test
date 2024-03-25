
List all namespaces currently registered on the cluster: `kubectl get namespaces`{{exec}}

List all Pods that are currently running on the cluster: `kubectl get pod -A`{{exec}}

Create Dynatrace-Namespace: `kubectl create namespace dynatrace` {{exec}}

Install Dynatrace-Operator: `kubectl apply -f https://github.com/Dynatrace/dynatrace-operator/releases/download/v0.15.0/kubernetes.yaml`{{exec}}

Watch for all pods to start (1/1): `kubectl get pods –n dynatrace`{{exec}} 