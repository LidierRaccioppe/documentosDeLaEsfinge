Cabecera
========


Parrafos
----

Para escribir paráfos solo tenemos que escribir sin marcar. Si queremos remarcar con *cursiva*. La **negrita**es con
doble asterisco. Para ejemplos de codigo las dobles comillas ``print("Hola Mundo")``.

* No puede estar submetidos
* Los contenidos no pueden comenzar con un espacio en blanco. * texto* no funciona
* Tiene que estar separado por caracteres separadores. Puede usar la barra de escape para permitir unir palabaras : Esto\ **Es**\una palabra

.. _nivelSecciones:
Niveles de secciones.
---------------------

Los distintos niveles de seccion se escriben de la siguiente forma:

* = para secciones.
* "-" para subsecciones.
* ^ para subsubsecciones.
* " para parrafos.

Listas
----
Las listas se marcan con *.

Listas Desordenadas
^^^^

* Lista Simple
* Otro elemento de la lista

 * con subniveles
 * muy facilemente

Listas Ordenadas
^^^^
1. Primer elemento.
2. Segundo elemento.

 2.1. Subelemento
 2.2. Otro subelemento

#. Otro tipo de lista
#. Ordenada

Listas de definiciones
^^^^

Termino (primera linea de texto)
 Definción del termino, que tiene que estar tabulado

 Puede tener varias linea o varios parrafos.
Siguiente termino
 Con su definición.

Bloques Literales
^^^^

Despues de un texto normal, podemos dejar un parrafo con un ejemplo de codigo::

 def hola_mundo():
     print("Hola Mundo")
     return None

 def adios_mundo():
     print("Adios Mundo")

El texto continua normal despues del bloquea.

Bloques Doctest
^^^^

Para los bloques de Doctest no requieren ninguna marca especial.

 >>> 1 + 1
 2

Hipervinculos
^^^^

Enlaces externos
````

Podemos consultar la documentacion de uso de `restructuredtext <http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`_ para consultar la ayuda.

El parrafo tiene un enlace a la pagina principal de `Daniel Castelao`_.

.. _Daniel Castelao: https://www.danielcastelao.org

Enlaces internos
````
Puedo hacer referencias con una etiqueta colocada arriba con :ref:`nivelSecciones`.

