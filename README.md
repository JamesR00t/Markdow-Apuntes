<!-- Cabecera de Metadatos-->

---
title: "Sintaxis Markdown"

autor: "James Root"

date: "2022/02/05"

---


<!-- Este es un comentario-->
# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titutlo 6




<!--Tipos de texto-->
This is an *italic* text utilizando un asterisco antes y despues de la palabra un * cursivo.

Este es un formato en **Negrita** utilizando dos asteriscos antes y despues de la palabra sin espacios.

Este es un texto ~~Tachado~~
con dos ~ antes y desoyes de la palabra sin espacions.

<!-- UL Listas desordenadas utilizando simplemente un * antes de cada palabra y un espacion -->
Estas es una lista desorenada:
* Manzana 
    * Item dentro de otro item
* Platanos
* Arroz

<!--Hacer una lista ordenada unicamente haciendo uso del numero y punto y espacio-->
Esta es una lista ordenada:
1. Manzanas
2. Platanos

    2.1. Nuumero dentro de otro numero 
3. Arroz

<!-- Generar enlaces-->

Para generar un enlace se usa colocando el nombre a mostrar entre corchetes [] y la direccion url entre parentesis (), si deseamos que tel el enlace muestre una etiqueta con un nombre distinto de la direccion, se coloca enseguida de la url,  dejando un espacio, entre comillas y dentro de los ().

[Google.com](https://www.google.com.mx/)


[Google.com](https://www.google.com.mx/  "google")


<!--Para generara una cita -->

Para generar una cita se genera con el signo de mayor que >
>Esta es una cita.

Para generar unas lineas solo realizan tres - o lineas inferiores _.

---
___

<!--Para generar un bloque de codigo-->
Para poder mostrar un bloque de codigo se puede realizar con tilde inversa ` al inicio y al final de el codigo.

`System.out.println("Hola Mundo!");`

Si deseamos mostrar un bloque de codigo podemos hacerlo entre ``` tres tildes y si deseamos especificar que tipo de lenguaje es podemos indicarlo enseguida de las primeras tres tildes.
Ejemplo:

```Java
System.out.println("Hola Mundo con Java !");
```

```html
<h1>Helloworld</h1>
<p>Con html</p>
```

### Para generar tablas:

Para generar tablas solo tenemos que darlo la presentacion como nosotros deseamoas.
Ejemplo:

Tabla1

| Columna1 | Columna2 | Columna3 |
| -------: | -------: | -------: |
| Fila1    | Fila1    | Fila1    |
| Fila2    | Fila2    | Fila2    |


### Para usar una imagen
Se puede usar una imagen de manera local o por medio de enlaces.

**Imagen por URL**

Se inicia con un ! para que markdown no lo identifique como un enlace y enseguida se abre un corchete [] dentro de los corchetes se realizara la el texto que se podria ver, posteriormente a los corchetes se abren parentesis () y dentro de los parentesis va la direccion URL de la imagen.

Ejemplo:

`![MR. ROBOT](https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/mr-robot-fotogramas-1633377951.jpg)`

![MR. ROBOT](https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/mr-robot-fotogramas-1633377951.jpg)


**Imagen de manera local**

Para las imagenes de manera local se realiza el mismo proceso solo que entre los () se ingresa la ruta de la imgane, adicionalmente una vez puesta la ruta de la imagen se puede colocar una descripcion entre "".
Ejemplo:

`![Mr. Robot](Mr. Robot.webp "Cartel de la serie")`

![Mr. Robot](Mr.Robot.webp "Cartel de la serie")