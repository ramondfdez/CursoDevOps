# Ejercicio Docker - React

## Objetivo

Contenerizar una aplicacion React con dos enfoques: Dockerfile estandar y multi-stage.

## Archivos clave

- `Dockerfile`
- `multistage.Dockerfile`
- `package.json`

## Opcion 1: Dockerfile estandar

```bash
cd 3-Docker/react
docker build -t docker-react .
docker run --rm -p 3000:3000 docker-react
```

## Opcion 2: Multi-stage con Nginx

```bash
cd 3-Docker/react
docker build -f multistage.Dockerfile -t docker-react-multistage .
docker run --rm -p 8080:80 docker-react-multistage
```

## Verificacion

- Estandar: `http://localhost:3000`
- Multi-stage: `http://localhost:8080`
