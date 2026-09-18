# Lab 06 - Criar Ingress

## Fluxo

```mermaid
graph TD

Internet

--> Ingress

Ingress

--> Service

Service

--> Pods
```

## Verificar

```bash
kubectl get ingress
```