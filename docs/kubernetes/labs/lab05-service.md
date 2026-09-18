# Lab 05 - Criar Service

## Expor aplicação

```bash
kubectl expose deployment nginx \
--port=80 \
--type=ClusterIP
```

## Verificar

```bash
kubectl get svc
```

## Arquitetura

```mermaid
graph LR

Service

--> Pod1
--> Pod2
--> Pod3
```
