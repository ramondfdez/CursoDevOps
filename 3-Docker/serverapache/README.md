# Ejercicio Docker - Apache Server

## Objetivo

Levantar un servidor Apache con una pagina estatica.

## Archivos clave

- `Dockerfile`
- `index.html`
- `old.Dockerfile` (referencia legacy)

## Comandos

```bash
cd 3-Docker/serverapache
docker build -t docker-serverapache .
docker run --rm -p 8080:80 docker-serverapache
```

## Verificacion

Abrir `http://localhost:8080` y revisar contenido HTML servido por Apache.
