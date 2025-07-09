# 🌆 IMT2118-Proyecto-Manhattan 🌆

Análisis Geoespacial de Propiedades en Nueva York

El distrito de Manhattan es conocido por ser la zona residencial más costosa de toda la ciudad
de New York, contando con un aproximado de 8,6 millones de habitantes, y, según la página tinsa
en 2013, también es conocido por ser una de las zonas de tiendas más caras y exclusivas de todo el
mundo. Un ejemplo concreto de esto ocurrió con la empresa Zara, que gastó una suma total de 324
millones de dólares por un local de este distrito.
Las razones del precio de sus residencias son variadas, pero destaca por sobre todo en ser un lugar
lujoso y turístico, y no es para menos, puesto que ((alberga varias atracciones tur´ısticas famosas, como el
Empire State Building, el Chrysler Building, el Rockefeller Center, el World Trade Center,
el puente de Brooklyn y Central Park)).

Manhattan es uno de los lugares más caros para vivir, por ende, la meta de este proyecto consiste
principalmente en poder facilitar la localización de los lugares potencialmente más efectivos para poder
proliferar adecuadamente en esta ciudad, segúun los intereses de un potencial interesado en adquirir
una vivienda. Se intenta responder a la pregunta ¿En qué zonas es más probable encontrar pro-
piedades en venta que sean favorables para un futuro comprador, considerando factores
económicos, índices delictivos, cercanía a servicios de transporte, de salud y educación,
entre otros?

Este proyecto fue realizado en Google Colab, hay que seguir la estructura de directorios y ficheros indicada en el repositorio, y simplemente ejecutar el .ipynb. En caso de utilizar otro entorno, probablemente habrá que instalar librerías faltanes.


Funcionamiento General del Proyecto

El proyecto se divide en tres grandes etapas:

1. Preparación de datos, esto incluye la proyección, geodoficación, limpieza, operaciones geoespaciles de los geodataframes como la unión espacial, etc.


2. Creación del modelo predictivo usando el algoritmo Random Forest con el GeoDataFrame resultante de la unión de todos los 