# Port forward to db on particular pod

```
kubectl port-forward db-abcd12345-abcde 5433:5432
```

# Generate temporary token for logging into the k8 dashboard

```
kubectl -n kube-system describe secret $(kubectl -n kube-system get secret | grep admin-user | awk '{print $1}')
```
