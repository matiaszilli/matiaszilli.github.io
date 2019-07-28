---
layout: project
type: project
image: images/sqltomongo_card.jpg !!!!!
title: Angular apps
permalink: projects/angular-apps
# All dates must be YYYY-MM-DD format!
date: 2018-09-01
labels:
  - Angular
  - MongoDB
summary: Algunos ejemplos de apps desarrolladas mientras aprendía Angular.
---

<img class="ui image" src="../images/sqltomongo_header.jpg">

Spotiapp es una app desarrollada en Angular que utiliza la api de Spotify para obtener informacion de albums, artistas y tracks. Esta permite consultar los nuevos lanzamientos de albums, buscar artistas, consultar informacion de un artista dado incluyendo sus top-tracks y un preview de estos.

Clinicaapp es una app que utiliza un backend desarrollado en Node.js con base de datos MongoDB, esta permite administrar la gestion de una clinica incluyendo hospitales, medicos, usuarios cada uno de estos con sus roles asociados, soporta login normal y mediante Google.

Peliculas app es un simple desarrollo que utiliza la api "themoviedb.org" para obtener informacion de peliculas populares, peliculas para ninios y nuevos lanzamientos. Ademas permite buscar peliculas por nombre y mostrar toda la informacion asociada a una de ellas.

Node.js app desarrollada para migrar un proyecto que consta de una base de datos MSSQL Server con 1000 millones de registros y tamano 1Tb a MongoDB. La app inserta toda las tablas presentes en MSSQL a una unica collection en MongoDB, es posible parsear la data antes de insertarla en MongoDB para de esta manera tener la posibilidad de agregar, borrar o restructurar los datos antes de hacer la insercion. 

Para lograr buena performance la app utiliza el "child_process" module de Node.js para paralelizar la ejecucion de la migracion y asi ejecutar un worker por core. Otra de las estrategias consiste en leer una tabla completa de MSSQL y luego insertar todo el recordSet a MongoDB utilizando "insertMany", con esto se reduce drasticamente el numero de comandos enviados a ambas bases de datos y se logra un incremento relevante en la performance.  

Source: <a href="https://github.com/matiaszilli/someAngular"><i class="large github icon "></i>matiaszilli/someAngular</a>

