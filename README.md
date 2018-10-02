# descripccion del juego
en este repositorio encontrara lo que se hizo en estas 10 lecciones
En este texto se te explicara paso a paso lo que pasa en cada una de las lecciones realizadas, la intención de estas lecciones es hacer un juego y mostrar como será su evolución en cada leccion.

PRIMERA LECCION 1:
En esta lección encontraras en HTML del juego que no cambiara en las siguientes lecciones, pero lo que nos llamara la atención, será el cambio que se va a producir en el CSS y JavaScript como va ir evolucionando en esta primera parte no será mucho lo que se encontrara, solo unas figuras de colores serán lo más interesante de este código; claro creando un lienzo (canvas).

SEGUNDA LECCION 2:
En esta lección el código se lograra crear una bolita y que esta misma se mueva, teniendo en cuenta que borraremos el lienzo antes de cada fotograma, se limpia el código y tendremos una bola con movimiento.

TERCERA LECCION 3:
En esta lección tendremos que hacer que la bolita tenga una detección de colisión, que rebote de arriba y abajo, derecha e izquierda con unos bordes ya predefinidos genere una colisión simple, claro el JavaScript cambiara algo con nuevos llamados.

CUARTA LECCION 4:
En esta lección lograremos crear una interacción, donde el usuario será el que maneje este objeto, la cual será una paleta que golpeara la pelota pero por el momento solo crearemos la paleta y lograremos que se mueva con nuestros movimientos.

QUINTA LECCION 5:
Aplicaremos un final de juego para que tenga lógica y podamos perder, entonces implementaremos el final del juego, donde si la paleta no golpea la bola cuando caiga se perderá de lo contrario seguirá jugando, también implementaremos un ALERT donde diga GAME OVER.

SEXTA LECCION 6:
En esta parte de nuestro juego implementaremos variables ladrillos que todavía no será solidos pero ya estarán declarados, también los dibujaremos.

SEPTIMA LECCION 7:
En esta leccion aplicaremos una función para detectar colisiones, además lograremos que los ladrillos desaparezcan cuando reciban un golpe entonces actualizaremos el status del bloque para no tener que pintarlo de nuevo; claro tendremos que activar la función colisiones.

OCTAVA LECCION 8:
En esta leccion lograremos hacer un contador que nos muestra los ladrillos destruidos y que cuando hallamos acabado con todos, nos muestre un mensaje de victoria, para que nos muestre el contador tendremos que dibujarlo con canvas, similar a  dibujar un circulo o cualquier otra figura y debemos mostrar un mensaje

NOVENA LECCION 9:
En esta leccion ya con los movimientos de la paleta añadidos al teclado, añadiremos esto al ratón
Entonces asociaremos el movimiento de la pala al ratón, con una función en este caso llamada mauseMoveHandler y esta una variable y un condicional.

DECIMA LECCION 10:
Este es el último paso donde le daremos vidas al jugador donde el jugador cada vez que deje caer la bola perderá una vida, y cuando pierda todas sus vidas terminara el juego, y si destruye todos los bloques gana, claro está destruirlos aunque sea solo con la última vida, se implementara un refresco de animación con requestAnimationFrame()
