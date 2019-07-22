# Kubernetes Cheatsheet

## Explain

```
$ kubectl explain role
KIND:     Role
VERSION:  rbac.authorization.k8s.io/v1

DESCRIPTION:
     Role is a namespaced, logical grouping of PolicyRules that can be
     referenced as a unit by a RoleBinding.
...
```

## Namespaces

Switch namespace with [kns](https://github.com/blendle/kns)

```
$ kns
*arrow up/down + enter*
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
