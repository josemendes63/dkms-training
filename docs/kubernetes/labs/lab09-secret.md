# Lab 09 - Secret

## Criar Secret

```bash
kubectl create secret generic db-secret \
--from-literal=password=Pass123
```

## Verificar

```bash
kubectl get secrets
```