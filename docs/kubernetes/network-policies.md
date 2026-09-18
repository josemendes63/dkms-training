# Network Policies

As Network Policies controlam a comunicação entre Pods.

## Sem Policy

```mermaid
graph LR

PodA --> PodB

PodA --> PodC

PodB --> PodC
```

## Com Policy

```mermaid
graph LR

PodA --> PodB

PodA -.Bloqueado.-> PodC

PodB -.Bloqueado.-> PodC
```

## Ver policies

```bash
kubectl get networkpolicy
```

## Exemplo

```yaml
apiVersion: networking.k8s.io/v1

kind: NetworkPolicy

metadata:
  name: allow-nginx
```
