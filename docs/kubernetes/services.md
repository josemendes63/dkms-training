# Services

Os Services permitem expor Pods.

## Fluxo

```mermaid
graph LR

U[Utilizador]

U --> S[Service]

S --> P1[Pod 1]

S --> P2[Pod 2]

S --> P3[Pod 3]
```

## Listar

```bash
kubectl get svc
```

## Exemplo Service

```yaml
apiVersion: v1

kind: Service

metadata:
  name: nginx-service

spec:
  selector:
    app: nginx

  ports:
    - port: 80
      targetPort: 80
```