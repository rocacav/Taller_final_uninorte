## Taller_final_uninorte
Descargar una imagen de Nginx y una  imagen de alpine/git.
Usar el puerto 8080 para el Nginx.

Construir una imagen a partir de las descargadas con el comando:
docker build -t tallerfinal .

Crear un docker container con la imagen de Nginx y de alpine/git que fue descargada en el paso anterior
Publicar el contenedor con el comando:
docker container run --publish 8080:80 -d --name tallerfinal_container tallerfinal

Los archivos Dockerfile y docker-compose cuentan con la información necesaria, para la ejecución exitosa del proyecto.


Puede obtener una vista previa del proyecto aqui: https://grupo2iis.000webhostapp.com/
