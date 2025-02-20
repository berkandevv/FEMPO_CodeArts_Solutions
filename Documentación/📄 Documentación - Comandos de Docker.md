# Comandos de Docker

## Comandos de administración general

- `docker -v` => Ver la versión del Docker.
- `docker image prune` => Eliminar imágenes no utilizadas.
- `docker info` => Ver información del sistema Docker.

## Comandos para gestionar imágenes

- `docker images` => Muestra las imágenes.
- `docker build -t nombre_imagen .` => Construye la imagen usando Docker (Hay que escribir antes el Dockerfile).
- `docker pull <nombre_imagen>` => Descarga una imagen desde Docker Hub.
- `docker rmi <ID/nombre_imagen>` => Elimina la imagen.

## Comandos para gestionar contenedores

- `docker ps` => Muestra los contenedores en ejecución.
- `docker ps -a` => Muestra todos los contenedores en ejecución y detenidos.
- `docker start <ID/nombre_contenedor>` => Inicia un contenedor detenido.
- `docker stop <ID/nombre_contenedor>` => Detiene el contenedor.
- `docker run <opciones> <nombre_imagen>` => Crea y ejecuta un contenedor.
- `docker run -d <nombre_imagen>` => Crea y ejecuta un contenedor en segundo plano.
- `docker rm <ID/nombre_contenedor>` => Elimina un contenedor.

## Comandos para interactuar con los contenedores

- `docker inspect <ID/nombre_contenedor>` => Obtiene información del contenedor.
- `docker exec -it <ID/nombre_contenedor> bash` => Abre una terminal interactiva dentro de un contenedor en ejecución, lo que te permite ejecutar comandos dentro del contenedor.
