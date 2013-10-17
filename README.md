Sistemas y Tecnologías Web
==========================
David Hernández Bethencourt

Práctica 4: Añadir hojas de estilo a Rock, Paper, Scissors
-----------------------------------------------------------------------------
La práctica consiste en añadir a la aplicación Rock, Paper, Scissors, de la "[práctica anterior](https://github.com/DavidHerBet/SYTW-pr3-Haml)", hojas de estilo cascada (CSS).

Introducción
------------
<p align="center">
  <img src="http://altherius.99k.org/materias/paginasweb/css/imagenes/css.jpg" height="280" width="520"></img>
</p>

Las hojas de estilo (style sheets) son conjuntos de instrucciones, a veces en forma de archivo anexo, que se asocian a los archivos de texto y se ocupan de los aspectos de formato y de presentación de los contenidos: tipo, fuente y tamaño de letras, alineación y posicionamiento del texto, colores y fondos, etc. Las hojas de estilo permiten liberar la composición del texto de los aspectos visuales y favorecen que se estructure y anote mediante códigos que permiten un tratamiento más eficaz de los contenidos.

Bootstrap
---------
<p align="center">
  <img src="http://alanchavez.com/wp-content/uploads/2013/09/Twitter-Bootstrap-Logo.jpg" style="text-align: center"></img>
</p>

Bootstrap es el framework de Twitter que permite crear interfaces web con CSS y Javascript. Hemos empleado este framework para el desarrollo de esta práctica.

Instrucciones
-------------
1. Se ejecuta el programa de forma manual o mediante Rake:

        $ rackup
        $ rake rps

2. Ahora deberemos ir al puerto 9292 de localhost:

        $ http://localhost:9292

3. Una vez allí introducimos una jugada y observamos el resultado. Veremos la mejora estética al añadirle hojas de estilo y alguna funcionalidad nueva.


**Notas:**
- Usando las tareas de rake (rock, paper o scissors), podremos visualizar mediante cURL el código HTML que se genera con el resultado de nuestra elección. Para ello primero deberemos de haber iniciado el servidor previamente, sino dará error.

---

Universidad de La Laguna  
Escuela Técnica Superior de Ingeniería Informática
