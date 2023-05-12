![https://images.unsplash.com/photo-1574375927938-d5a98e8ffe85?ixlib=rb-4.0.3&q=85&fm=jpg&crop=entropy&cs=srgb](https://images.unsplash.com/photo-1574375927938-d5a98e8ffe85?ixlib=rb-4.0.3&q=85&fm=jpg&crop=entropy&cs=srgb)

# Análisis exploratorio de datos de Netflix

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) sobre el contenido de Netflix.

## Dataset

El dataset utilizado es una base de datos de títulos de películas y programas de televisión disponibles en Netflix del 1950 al 2023. El dataset cuenta con más de 6137 registros/filas y 15 variables.

**🔗 Link de la fuente de datos**

## Variables

Las variables incluidas en el dataset son las siguientes:

- `id`: identificador único de cada título.
- `title`: título del programa o película.
- `type`: indica si el título es una película o un programa de televisión.
- `description`: una descripción breve del título.
- `release_year`: el año de lanzamiento del título.
- `age_certification`: la clasificación por edad del título (Ej: PG, R, TV-14, etc.).
- `runtime`: la duración en minutos para las películas o el número de temporadas para los programas de televisión.
- `genres`: el género o géneros del título.
- `production_countries`: los países donde se produjo el título.
- `seasons`: el número de temporadas que tiene el programa de televisión.
- `imdb_id`: el identificador único de la película o programa de televisión en la base de datos de IMDB.
- `imdb_score`: la calificación que tiene el título en IMDB.
- `imdb_votes`: el número de votos que tiene el título en IMDB.
- `tmdb_popularity`: la popularidad del título en la base de datos de TMDB.
- `tmdb_score`: la calificación que tiene el título en la base de datos de TMDB.

## Objetivos del análisis exploratorio de datos

Los objetivos principales del análisis exploratorio de datos son los siguientes:

1. ¿Cuáles son las variables y tipos de datos presentes en el conjunto de datos?
2. ¿Hay más películas o series en el conjunto de datos?
3. ¿Cuáles son las 10 películas y series más populares según el ranking?
4. ¿Cuál es el país que produce más contenido en comparación con el país que produce menos contenido?
5. ¿Qué país produce más contenido, series o películas?
6. ¿Cuáles son las palabras que más se repiten en la descripción de las películas y series?
7. ¿Cuál es la película y serie con la mayor duración?
8. ¿Cómo se comparan las palabras que más se repiten en la descripción con la película y serie de mayor duración en minutos?
9. ¿Cuáles son las 10 películas y series con mayor número de puntaje?
10. ¿Quiénes son los actores y directores de las películas más populares?
11. ¿Quiénes son los directores más populares en cada región?
12. ¿Cuál es la mejor película de cada década según el puntaje de IMDB?

## Resultados

Los resultados del análisis exploratorio de datos se presentan en el archivo `file_name.ipynb`. En este archivo se incluyen visualizaciones y estadísticas descriptivas que responden a los objetivos planteados.

Entre los hallazgos más destacados se encuentran:

- La distribución de películas y programas de televisión en Netflix es casi igual, con una ligera ventaja para las películas.
- Estados Unidos es el país que produce la mayor cantidad de títulos en Netflix, seguido de India y el Reino Unido.
- Los géneros de películas y programas de televisión más comunes en Netflix son la comedia, el drama y el documental.
- La película con la calificación más alta en Netflix es "The Shawshank Redemption", mientras que el programa de televisión con la calificación más alta es "Breaking Bad".
- Los actores y actrices más comunes en Netflix son Anupam Kher, Shah Rukh Khan y Om Puri.

## Conclusiones

En este proyecto se realizó un análisis exploratorio de datos sobre el contenido de Netflix, con el objetivo de identificar patrones y tendencias en los datos. Los resultados obtenidos permiten conocer mejor la distribución de películas y programas de televisión en Netflix, así como los países, géneros, actores y calificaciones más comunes. Este análisis puede ser de utilidad para entender mejor las preferencias de los usuarios de Netflix y para la toma de decisiones en cuanto a la adquisición de nuevos títulos para la plataforma.

