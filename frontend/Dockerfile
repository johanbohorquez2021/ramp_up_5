# Para el frontend
FROM nginx:alpine

# Actualiza los repositorios e instala net-tools
RUN apt-get update && apt-get install -y net-tools curl

# Copiar el contenido del frontend
COPY . /usr/share/nginx/html

# Establecer las variables de entorno FRONTEND_DOCKER_PORT y FRONTEND_IP
ENV FRONTEND_DOCKER_PORT=80
ENV FRONTEND_IP=52.52.10.204

# Exponer el puerto del frontend definido por la variable de entorno FRONTEND_DOCKER_PORT
EXPOSE $FRONTEND_DOCKER_PORT



# Para el frontend
# FROM nginx:alpine

# COPY . /usr/share/nginx/html
