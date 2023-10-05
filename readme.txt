requestAnimationFrame(animate);:

requestAnimationFrame es una función proporcionada por los
 navegadores web que solicita que el navegador llame a una
  función específica para actualizar la animación antes 
  del próximo repintado. 
  En este caso, requestAnimationFrame se utiliza para 
  crear un bucle de animación.
Cuando llamas a requestAnimationFrame(animate);, estás 
diciendo al navegador que llame a la función animate antes
 del próximo repintado, creando así un bucle continuo de 
 animación.


################ DOCUMENT.BODY.APPENDCHILD(RENDERER.DOMELEMENT) ###############

 La sentencia document.body.appendChild(renderer.domElement); tiene como
  objetivo adjuntar el elemento del renderizador (que es 
  el lienzo WebGL) al cuerpo (<body>) del documento HTML.

En Three.js (y en muchas aplicaciones WebGL en general), el
 resultado de la renderización se muestra en un lienzo HTML,
  que es una etiqueta <canvas> en el documento HTML.
   Este lienzo es donde se dibujan y muestran los gráficos
    3D generados por la biblioteca Three.js.

La variable renderer.domElement representa el lienzo WebGL
 que Three.js usa para dibujar la escena 3D. La función 
 appendChild se utiliza para añadir este lienzo como un 
 hijo del cuerpo (<body>) del documento. Al hacerlo, el 
 contenido del lienzo (la escena 3D) se mostrará en la 
 página web cuando se visualice en un navegador. En 
 resumen, esta sentencia permite que la salida de la 
 renderización 3D se integre en la estructura de la 
 página HTML para que los usuarios puedan ver el contenido
  tridimensional en su navegador.


  https://threejs.org/build/three.js // IMPORTAR THREEJS