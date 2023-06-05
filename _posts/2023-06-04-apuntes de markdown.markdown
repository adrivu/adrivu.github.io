---
layout: post
title:  "Markdown"
date:   2023-06-04 21:22:11 +0200
categories: jekyll update
---
En esta sección encontraréis cómo escribir la sintáxis básica de __markdown__, que será la empleada para escribir este blog

---
### Encabezados

Para crear encabezados, deberás colocar el símbolo \# antes del texto. Puedes colocar de 1 a 6 unidades de \* y su tamaño irá desde el más grande con uno hasta el más pequeño son 6. A continuación una pequeña muestra de cómo se muestra el texto con los diferentes encabezados.
# Encabezado 1
Escribiendo \#Encabezado 1
## Encabezado 2
Escribiendo \#\#Encabezado 2
### Encabezado 3
Escribiendo \#\#\#Encabezado 3
#### Encabezado 4
Escribiendo \#\#\#\#Encabezado 4
##### Encabezado 5
Escribiendo \#\#\#\#\#Encabezado 5
###### Encabezado 6
Escribiendo \#\#\#\#\#\#Encabezado 6

---
### Párrafos y cambios de línea

Lo primero, para crear otro párrafo basta con dejar una línea en blanco. Recordar no poner nunca sangrías si no es una lista.

Por otra parte, para crear un salto de línea  
como este, símplemente se debe introducir dos o más espacios en blanco y luego un salto de línea pulsando intro donde se quiera.

---
### Líneas horizontales

Para crear las líneas horizontales que estamos colocando como separadores de los diferentes apartados, basta con colocar tres guiones, barrabajas o asteriscos seguidos. No hay diferencias entre emplear uno u otro y nos dan todos el mismo resultado.

\*\*\*  
\-\-\-  
\_\_\_

---
### Negrita

Para crear texto en negrita, tienes que rodearlo o de dos asteriscos o de dos guines bajos.

\*\*ejemplo1\*\*  
**ejemplo1**  
\_\_ejemplo2\_\_  
__ejemplo2__  

---
### Cursiva
Se escribe igual que la negrita pero con sólamente uno de los elementos anteriores, es decir, sólo un asterisco o barrabaja.

\*ejemplo1\*  
*ejemplo1*  
\_ejemplo2\_  
_ejemplo2_  

---
### Negrita y cursiva

Este caso es similar a los anteriores, pero con tres elementos.

\*\*\*ejemplo1\*\*\*  
***ejemplo1***  
\_\_\_ejemplo2\_\_\_  
___ejemplo2___

---
### Código en una línea

Para esto, basta con escribir la línea entre comillas invertidas, que está en la misma tecla que el fin de interrogación.

\'ejemplo de código\'  
`ejemplo de código`

Si el texto que vamos a usar ya tiene comillas, debemos utilizar comillas dobles.

\`\`texto con \`comillas\` \`\`  
``texto con `comillas` ``

---
### Bloques de código

Para añadir más de una línea de código, basta con colocar tres comillas en las lineas anterior y posterior al código  
\`\`\`  
x=5  
y=3  
print(sum(x+y))  
\`\`\`  
```
x=5
y=3
print(sum(x+y))
```

---
### Enlaces

Para colocar enlaces lo que debe hacer es colocar entre corchetes el texto y después entre paréntesis la URL

Esto va a ser el enlace: \[Texto enlace\]\(https://adrivu.github.io/\)  
Esto va a ser el enlace: [Texto enlace](https://adrivu.github.io/)

Hay truquitos para el tema links, que es enlaces de referencia. Esto significa que puedes hacer una llamada a tu link más corta. 

[Enlance][Referencia]

[Referencia]: https://adrivu.github.io

\[Enlance\]\[Referencia\]

\[Referencia\]: https://adrivu.github.io

Si quieres mostrar los links, hazlo entre simbolos mayor que y menor que  
<https://adrivu.github.io>  
\<https://adrivu.github.io\>

---
### Citas

Para una cita, basta con colocar el símbolo mayor que antes del texto. También puedes colocar varios mayor que para crear citas anidadas

\> Solo sé que no se nada  
> Solo sé que no se nada

---
### Listas

Hay dos tipos de listas. Las desordenadas debes colocar antes de cada elemento un asterisco, guion o suma

+ Primer elemento
- Segundo elemento
* Tercer elemento

\+ Primer elemento  
\- Segundo elemento  
\* Tercer elemento  

Para hacerlas anidadas, se hace colocando cuatro espacios antes del siguiente elemento guión o el que pongas

+ Primer elemento
    + Segundo elemento
+ Tercer elemento

Para las listas ordenadas se coloca el número y un punto. Estas listas también se pueden anidar y  combinar

1. Primero
2. Segundo
    + Segundo bis
3. Tercero

---
### Imágenes

Para meter imágenes se hace igual que para meter links, solo que con una exclamación al principio

\!\[Esto es el texto alternativo\]\(Ruta de la imagen\)

![Carita sonriente](/imagenes/prueba.jpg "Carita")

Comentar que también se puede hacer lo de las referencias, de ponerlas en un lugar del texto para no poner toda la ruta. 

---

### Caracteres especiales

Si quieres que se vean los caracteres especiales como almohadillas, debes colocar antes una barra invertida \

---
### Tablas

Para hacer una tabla

|Cabecera|Otra|
|---|:---:|
|Elemento|otra mas|
|otra cosa|y última|

Para alinear, dos puntos donde quieras alinear, antes después o a los dos lados de los tres guiones que separan la cabecera

---
Con esto deberíamos estar listos para empezar, olvamos al [hub](/index.md)