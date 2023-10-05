# 23-2-parcial-b

###Para poder ejecutar de manera el proyecto usando una base de datos mysql de manera correcta necesitamos utilizar el siguiente comando "docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=clave -e MYSQL_DATABASE=parcial mysql" esto lo que hace es levantar un contenedor con la imagen de MYSQL y montar una base de datos de manera local sin ninguna red en el puerto 3306 de nuestra maquina y 3306 de la MINI maquina virtual. Ademas de esto, toca ejecutarla usando la conexion parcial, direccion localhost:3306 y la contraseña clave
