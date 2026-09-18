# Persistent Volumes

Permitem armazenamento persistente.

## Arquitetura

```mermaid
graph TD

Pod

--> PVC

PVC

--> PV

PV

--> Storage
```

## Ver PV

```bash
kubectl get pv
```

## Ver PVC

```bash
kubectl get pvc
```