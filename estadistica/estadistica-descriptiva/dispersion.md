---
layout: page
title: Medidas de dispersión
permalink: /Medidas de dispersión/
---

Bienvenido al apartado de Medidas de Dispersión. Estas medidas son capaces de arrojar información sobre lo cerca o lejos que están los distintos valores. Son necesarias a la hora de conocer la dispersión de una variable. Por ejemplo el conjunto -1000 y 1000 tienen de media 0, y el conjunto -1 y 1 también, pero su distribución es muy distinta.

### Varianza

Es la medida más importante, conocida como S2 o σ2,  y su forma cálculo es:

`(x1-x̄)^2+(x2-x̄)^2+...+(xn-x̄)^2/n`

Con esto calculamos la distancia de cada valor a la media, y se hace al cuadrado para eliminar los valores negativos. 

La **desviación estándar** es la raiz cuadrada de la varianza.

Para los cálculos usualmente se usa la cuasivarianza, que en lugar de dividir por n divide por n-1.  

La varianza tiene las siguientes características:  
- Si se suma una constante a la variable, la varianza no cambia.
+ Su se multiplica una constante a la variable, la varianza es la antigua por la constante al cuadrado.

### Media

Aunque lo llamemos la media, existen muchas medias. Para que una medida pueda ser llamada media se tienen que cumplir tres requisitos:

1. Se deben utilizar todas las observaciones.
2. Su valor está entre el máximo y el mínimo de las obsevaciones.
3. Sus unidades son las mismas que las de las observaciones.

Veamos algunas de las medias más utilizadas:

|Nombre|Ecuación|Definición|Usos|
|:---:|:---:|:---:|:---:|
|Aritmética|=(x1+x2+...+xn)/n|Es la media más común|Para longitudes, pesos...|
|Recortada|Igual que aritmética sin extremos|Se eliminan los valores α% más grandes y pequeños|Para eliminar valores atípicos|
|Ponderada|(x1w1+x2w2+...+xnwn)/(w1+w2+...+wn)|Para dar más importancia o peso a algún valor|Centros de masas, exámenes con ponderación distinta|
|Geométrica|(x1x2...xn)^(1/n)|Fundamentalmente en economía|Promediar porcentajes|
|Armónica|n/(1/x1+1/x2+...+1/xn)|Para datos que vienen en proporciones|km/h, kg/m3|

Dos caracterísiticas clave
+ Si sumamos a cada observación una constante k, la media será la media anterior mas k
+ Si multiplicamos a cada observación una constante k, la media será la media anterior multiplicada por k
 
La media es **el centro de gravedad** de la distribución

### Mediana
La mediana es el valor que al ordenar los datos deja al 50% a su izquierda y al otro 50% a su derecha. Su valor será el del valor central si es impar X_(n+1)/2 y haciendo la media de los dos valores centrales si es par (X_(n+1)/2  +  X_(n)/2)/2

La mediana se suele usar para ver si la media no está demasiado afectada por los valores extremos, debido a que la media es muy poco robusta respecto a la mediana.

Ejemplo:
+ 1, 2, 2, 2, 2, 2, 3, 4, 90
    - Mediana = 2
    - Media = 12

Esto no es tan extraño que suceda en el mundo industrial, debido a malas lecturas de sensores o simplemente situaciones extraordinarias que no tienen por qué ser tenidas en cuenta en los estudios.

### Moda

La moda es el valor que mas veces se repite. En el ejemplo anterior la moda también sería 2.

### Cuantiles

Son similares a la media, solo que en lugar de dividir al 50% hacia cada lado, divide en otras proporciones. Los más famosos son los cuartiles, que dividen al 25, 50 y 75%, y los percentiles, que son cada 1%.

[Retorno al hub](/)