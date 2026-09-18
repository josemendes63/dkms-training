# Troubleshooting

## Ver Nodes

```bash
kubectl get nodes
```

## Ver Pods

```bash
kubectl get pods -A
```

## Ver Eventos

```bash
kubectl get events
```

## Ver Logs

```bash
kubectl logs POD_NAME
```

## Ver utilização de recursos

```bash
kubectl top nodes

kubectl top pods
```

## Ver objetos com problema

```bash
kubectl get all -A
```

## Entrar num Pod

```bash
kubectl exec -it POD_NAME -- bash
```