README
Racer Game - Dockerizado
Descripción

Este proyecto consiste en el despliegue del juego Racer Game utilizando Docker y Nginx.

La aplicación se ejecuta dentro de un contenedor Docker basado en la imagen oficial de Nginx, copiando los archivos del directorio src hacia el directorio público del servidor web.

El servicio se despliega en el puerto 80 y permite acceder al juego desde cualquier navegador web.

Tecnologías Utilizadas:

-Docker
-Nginx
-HTML5
-CSS3
-JavaScript
-Dockerfile
-FROM nginx

Estructura del Proyecto
´´´text
.
├── Dockerfile
├── src/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── assets/
