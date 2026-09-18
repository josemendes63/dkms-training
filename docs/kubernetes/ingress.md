# Ingress

Ingress permite publicar aplicações HTTP e HTTPS.

## Arquitetura

```mermaid
graph TD

Internet

--> Ingress

Ingress --> App1

Ingress --> App2

Ingress --> App3
```

## Ver Ingress

```bash
kubectl get ingress
```

## Exemplo

```yaml
apiVersion: networking.k8s.io/v1

kind: Ingress

metadata:
  name: web-ingress
```
