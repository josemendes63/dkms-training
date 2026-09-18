# Certificates

Gestão de certificados TLS.

## Componentes

```mermaid
graph TD

CA

--> API_Server

CA

--> kubelet

CA

--> User
```