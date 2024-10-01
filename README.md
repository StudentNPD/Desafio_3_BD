# Proyecto Base de Datos Top 100 Películas

## Descripción

Este proyecto consiste en crear una plataforma web dedicada al mundo del cine, permitiendo a los usuarios explorar detalles de las 100 películas más populares. La característica clave de este sitio web es su variedad de filtros, lo que permite a los usuarios realizar búsquedas más efectivas.

## Requisitos del Proyecto

1. Crear una base de datos llamada "películas".
2. Cargar datos desde archivos CSV proporcionados en dos tablas: "películas" y "reparto".
3. Realizar varias consultas SQL para extraer y analizar datos de estas tablas.

## Configuración

1. Crear una base de datos PostgreSQL llamada "películas".
2. Utilizar los archivos CSV proporcionados para poblar las tablas "películas" y "reparto".

## Consultas Requeridas

El proyecto requiere implementar las siguientes consultas SQL:

1. Obtener el ID de la película "Titanic".
2. Listar todos los actores que aparecen en "Titanic".
3. Contar el número de películas del top 100 en las que aparece Harrison Ford.
4. Listar las películas estrenadas entre 1990 y 1999, ordenadas por título (ascendente).
5. Mostrar los títulos de las películas con su longitud, usando "longitud_titulo" como nombre de columna para la longitud.
6. Encontrar la longitud máxima entre todos los títulos de películas.

## Tecnologías Utilizadas

- PostgreSQL
- SQL

## Archivos Incluidos

- `peliculas.csv`: Contiene datos para la tabla "películas".
- `reparto.csv`: Contiene datos para la tabla "reparto".

## Tiempo Asignado

El tiempo estimado para completar este proyecto es de 2 horas.

## Criterios de Evaluación

- Crear la base de datos (1 punto)
- Cargar datos en las tablas (1 punto)
- Obtener el ID de Titanic (1 punto)
- Listar el reparto de Titanic (1 punto)
- Contar las apariciones de Harrison Ford (2 puntos)
- Listar películas de los años 90 (1 punto)
- Mostrar longitudes de títulos (1 punto)
- Encontrar la longitud máxima del título (2 puntos)

Total: 10 puntos

