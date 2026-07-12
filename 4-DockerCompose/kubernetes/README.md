# Kubernetes - Manifiestos del Full App

## Objetivo

Desplegar en Kubernetes los componentes equivalentes al stack de Compose.

## Archivos

- `back-deployment.yaml`
- `back-service.yaml`
- `db-deployment.yaml`
- `db-service.yaml`
- `ui-deployment.yaml`
- `ui-service.yaml`
- `ingress.yaml`

## Comandos

```bash
cd 4-DockerCompose/kubernetes
kubectl apply -f .
```

## Verificacion

```bash
kubectl get pods
kubectl get svc
kubectl get ingress
```

## Requisito

Asegurar que las imagenes referenciadas en los deployments existen y son accesibles desde el cluster.
