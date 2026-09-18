# Helm

Helm é o gestor de pacotes do Kubernetes.

## Fluxo

```mermaid
graph TD

Chart

--> Helm

Helm

--> Deployment

Deployment

--> Pods
```

## Ver repositórios

```bash
helm repo list
```

## Adicionar repositório

```bash
helm repo add bitnami https://charts.bitnami.com/bitnami
```

## Instalar NGINX

```bash
helm install nginx bitnami/nginx
```