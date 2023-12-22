# redis
Repo for redis setup on k8s cluster
Current setup is running redis in `redis` namspace.

## Installation of redis in cluster:
### Helm:
`helm install bitnami/redis` - this will deploy all resources in default namespace
### Kustomise:
`helm template bitnami/redis --output-dir .`
`kubectl apply -k redis/`
