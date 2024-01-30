# Outline

## develop

```bash
kubectl create secret generic outline-secret -n outline --dry-run=client --from-env-file=.env --output=yaml > kubefiles/secret.yaml
kubectl create secret generic postgres-secret -n outline --dry-run=client --from-env-file=postgres.env --output=yaml > kubefiles/postgres-secret.yaml
```

```bash
kubectl 
```