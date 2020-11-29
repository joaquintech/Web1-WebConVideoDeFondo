Pagina con video de fondo.

Se creará en 3 capas
1- video
2- capa transparente 
3- texto

==============
El video se puede descargar de una librería con licencia abierta:
https://www.pexels.com/videos/
==============
1) Se crean el header (donde irá el video) y se le agrega 2 clases: header y content

2) Dentro del header se crearán 3 div, una para cada capa.
2.1) div para video, con la clase header-video. En la que se agregó el video a través de la etiqueta <video>.
2.2) div para capa transparente, con la clase header-overlay
2.3) div para los textos y botón

3) Se enlaza el main.css mediante la etiqueta <link> debajo dentro de <head>

4) Hasta ahora se puede ver el video pero aparecerá detenido, por lo que es necesario agregar autoplay en la etiqueta <video>. También se agrega loop, para que se reproduzca de forma infinita.
