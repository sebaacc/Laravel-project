# Laravel-project
Primer proyecto con Laravel php. Me guié con documentación y [este video](https://youtu.be/rn2LCOeNPds). 

## Instrucciones
1. Primero se debe instalar [XAMPP](https://www.apachefriends.org/es/index.html). Para poder correr la app de Laravel.  
Además también instalar [Composer](https://getcomposer.org/). 
2. Se crea una carpeta del proyecto, en mi caso es la de este repositorio "Laravel-project".
3. Abrir terminal en dentro del directorio y poner el comando (cambiando "proyecto" por el nombre que se quiera):
```bash 
 composer create-project laravel/laravel proyecto
```
Si falla quizá sea por tener el antiVirus activado, desactivarlo e intentar de nuevo.
4. Entramos desde la terminal en la carpeta "proyecto" (cd proyecto). 
5. Para corroborar que funciona todo inciamos el servidor local con:
```bash 
 php artisan serve
```
6. Las carpetas que más vamos a recurrir son: app, database, public, y resources.

## Base de datos 
Para iniciar la base de datos nos dirigimos al programa XAMPP control panel, y le damos en **start** a Apache y luego MySQL.  
Corroboramos que funciona accediendo a http://localhost/phpmyadmin/ .
Una vez dentro creamos una base de datos, en mi caso se llama laravel11.    
Luego en archivo .env cambiamos (línea 23) DB conection por mysql, y descomentamos hasta la línea 28, cambiando el nombre de la BD por el que le pusimos.
