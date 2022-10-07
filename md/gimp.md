# Cómo instalar la última versión de GIMP en nuestro Ubuntu
![Screenshot](img/gimp.jpg)

Seguramente que muchos de vosotros echáis en falta tener Gimp en vuestra distribución o sabor oficial así como algunos echarán en falta tener la última versión de este editor de imágenes.
La última versión de este popular editor de imágenes incorpora bastantes correcciones de bugs, nuevas traducciones y también soporte para nuevos plugins, una faceta suya que mejora notablemente el trabajo de muchos de sus usuarios. Tener la última versión de GIMP es posible gracias a los repositorios externos.
Para poder **instalar la última versión de GIMP en nuestro Ubuntu o derivados**, bien sean sabores oficiales o bien distribuciones que se basan en Ubuntu, necesitamos abrir la terminal y escribir lo siguiente:

`sudo add-apt-repository ppa:otto-kesselgulasch/gimp`

`sudo apt update`

`sudo apt install gimp`

Esto instalará la última versión estable de GIMP que es la versión 2.8.20. Además este repositorio cuenta con un extra de plugins que nos facilitará el uso de este programa, todo a través de la terminal. Algo más práctico y rápido que hacerlo de manera manual, uno tras otro. Para la instalación de estos plugins hay que escribir en la terminal lo siguiente:

`sudo apt install gimp-plugin-registry gimp-gmic`

Si por lo que fuera queremos eliminar el repositorio, sólo necesitamos abrir la terminal y escribir lo siguiente:

`sudo apt install ppa-purge ( en caso de no tener este programa)`

`sudo ppa-purge ppa:otto-kesselgulasch/gimp`

Tras esto se eliminará el repositorio añadido y entonces Ubuntu utilizará el repositorio oficial para instalar y gestionar las actualizaciones de esta famosa aplicación. El proceso como podéis ver es sencillo y fácil de hacer, pero hay que tener en cuenta que la versión más actual de GIMP no cambia sustancialmente la aplicación y puede que sea cuestión de semanas cuando recibamos estas versiones a través del canal oficial de Ubuntu. En cualquier caso, la elección es vuestra y dependerá del uso que queráis dar a GIMP.

