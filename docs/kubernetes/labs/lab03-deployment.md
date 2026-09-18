# Lab 03 - Criar Deployment

## Criar Deployment

```bash
kubectl create deployment nginx \
--image=nginx
```

## Verificar

```bash
kubectl get deployments
```

```mermaid
graph TD

Deployment
--> ReplicaSet
--> Pod
```