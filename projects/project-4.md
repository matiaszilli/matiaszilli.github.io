---
layout: project
type: project
image: images/sqltomongo_card.jpg
title: Sql to MongoDB
permalink: projects/sqltomongo
# All dates must be YYYY-MM-DD format!
date: 2019-04-15
labels:
  - Node.js
  - MongoDB
  - MSSQL
summary: Node.js app para migrar datos de una base de datos MSSQL Server a MongoDB.
---

<img class="ui image" src="../images/sqltomongo_header.jpg">

Node.js app desarrollada para migrar un proyecto que consta de una base de datos MSSQL Server con 1000 millones de registros y tamano 1Tb a MongoDB. La app inserta toda las tablas presentes en MSSQL a una unica collection en MongoDB, es posible parsear la data antes de insertarla en MongoDB para de esta manera tener la posibilidad de agregar, borrar o restructurar los datos antes de hacer la insercion. 

Para lograr buena performance la app utiliza el "child_process" module de Node.js para paralelizar la ejecucion de la migracion y asi ejecutar un worker por core. Otra de las estrategias consiste en leer una tabla completa de MSSQL y luego insertar todo el recordSet a MongoDB utilizando "insertMany", con esto se reduce drasticamente el numero de comandos enviados a ambas bases de datos y se logra un incremento relevante en la performance.  

Source: <a href="https://github.com/matiaszilli/SQLtoMongo"><i class="large github icon "></i>matiaszilli/SQLtoMongo</a>

