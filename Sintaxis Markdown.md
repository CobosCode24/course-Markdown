Primero de todo hay que tener en cuenta que este es un lenguaje que normalmente se usa para los archivos README.md que son aquellos que aparecen cuando entras a un perfil de GitHub y viene una presentacion. Pues bien, ahora vamos a ver algunas reglas de este lenguaje.

La primera regla es que para saltar de linea, como lo acabo de hacer, es necesario que el documento .md, le demos dos veces a la tecla 'intro', ya que si le damos una vez aparecería en la misma linea.

Otra de las reglas, aunque esta es mas bien una ventaja, es que este lenguaje admite tambien html puro, como por ejemplo, ``<br></br>``, ``<h1></h1>``, ``<ol></ol>`` y muchas mas...

---
---
---
<br>
Encabezados:

# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
~~~
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

---

~~~
Citas:

> Texto de ejemplo.
~~~
> Texto de ejemplo.
> > Texto de ejemplo.
>>> Texto de ejemplo.

---

~~~
Listas:
- Elemento de lista 1
- Elemento de lista 2
  * Elemento de lista 3
  * Elemento de lista 4
    + Elemento de lista 5
    + Elemento de lista 6
     7. Elemento de lista 7
     8. Elemento de lista 8
~~~
- Elemento de lista 1
- Elemento de lista 2
  * Elemento de lista 3
  * Elemento de lista 4
    + Elemento de lista 5
    + Elemento de lista 6
    7. Elemento de lista 7
    8. Elemento de lista 8
---
~~~
Códigos de bloque:
    ~~~
    Creando códigos de bloque.
    Puedes añadir tantas líneas y párrafos como quieras.  
    ~~~
~~~
~~~
Creando códigos de bloque.
Puedes añadir tantas líneas y párrafoscomo quieras.  
~~~
---
~~~
Separadores horozontales:
se pueden poner con: --- y ***
~~~
---
***

<br>

---
~~~
Énfasis (negritas y cursivas):
*cursiva*
_cursiva_
**negrita**
**negrita**
***cursiva y negrita***
___cursiva y negrita___
~~~
*cursiva*

_cursiva_

**negrita**

**negrita**

***cursiva y negrita***

___cursiva y negrita___

---
~~~
Links o enlaces:
Entre [] se pone el nombre del enlace y entre () la dirección web.

[enlace en línea](https://markdown.es/)
~~~
[enlace en línea](https://markdown.es/)

---
~~~
Código:
Para poner codigo en markdown lo mas sencillo es poner las etiquetas ` esto es una linea de código `. Esta se corresponde con <code></code> en html.
~~~
`
 esto es una linea de código.
`

---
~~~
Para poner imágenes:

![Texto alternativo](/ruta/a/la/imagen.jpg)
~~~
---
~~~
Links automáticos:
Solo con poner entre <> la direccion del enlace.
<http://www.limni.net>
~~~
<http://www.limni.net>

---
~~~
¿Como puedo omitir texto el markdown?
Simplemente poniendo la barra inbertida ' \ ' delante del texto que deseemos que no este con el formato markdown.
~~~
---

~~~
¿Como poner comentarios ?
 Se logra con la instrucción:
 [//]: <> (comentario) 
~~~

[//]: <> (comentario) 

---
~~~
Lista de tareas:
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
~~~
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
---

~~~
~~~
Para usar emojis, como norma general tienen el formato :nombreDelEmoji: , pero también podemos visitar diversas  paginas web como la de rxaviers.
~~~

[GitHub de rxaviers](https://gist.github.com/rxaviers/7360908)


~~~
Para que las palabras resalten se utiliza ==texto remarcado==
~~~
I need to highlight these ==very important words==.

---



<br><br><br>

© Todos los derechos reservados CobosCode24, 2022.
