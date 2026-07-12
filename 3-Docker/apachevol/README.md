# Ejercicio Docker - Apache con contenido estatico

## Objetivo

Servir un `index.html` usando Apache dentro de un contenedor.

## Archivos clave

- `Dockerfile`
- `html/index.html`

## Comandos

```bash
cd 3-Docker/apachevol
docker build -t docker-apachevol .
docker run --rm -p 8080:80 docker-apachevol
```

## Verificacion

Abrir `http://localhost:8080` y comprobar que se muestra la pagina.
