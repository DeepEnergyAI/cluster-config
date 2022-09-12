# cluster-config

## Storage
### Redis

```bash
kubectl create namespace redis
kubectl apply -f redis-config.yaml
kubectl apply -f redis-acl.yaml
kubectl apply -f redis.yaml
```
