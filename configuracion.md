Configuracion de mysql en docker
===============================
restart: always es para que siempre se reinicie el contenedor
```

# ver los contenedores
docker ps

# ver los logs
docker logs -f mysql

# construir el contenedor
docker-compose up -d

una vez que se construye el contenedor se nos crea la carpeta schemas y dentro de ella el archivo schema.sql

docker ps -a
ps -a es para ver todos los contenedores

# detener el contenedor
docker stop mysql 