# Kratix PostgreSQL (Simples)

Este template gera um manifesto do recurso:

- apiVersion: marketplace.kratix.io/v1alpha2
- kind: postgresql

## Aplicar manualmente (por enquanto)

1) Aplicar no cluster platform:
```bash
kubectl --context kind-platform apply -f ./pg-<nome>.yaml
