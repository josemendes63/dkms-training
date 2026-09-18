# Lab 01 - Criar Namespace

## Objetivo

Criar um namespace para ambientes de desenvolvimento.

## Criar Namespace

```bash
kubectl create namespace dev
```

## Verificar

```bash
kubectl get ns
```

## Resultado Esperado

```text
dev
```

## Limpeza

```bash
kubectl delete namespace dev
```