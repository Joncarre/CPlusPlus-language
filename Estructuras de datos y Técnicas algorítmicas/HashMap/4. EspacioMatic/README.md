# EspacioMatic

Eres un prestigioso diseñador de videojuegos, y estás trabajando ahora en uno llamado EspacioMatic , en el que habrá naves espaciales con distintos módulos (motores, cabinas, escudos, láseres, etcétera). Necesitarás implementar, como poco, las siguientes operaciones:

- *EspacioMatic*: inicializa el sistema de juego.

- *equipaNave*: dado el identificador de una nave, un nombre de módulo (una cadena como "motor", "cabina", "láser", etcétera) y un nivel de funcionalidad (un entero >= 1 ), añade el módulo correspondiente a esa nave con el nivel indicado. Si esa nave ya tenía ese módulo, se suma el nuevo nivel al anterior (esto permite reparar módulos de naves). No devuelve nada.

- *estropeaNave*: dado el identificador de una nave, y un nombre de módulo, resta 1 al nivel de > 0 ). Devuelve true si el módulo existía y tenía un nivel positivo antes de hacer la resta, ó false si ha sido imposible restar ese módulo en esa nave (asumiendo que tuviese un nivel ya que el módulo no existía o estaba ya a 0.

- *navesDefectuosas*: devuelve una lista de identificadores de naves que tienen uno o más módulos completamente estropeados (con un nivel de 0).

- *modulosNave*: dado el identificador de una nave, devuelve una lista con los nombres de los módulos que tiene equipados (tengan el nivel que tengan), ordenada alfabéticamente.
