# Lab 07 - Persistent Volume

## Arquitetura

```mermaid
graph TD

Pod

--> PVC

PVC

--> PV
```

## Verificar

```bash
kubectl get pv

kubectl get pvc
```