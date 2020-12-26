# ACTIVIDAD 1:
Como actividad complementaria para el primer tema, este ejercicio os servirá para ampliar
vuestro conocimiento y experiencia con XAMP, PHP y MYSQL, como una extensión de lo que
habéis realizado ya como parte del contenido; es decir, sobre la instalación de XAMPP.

1. Instalar XAMPP en vuestro ordenador y configurar el puerto de escucha del servidor web a
otro que no sea 80; por ejemplo, 8080.
2. Comprobar que podéis acceder al servidor con http://localhost:8080 y https://localhost:443
3. Crear dentro de la carpeta xampp\htdocs el fichero de texto "prueba.php" con el siguiente
código:
<php?
echo 'Hola, mundo';
?>
4. Crear la carpeta "recursos" dentro de xampp\htdocs y crear ahí el fichero "recursos.php",
con el siguiente código:
<php?
echo 'Estoy en la carpeta de recursos';
?>
5. Comprobar que se pueden acceder a dichas páginas,
con http://localhost:80/prueba.php y http://localhost:80/recursos/recursos.php
6. Habilitar la utilidad phpinfo() del sitio web para que se pueda ver que lo tenéis instalado y
operativo, creando el fichero "phpinfo.php" con el siguiente texto y acceder con la dirección
http://localhost:8080/phpinfo.php
<?php
phpinfo();
?>
Una vez terminado, enviad un documento con los pantallazos del navegador que muestre cada
página (puntos 3, 4 y 6).
