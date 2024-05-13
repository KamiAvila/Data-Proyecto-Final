#### Data Science for Development-Proyecto-Final

### Repositorio Proyecto Final:

### Objetivo:
Observar que lugares son los "puntos calientes" de homicidios y asesinatos en el Ecuador para así comprender el fenómeno, los patrones y frecuencia de la violencia ejercida en forma de asesinatos y homicidios según características específicas durante el año 2023, además como se encuentra la distribución de los homicidios en el territorio nacional. 

### Metodología :
Mediante la separación por categorías como: edad, género, lugar de ocurrencia, tiempo del día en el que ocurre el homicidio y herramientas de vizualización se pudo establecer por la frecuencia de ocurrencia que lugares, ciudades, grupos etarios, entre otras características que grupos fueron los más afectados por la violencia en el país a lo largo del año 2023.

### Principales Hallazgos:
Entre los principales resultados se obtuvo:

- La mayoría de homicidios ocurren en horas de la noche (oscuridad: pasado las 18:00h hasta las 2:00h) y en espacios públicos

- Que el principal grupo etario afectado por este tipo de violencia son los jóvenes adultos y adultos comprendidos entre 20 y 35 años de edad

- Que 7391 de los 8009 homicidios registrados fueron contra hombres

 - Existieron 262 abortos que fueron registrados en la base
 
 - Las 5 provincias más violentas del país solo contando el número de homicidios son: Guayas, Los Ríos, Manabí, El Oro y Esmeraldas, (todas de la región costa).

 - Las 5 provincias más violentas según la tasa de homicidios por cada cien mil habitantes son: Esmeraldas con 55.24, Guayas con 52.82, Santa Elena con 33.96, Sucumbíos con 33.67 y El Oro con 33.45, respectivamente.

 - Los 5 cantones con más homicidios registrados son: Guayaquil, Durán, Esmeraldas, Quevedo y Quito.

 - Los 5 cantones más violentos según la tasa de homicidos por cada cien mil habitantes son: San Jacinto de Yaguachi con 406.29, Pedernales con 401.11, Naranjal con 343.92, Esmeraldas con 187.43 y Babahoyo con 164.79, respectivamente.
 
 Además se realizó un mapa de calor y uno por clusters con las coordenadas exactas donde ocurrieron los homicidios.

 ### El siguiente documento brinda un análisis más detallado del estudio y lo encontrado en el mismo:
 
[Data_Science_Proyecto_Final.docx](https://github.com/KamiAvila/Data-Proyecto-Final/files/15284733/Data_Science_Proyecto_Final.docx)

### ¿Cómo y qué instalar para correr adecuadamente el código?

Primero instalar paquetes de python:

- ! pip install ISLP
  
- ! pip install sweetviz
  
- ! pip install numpy
  
- ! pip install keplergl
  
- ! pip install folium

Luego instalar librerías:

- import plotly.express as px

- import numpy as np

- import pandas as pd

- import matplotlib.pyplot as plt

- import seaborn as sns

- import sweetviz as sv

- from google.colab import files

- import io
  
- from google.colab import drive
  
- from keplergl import KeplerGl

- from folium.plugins import HeatMap

- from sklearn.decomposition import PCA

- from sklearn.preprocessing import StandardScaler

Instalar las bases de datos, preferiblemente tenerlas en google drive y con los mismos nombres de código fuente:

[Bases- Homicidios y Detenidos.zip](https://github.com/KamiAvila/Data-Proyecto-Final/files/15284969/Bases-.Homicidios.y.Detenidos.zip)

Las bases de datos provienen del Ministerio del Interior como bases de homicidios intencionales y de aprehensiones: http://181.113.21.13:8080/registroinicial-war/estadisticas.html

Una breve descripción de las bases es que tienen códigos de circuitos, subcircuitos y provincias, además de características de las víctimas de los homicidios, como etnia, género, instrucción, entre otros. Además de características del hecho ocurrido como el arma con la que se ejecutó, la hora, coordenadas exactas, entre otros. La muestra brinda información sobre 8009 homicidios intencionales a lo largo de 2023, donde la gran mayoría de variables son categóricas.



