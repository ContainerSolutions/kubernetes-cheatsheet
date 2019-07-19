# Kubernetes Cheatsheet

## Namespaces

Switch namespace with [kns](https://github.com/blendle/kns)

```
$ kns
*arrow up/down*
```

## Secrets

List all secrets

```
$ kubectl get secret
```

Export a specific secret

```
$ kubectl get secret secret-name -o yaml --export
```
