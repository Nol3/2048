## Ejecutar con Docker

1. Construir la imagen:
```bash
docker build -t 2048-game .

docker run -d -p 8080:8080 --name 2048 2048-game


Estos comandos:
1. Construyen una imagen Docker usando el Dockerfile del proyecto
2. Ejecutan un contenedor basado en esa imagen, exponiendo el puerto 8080
3. La aplicación estará disponible en localhost:8080

Para detener y eliminar el contenedor puedes usar:
```bash
docker stop 2048
docker rm 2048