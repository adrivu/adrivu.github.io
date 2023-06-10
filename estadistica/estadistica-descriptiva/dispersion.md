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
+ Si se multiplica una constante a la variable, la varianza es la antigua por la constante al cuadrado.

### Desigualdad de Tchebychev

Fórmula que dice que en `a` veces la desviación típica se encuentran siempre `1-(1/a^2)` porcentaje de datos. Por ejemplo en a=2 tenemos 0,75% de los datos, osea, en la media masmenos 2 veces la desviación típica tenemos al menos el 75% de los datos.

### Rango

Es la diferencia entre el máximo y el mínimo. Es facil de calcular pero sensible a valores extremos.

### Rango intercuarlítico

Es el rango pero calculado entre el primer y el tercer cuartil. Se usan para su cálculo la mitad de los datos.

### Coeficiente de variación

Es el cociente entre la desviación típica y la media.

`CV=S/|x̄|`

Es **adimensional**, por lo que se utiliza para comparar entre variables. Cuanto más grande es su valor, menos representativa es la media. Si es menos de 0,1 es muy buen valor, y entre 0,5 y 1 se empieza a considerar mala.

De forma muy similar podemos hacer lo mismo con el rango intercuarlítico y la mediana.

### Simetría

Coeficiente que nos dice si tiene colar hacia algún lado. Hay varias formas de calcularla, pero la más famosa es el primer coeficiente de Fisher:

`g1=m3/S3` 

siendo m3:

`m3=((x1-x̄)^3+(x2-x̄)^3+...+(xn-x̄)^3)/n`

Esto representa que si g=0 es simétrica (coincide media y  mediana), si g>0 es simetrica positiva (cola hacia la derecha) y viceversa.

### Curtosis

Coeficiente que nos dice si la distribución es plana o curvada. Se suele utilizar el segundo coeficiente de Fisher, que es:

`g2=(m4/S4)-3`

Siendo m4:

`m4=((x1-x̄)^4+(x2-x̄)^4+...+(xn-x̄)^4)/n`

Si g2 es 0 es igual de picuda o **apuntada** que la normal, si es mayor lo será mas y si es menor lo será menos.

[Retorno al hub](/)