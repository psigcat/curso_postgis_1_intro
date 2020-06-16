
# Curso de introducción a PostgreSQL y PostGIS

## https://github.com/psigcat/curso_postgis_1_intro

## Tema 1 Introduccións

#### Resumen del curso
Introducción a PostgreSQL y PostGIS, configuración y gestión básica
Usod el complemento DB Manager de QGIS para administrar los datos

#### Presentación y normas de uso
Benvinguda i instruccions d'ús
../../ZProjectA/Barcelona_Activa/Documents/Formacio_Virtual_Teams/Regles_d'ús (003).pptx

Recordeu mantenir desconnectades la vostra càmera i micròfon per evitar interferències.

Les preguntes es fan principalment pel xat. Si no disposeu d’aquesta icona, pengeu, elimineu cookies (o accedir en una pestanya en incògnit) i torneu a accedir. Si segueix sense aparèixer, pots fer les preguntes a través del micròfon al final de la sessió.

## Hay que tener instalado PostgreSQL, PostGIS, pgAdmin 4 y QGIS Desktop

### Windows
Toturial como instalar postgreSQL y PostGIS en Windows
https://www.youtube.com/watch?v=bq9dOrwZ-KA

### Linux
Protoclo de instalación y configuración en Linux
https://github.com/carlospsig/protocol_install_qgis_ubuntu/blob/master/install_postgis.sh


### PostgreSQL Service connection file
https://docs.qgis.org/3.10/en/docs/user_manual/managing_data_source/opening_data.html#pg-service-file

## Primero hay que descarregar los ficheros comprimidos en zip de este enlace, y descomprimirlos
http://psig.es/Curso_PostGIS_1_Intro.zip (?? MB)

## Pasos a hacer
1 Instalar PostgreSQL 10.13

2 Instalar PostGIS 2.5

3 Instalar pgAdmin4 4.22


4 Abrir pgAdmin con la configuración inicial

host=localhost

port=5432

dbase=postres

user=postgres

password=??

Crear una nueva base de datos = **gis_curso**

crear un nuevo usuario gisadmin

CREATE ROLE **gisadmin** login PASSWORD **'your_password'** SUPERUSER CREATEDB CREATEROLE NOINHERIT;


5 Abrir QGIS con el usuario gisadmin

guardar la conexión

6 Utilizar el DB Manager para cargar capas

Crea esquema limit_admin y medi_ambient

Cargar las capas que hay en la carpeta Datos



#### video 1- Conexión y importar capas




#### Otros vídeos tutoriales en este canal
http://www.youtube.com/c/CarlosLópezQuintanilla

### dudas y comentarios
carlos.lopez@psig.es

Colabora con QGIS, hazte socio!
www.qgis.es
