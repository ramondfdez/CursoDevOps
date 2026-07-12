# Ejercicio Docker - Nginx Web

## Objetivo

Servir una web estatica con Nginx y configuracion custom.

## Archivos clave

- `Dockerfile`
- `default.conf`
- `inicio.html`

## Comandos

```bash
cd 3-Docker/web
docker build -t docker-nginx-web .
docker run --rm -p 8080:8080 docker-nginx-web
```

## Verificacion

Abrir `http://localhost:8080` y validar que Nginx sirve `inicio.html`.
