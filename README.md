
# Curso de introducción a PostgreSQL y PostGIS

## https://github.com/psigcat/curso_postgis_1_intro

## Tema 1 Introducción

#### Resumen del curso
Introducción a PostgreSQL y PostGIS, configuración y gestión básica

## Primero hay que descarregar los ficheros comprimidos en zip de este enlace, y descomprimirlos
Link material del curs([[enlace]](https://drive.google.com/file/d/1TvBvySj9hnc3CTP7wa3d959tyK0Fzb4o/view?usp=sharing)]) (89 MB)

## Hay que tener instalado PostgreSQL, PostGIS, pgAdmin 4 y ...... QGIS Desktop
Por si falla la conexión a internet, les dejo un zip con las 3 aplicaciones a instalar
https://drive.google.com/file/d/1GDWted0-H1da552CfLEcU4kZwff8X8QS/view?usp=sharing

### Windows
Toturial como instalar postgreSQL y PostGIS en Windows
https://youtu.be/_EgtELrjLO4

### Linux
Protoclo de instalación y configuración en Linux
https://github.com/carlospsig/protocol_install_qgis_ubuntu/blob/master/install_postgis.sh

### PostgreSQL Service connection file
https://docs.qgis.org/3.10/en/docs/user_manual/managing_data_source/opening_data.html#pg-service-file

## Pasos a hacer
##### 1 Instalar PostgreSQL 18

##### 2 Instalar PostGIS 3

##### 3 Instalar pgAdmin4 9

##### 4 Abrir pgAdmin con la configuración inicial
- host=localhost
- port=5432
- dbase=postgres
- user=postgres
- password=??

##### 5 Crear una nueva base de datos = **gis_curso**
A futuro, les recomiendo utilizar otra base de dadtos como plantilla (template) la base de datos "postgres" (pe)

##### 6 Activar la extensión de PostGIS
Ejecutar la sintaxi siguiente en una "Query Tool"
- create extension postgis;


##### podemos compartir el código en esta web:
https://codeshare.io/2W9xDE

##### 7 crear un nuevo usuario gisadmin
Ejecutar la sintaxi siguiente en una "Query Tool", antes de ejecutarlo reemplazar el texto 'your_password' por un password vuestro personal y guardarlo en agún sitio seguro como keepass
- CREATE ROLE **gisadmin** login PASSWORD **'your_password'** SUPERUSER CREATEDB CREATEROLE NOINHERIT;

##### 8 Abrir QGIS con el usuario gisadmin
Crear un nueva conexión con el usuario gisadmin y guardar la conexión

##### 9 Utilizar el DB Manager para cargar capas
- Abrimos el complemento DB Manager
- Primero creamos nuevos esquemas 
  - limit_admin 
  - medi_ambient

Luego importar las capas de municipis, comarques y PEIN, cómo mínimo.
Cargar las capas que hay en la carpeta Datos


#### video 1- Instalar, configurar PostGIS e importar capas
https://youtu.be/_EgtELrjLO4

#### Otros vídeos tutoriales en este canal
http://www.youtube.com/c/CarlosLópezQuintanilla

### dudas y comentarios
carlos.lopez@psig.es

Colabora con QGIS, hazte socio!
www.qgis.es

## Fí
