# Mono App

1. Descargar los archivos que no digan demo___
2. Crear la siguiente interfaz

a) Dar clic en la opcion anadir pantalla y llamarla scrJugar
b) Crear otra ventana mas y llamarala scrHallOfFame

c) Empezar a llenar las propiedades
  1. Escribir en la ventana acerca de: "Hecho por nombre...", por ejemplo.
  2. icono si aparece: colocar la imagen iconoApp.png
  3. AnimacionAlAbrirPantalla: Fundido
  4. OrientacionDePantalla: Vertical
  5. Titulo: borrar y seleccionar invisible
d) Anadir un archivo que se llama Pantalla_Principal.jpg
e) Poner una dispocion vertical, ajustar al ancho y alto, colocar 3 botones con los siguientes textos y el nombre descriptivo:
  1. btnJugar 
  2. btnHallOfFame 
  3. btnSalir
f) Subir loas archivos para las imagenes en los botones en orden: btnJugar.png, btnHallOfFame.png y btnSalir. Hacer mas chicos el alto y ancho de las pantallas.
ancho: 150 px por ejemplo y alto: 55 px y quitar el texto del boton.

g) Seleccionar la pantalla <bold>srcHallOfFame</bold>
h) Agregar un titulo: Puntuaciones mono loco, por ejemplo.
i) Poner una disposicion Tabular(modificar las propieddes columnas 2 y registros 2, 
colocar una etiqueta con texto: Puntos, cambiar nombre a . Colocar otra etiqueta (nombre, color negrita, ancho de 120px, centrado(posicion de texto)) y 
una disposicionHorizontal(configurarlo en centrar y color car un boton, colocar la imagen btnSalir y ajustar el tamano). Ir modificando ancho para que luzca como en la imagen.

2) Ir al menu Almacenamiento/Storage y selecciona TinyBD1, para almacenar de forma persistente los nombres y puntos. (Almacena parejas de elementos -> Identificar: valor = etiqueta en appInventor). 

3) Ir a la pantalla srcJugar
   a) Orientacion: Vertical
   b) AnimacionAlAbrirPantalla y AnimacionCierreDePantalla: Fundido
   c) Anadir un lienzo y una disposicion horizontal
   d) Seleccionamos el lienzo y ajustamos ancho y alto.
   e) Agregar la imagen: Bosque.png
   f) Anadir los sprites: sprMono (MonoSprite1.png) y ajustar ancho y alto en px. y subit MonoSprite2.png
   g) sprPlatano -> 
      sprVida3 -> CaraMono.png
      sprVida2 -> CaraMono.png
      sprVida3 -> CaraMono.png
   h) Anadir la image game over - sprGameover y seleccionar como no visible
   i) Anadir relojes:
     1) Caida de platano: rljCaidaPlatano, intervaloDelTemporizador: 100 (ms)
     2) Caida de mono: rljMono, intervaloDelTemporizador: 500 (ms)
     3) Reloj dificultad: rljDificultad: 10000 (ms)
     4) Caida de game over: rljGameOver, intervaloDelTemporizador: 3000 (ms)
   j) Anadir notificador, se encuentra en Interfaz de Usuario
   k) Anadir un componente TinyBD
   l) Anadir un sonido --> Componente reproductor (Dancing_On_Green_Grass.mp3) y un componente sonido (Monkey.wav)

## Diseno

   [diseno1](./demoDiseno1.png)
  [diseno2](./demoDiseno2.png)
  [diseno3](./demoDiseno3.png)

## Bloques
