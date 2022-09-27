# Flow_2

Segundo ejercicio implementando NodeRed

# Introducción

Este ejercicio consiste en generar un TimeStamp legible cada segundo.

# Material Necesario
Para realizar este flow necesitas lo siguiente:

1. Ubuntu 20.04
2. NodeJS
* NPM
* NodeRed
* Nodos Dashboard

# Instrucciones de requisitos previos
Para realizar este flow necesitas lo siguiente
Instalación de NodeJS. (https://nodejs.org/es/)
Instalación de NodeRed. (https://nodered.org/)

# Instrucciones de preparación del entorno
Para ejecutar este flow, es necesario lo siguiente

1. Arrancar NodeRed con el comando node-red
2. Exportar el flow 1 creado en la actividad anterior e importarlo, una vez importado cambiar el nombre dando doble clic en el flow 1
3. Modificar el nodo Inyect con un intervalo de 1 segundo para mandar timestamp
4. Agregar un nodo funcion 

  var date = new Date(msg.payload);
  // Formato de fecha
  msg.payload = date.toString();
  return msg;

5.Observa los resultados en la pestaña debug

# Resultados

