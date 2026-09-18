# Pods

Os Pods são a unidade mais pequena executável no Kubernetes.

Um Pod pode conter um ou mais containers.

## Arquitetura

```mermaid
graph TD

N[Worker Node]

N --> P[Pod]

P --> C1[Container App]

P --> C2[Container Sidecar]
```

## Criar um Pod

```bash
kubectl run nginx --image=nginx
```

## Listar Pods

```bash
kubectl get pods
```

## Ver detalhes

```bash
kubectl describe pod nginx
```

## Ver logs

```bash
kubectl logs nginx
```

## Entrar no Pod

```bash
kubectl exec -it nginx -- bash
```

## Ciclo de Vida

```mermaid
stateDiagram-v2

Pending --> Running
Running --> Succeeded
Running --> Failed
Running --> Unknown
```