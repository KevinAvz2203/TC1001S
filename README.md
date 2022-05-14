# RESPOSITORIO GIT PARA LA CLASE TC1001S
Repositorio para alojar los ejercicios, prácticas y tareas a realizar en el curso de Herramientas Computacionales: El arte de la analítica, en el Tec de Monterrey Campus Sonora Norte.

## ESTUDIANTE
Kevin Alexis Valdez Zamora

## MATRICULA
A01254336

## LISTADO DE EJERCICIOS
* El programa prueba.c es un ejemplo para compilación en el lenguaje C.

* El programa prueba.py es un ejemplo para ejecución con python.

* Actividad 1 Juego Pintando: Consistia en utilizar la libreria Turtle para modificar el codigo base 
				para agregar un color nuevo y 3 figuras geoétricas: un círculo, un rectángulo y un triángulo.

* Actividad 2 Juego de la Víbora: En este ejercicio modificamos el código del juego  clásico de la serpiente. Hicimos que la
				comida se moviera al azar un paso a la vez y que tanto la serpiente como la comida cambien
				de color conforme la serpiente se alimenta, excluyendo el color rojo ya que este representa
				el fin del juego el chocar.

* Actividad 3 Juego del Packman: En esta actividad modificamos el juego de Pac-Man, modificamos el tablero que venia por
				defecto para tener una apariencia más clásica, al igual que hicimos a los fantasmas más 
				rápidos e incluso se le añadió mayor inteligencia al fantasma rojo ya que persigue al 
				Pac-Man.

* Actividad 4 Juego del Tiro Parabólico: Para este ejercicio aumentamos las velocidades de tanto los proyectiles disparados como el
					de los balones azules (objetivos). Asímismo, hicimos que el juego no tenga fin, esto fue
					posible ya que ahora, cuando los balones azules llegan al borde izquierdo de la pantalla,
					esto son teletransportados hacia el extemo derecho.

* Actividad 5 Juego de Memoria: Para la ultima actividad agregamos un contador que desplegaba en consola la cantidad de taps
				hasta el momento, imprimimos un mensaje de felicitaciones cuando ya no quedan más cuadros
				por desbloquear y por último, centramos los dígitos en los recuadros.  

##  PROYECTO
El proyecto de esta Semana Tec consiste en crear un videojuego utilizando el lenguaje de programación Python y la librería Turtle para la elaboracion
del mismo. Asímismo, utilizamos las herramientas de WSL para hacer nuestros commitments y pushes a nuestro repositorio en GitHub.
Esto fue posible gracias a los conocimientos previos en el área y lo aprendidos durante la semana.

Para elaborar el juego, primero decidimos que juego crear. Elegimos entre todo el equipo en crear un juego parecido al Space Invaders.
Este juego consiste en un shooter 2D en vertical, en el cual la  nave se mueve únicamente  por el eje X y dispara hacia las naves alienígenas. Cuando una de estas se destruye, se le suma un punto al contador. 

Para poder realizar el código, primero investigamos cada parte que se requería para el funcionamiento del juego, como el sistema de disparos, movimiento del personaje y aliens, texto que represente el puntaje y como agregar sonidos al programa.
Investigamos diferentes códigos en internet sobre juegos parecidos al Space Invader y recopilamos las partes que pensamos eran de utilidad.

Posteriormente elaboramos nuestro código con estás partes recopiladas y comenzamos a modificar el código a nuestro gusto para lograr el proyecto que teniamos en mente.
Utilizamos las siguientes librerias: Turtle, Math, Random, Time y Winsound.

Generamos nuestra ventana de aplicacion en la que jugaremos, primero colocamos una imagen de portada con los nombres de los integrantes y seguido de esto iniciamos el juego.
Creamos objetos Turtle para nuestro personaje, enemigos y los proyectiles que dispara nuestra nave. 

Posicionamos nuestra nave y los enemigos en la ventana de manera aleatoria, los enemigos se mueven de un extremo a otros de la ventana, cuando estos llegan a un extremo comienzan a avanzar en dirección contraría y se acercan un poco más a la altura del jugador.
Para mover nuestro personaje usamos las letras "a" para ir a la izquierda y "d" para ir a la derecha, disparamos el proyectil con la tecla "espacio" y la "g" para una bala especial.

Cuando se escapan 5 aliens o bien, el jugador colisiona con uno de estos, el juego se termina de manera automática y se despliega el menu de "Fin de juego" al igual que el puntaje total.

Liga para el video de youtube: https://youtu.be/oc4SNCogvtY
