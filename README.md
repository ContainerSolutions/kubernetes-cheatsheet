# Kubernetes Cheatsheet

## Secrets

List all secrets

```
$ kubectl get secret
```

Export a specific secret

```
$ kubectl get secret secret-name -o yaml --export
```
