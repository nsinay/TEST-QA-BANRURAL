El plan de ataque para resolver la funcionabilidad de este software es el siguiente:

Revisar la funcionabilidad en la consolola del navegador para encontrar los errores de una manera
mas rapida y sencilla.
Revisar el codigo con puntos por cada metodo utilizado, ademas de revisarlo a simple vista

Se encontraron varios errores, acontinuacion se describiran los errores y la solucion los cuales se mencionaran:
1. La estructura del proyecto fallo en la sintaxis. Body no abarcaba todo el proyecto como deberia de ser para que funcionara, se soluciono cambiando el cierre body hasta el final del codigo.
2. Linea numero 46 del codigo, estaba mal escrito ya que la sintaxis no fue la correcta esto impedia realizar el calculo la solucion es la siguiente: let randomNumber = Math.floor(Math.random()*100) + 1;
3. Linea numero 48 del codigo, ATTEMPS tenia solamente un numero 5 y deberia de ser 10 y asi lograr los 10 intentos que requiere el programa. 
4. Linea numero 51 del codigo, nuevamente habia un error en la sintaxis hacia falta un punto la solucion es la siguiente: const lowOrHi = document.querySelector('.lowOrHi');
5. Linea 60 del codigo, habia una confuncion en la comparacion del tipo de datos la solucion fue la siguiente: let userGuess = parseInt(guessField.value); agregando el parseInt para poder realizar una comparacion correcta de tipos de datos. 
6. Linea 69 a 83 del codigo, el anuncio a mostrar estaba invertido, al igual que el color en el  primer anuncio se tuvo que cambiar de negro a verde y reacomodar los anuncios para que funcionen de una manera correcta.
7. En la linea 101 y 109 del codigo, nuevamente la sintaxis fallo ya que estaba mal escrita la funcion addEventListener.
8. En la linea 128 del codigo, hacia falta una multiplicacion para asi lograr un buen calculo, solucion:
randomNumber = Math.floor(Math.random() * 100) + 1;
10. En la linea 61, 95, 96 y 97 del codigo, se agrego una condicion para cumplir con el siguiente requerimiento:
El número que ingresará el jugador debe pertenecer al conjunto de los enteros (e.g. 1, 2, 3...), en caso que no ingrese un número entero, debe mostrarse una alerta al usuario y no se debe incrementar un intento de prueba.


