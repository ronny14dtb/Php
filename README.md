# Php

Descargar el repositorio 
descargar el Xampp
instalar el Xampp
pegar el repositorio en la ruta C:\xampp\htdocs
Iniciar el xamp control de C:\xampp
iniciar el servidor de apache y mysql (darle en boton de configurar de este para acceder a la base de datos local)

*Archivo mysql en C:\xampp\htdocs\php-crud  "Konecta"*
Pasos de búsqueda por base de datos
Más stock= SELECT MAX(stock),id,nombre FROM productos;
más vendidos= SELECT * FROM productos INNER JOIN (SELECT SUM(cantidad) as total, id_producto FROM ventas_realizadas  GROUP BY id_producto) tabla1 ON tabla1.id_producto = productos.id
