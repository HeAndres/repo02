# Guía de Markdown

## 1. Títulos

En Markdown, tenemos distintos headers:

```
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
####### 7 almohadillas no crean un título más pequeño
```
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
####### 7 almohadillas no crean un título más pequeño

## 2. Saltos de línea

```
Esto no hace un
salto de línea

Dos retornos de carro, 

sí
```
Esto no hace un
salto de línea

Dos retornos de carro, 

sí


## 3. Comentarios
```
[commentario]: <> (Comentario que debe ir solo)

[//]: <> (Comentario que debe ir solo)

[//]: # (Comentario que debe ir solo)

<!--Comentario que puede ir o no solo-->

<!--Comentario multilínea que
debe ir solo-->

(no se muestra nada, todo funciona)
```
[commentario]: <> (Comentario que debe ir solo)

[//]: <> (Comentario que debe ir solo)

[//]: # (Comentario que debe ir solo)

<!--Comentario que puede ir o no solo-->

<!--Comentario multilínea que
debe ir solo-->

(no se muestra nada, todo funciona)

## 4. Negrita y cursiva
```
<!--El \ es otra forma de indicar salto de línea-->
**Esto va en negrita**\ 
*Esto va en cursiva*\
***Esto va en negrita y cursiva***\
```
<!--El \ es otra forma de indicar salto de línea-->
**Esto va en negrita**\
*Esto va en cursiva*\
***Esto va en negrita y cursiva***

## 5. Citas
```
> "Are you not entertained?!"\
-Maximus, "Gladiator"
    
> Cita
>> con
>>> subcitas
```
> "Are you not entertained?!"\
-Maximus, "Gladiator"

> Cita
>> con
>>> subcitas



## 6. Listas
### 6.1 Listas no enumeradas
```
+ Es indiferente usar     
+ \+, \- o \*. Sin embargo,
- al ponerlas en guiones sin
- dos saltos de línea,
* toma símbolos diferentes como
* diferentes listas, y las separa.
```
+ Es indiferente usar     
+ \+, \- o \*. Sin embargo,
- al ponerlas en guiones sin
- dos saltos de línea,
* toma símbolos diferentes como
* diferentes listas, y las separa.

### 6.2 Listas enumeradas
```
1. Para hacer listas enumeradas,
2. hay que escribir los números de cada item,
3. seguidos de un punto.
```
1. Para hacer listas enumeradas,
2. hay que escribir los números de cada item,
3. seguidos de un punto.

### 6.3 Listas anidadas
```
1. Item 1

    1.1. Subitem 1.1.

2. Item 2.

3. Item 3.

    * Subitem

* Item 1

  * Subitem

    * Subsubitem
```
1. Item 1

    1.1. Subitem 1.1.

2. Item 2.

3. Item 3.

    * Subitem

* Item 1

  * Subitem

    * Subsubitem

## 7. Enlaces

```
<http://youtube.com/>

[Ir a youtube](http://youtube.com/)

[Ir a youtube](http://youtube.com/ "Texto cuando se pone el cursor encima")
```
<http://youtube.com/>

[Ir a youtube](http://youtube.com/)

[Ir a youtube](http://youtube.com/ "Texto cuando se pone el cursor encima")


## 8. Tachado
<br><br>
En markdown, no existe el subrayado.
```
~~Sí existe el tachado~~
```
~~Sí existe el tachado~~

## 9. Líneas separadoras
```
Contenido 1
***

Contenido 2
---

Contenido 3
___

```
Contenido 1
***

Contenido 2
---

Contenido 3
___

También se pueden escribir con espacios entre los símbolos: el resultado es el mismo

## 10. Imágenes
```
![Imagen Gladiator: Error](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.pinimg.com%2F736x%2F9c%2F7e%2Fc3%2F9c7ec341a5d82a964f9dc7baac4f05ce--gladiator-film-gladiator-quotes-movie.jpg&f=1&nofb=1 "Marcus Aurelius en su máximo apogeo")

[![a](https://www.google.es/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](www.google.es)
```
![Imagen Gladiator: Error](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.pinimg.com%2F736x%2F9c%2F7e%2Fc3%2F9c7ec341a5d82a964f9dc7baac4f05ce--gladiator-film-gladiator-quotes-movie.jpg&f=1&nofb=1 "Marcus Aurelius en su máximo apogeo")

[![a](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.pinimg.com%2F736x%2F9c%2F7e%2Fc3%2F9c7ec341a5d82a964f9dc7baac4f05ce--gladiator-film-gladiator-quotes-movie.jpg&f=1&nofb=1 )](www.google.es)