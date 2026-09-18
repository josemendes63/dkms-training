# Lab 08 - ConfigMap

## Criar

```bash
kubectl create configmap app-config \
--from-literal=MODE=DEV
```

## Verificar

```bash
kubectl get configmaps
```