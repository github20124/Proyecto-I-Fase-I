
# Hola Soy Pedro Cabrera, mucho gusto.

Para el presente proyecto, esta a bien el analizar el proceso de Ingeniera de Características sobre el deporte de Levantamiento de Pesas. 

El data set contenido en el proyecto, consiste en una base de datos de Levantamiento de Pesas en Estados Unidos del mes de enero de 2024. OpenPowerlifting está creado desde un archivo de dominio público de la historia del levantamiento de pesas y obtenido de Kaggle.

# Porque es importante proyecto

 El levantamiento de pesas es un deporte en el que compiten para levantar la mayor cantidad de peso para su clase en tres levantamientos con barra separados, tales como: sentadilla, banco y peso muerto.

Si lo haces correctamente, el entrenamiento con pesas te ayudará a perder grasa, aumentará tu fuerza y tono muscular, y mejorará tu densidad ósea

# Cómo iniciar con el proyecto

Para el analisis del presente proyecto, al utilizar la Ingeniería de Características, se inicia con el siguiente proceso:

1. Importación de diferentes librerías a utilizar en python tales, como: pandas, numpy, matplotlib y seaborn.

2. Se carga el dataser OpenPowerlifting.csv y se realiza un análisis exploratorio que incluye tablas de cuantos columnas y líneas posee el proyecto, posteriormente la visualización en gráficas de las principales variables o columnas del data set, los cuales se incluyen en el Notebook 1 o Cuarderno I Fase I.

3. Para el caso del Notebook Proyecto y Fase I, constituye todo el proceso de realización de Ingeniería de Características, el cual se detalla a continuación:

  a) Carga del dataset y analizar sus variables.
  b) Seleccionar varibables a predecir, en este caso la categórica Place y las predictoras, tales como: Edad, Genero, Equipo, División, entre otras.
  c) Lo siguiente fue imputar los datos faltantes, tanto para las variables númericas, como categóricas.
  d) Seguidamente, se codificarons las variables categóricas,utilizando de conformidad con la naturaleza del dataset, una codificación por frecuencia. Una asignación de valores en función de la frecuencia de cada categoría en los datos es recomendable en el caso de asigna valores numéricos más altos a las categorías que aparecen con mayor frecuencia y valores numéricos más bajos a las categorías menos frecuentes.
  d) Se analizaron cada variables y después de efectuar la imputación por medio de media o mediana, se imputó por lo más conveniente y donde el resultado opitmizará dicha variable analizada.
 e) Para el caso de variables después de analizar su imputación y no aportaba al modelo fueron eliminados.
 

 En la parte de analisis de valores atípicos u outliers, se realizó lo siguiente:
  a) Identificar variables discretas y continuas en primer lugar
  b) Se utilizó el método del rango intercuartílico (IQR) para identificar outliers

  Asi también se efectuó el tratamiento de variables, se realizó así:

  a) Transformación logaritmíca
  b) Transformación a la inversa
  c) Transformación polimonial
  d) Transformación boxcox
  e) Transformación Jeo-Johson

  Por último se efectuo la Estandarización, normalización o escalado de valores para todas las variables continuas y de donde se visualizaron también su efecto después de realizado todo el proceso de Ingeniería de Características.
## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Appendix

Any additional information goes here


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

