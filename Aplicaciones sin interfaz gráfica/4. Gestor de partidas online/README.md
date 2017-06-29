
<!--Creado por Jonathan Carrero -->

**Gestor de partidas online**
==============
----------

**Introducción**

Este pequeño proyecto consiste en un gestor de partidas de 2 jugadores que permite a nuevos usuarios registrarse, y a los usuarios ya registrados buscar adversario para iniciar una partida, y jugar en partidas que tenga en curso. En esta modalidad de juego cada usuario se conecta cuando quiere jugar, pudiendo tener simultáneamente varias partidas en curso, hasta un máximo establecido.

Los usuarios se clasifican en categorías y las partidas se abren con adversarios de la misma categoría. Cuando un participando ha ganado suficientes partidas consecutivas asciende de categoría, por otra parte si pierde muchas partidas consecutivas baja de categoría.

Una partida puede terminar bien porque se acaba el juego, o bien porque un jugador decide abandonar. En este último caso, se da como ganador al adversario. Cuando un jugador termina una partida, el gestor avisará al adversario enviándole un aviso, que vera cuando se conecte.

**Descripción**

El menú principal del sistema permite realizar dos opciones (mientras no se elija salir): iniciar sesión, para usuarios ya registrados, o registrarse. En ambos casos se pide un nombre de usuario y contraseña.

- Acceder a mi cuenta: en esta opción se comprueba que el usuario exista en la lista de usuarios del sistema y que la contraseña sea correcta. Si una de estas dos condiciones no se cumple, se muestra un error y el menú principal aparece de nuevo.

- Registrarse: se comprueba si el usuario que se quiere registrar ya existe en el sistema. Si el nuevo usuario ya existe se mostrará un error y se volverá al manú principal.

- La opción "Salir" termina la ejecución de la aplicación.



