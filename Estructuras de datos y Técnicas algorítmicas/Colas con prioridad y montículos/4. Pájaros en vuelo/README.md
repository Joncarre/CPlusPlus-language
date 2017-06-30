# Pájaros en vuelo

Es muy conocido que algunas especies de aves vuelan creando una formacion en V. La razon es simple: de esa forma las aves que van detras aprovechan el rebufo de las que van delante. Esto implica que el pajaro que hace mas esfuerzo es aquel que va primero ocupando el vertice de la V, por lo que es importante elegir bien quien es.

Algunas especies lo que hacen es colocarse en orden de edad de izquierda a derecha, de forma que el pajaro que queda en el centro es el que no es ni demasiado joven ni demasiado viejo. De esta forma evitan que el que abre camino este poco desarrollado o demasiado cansado para tirar del grupo. Cuando a la bandada se van uniendo mas pajaros, ocupan su lugar y, si es necesario, el pajaro que abre el camino cambia.

Por ejemplo, imaginemos que hay una bandada en vuelo con pajaros de edades 10, 20 y 30 meses. En ese caso, el que ocupara el primer lugar es el de 20 meses. Si ahora llegan dos pajaros nuevos, uno de 25 meses y otro de 35, ambos ocuparan su sitio y el primero pasara a ser el de 25 meses. Si posteriormente llega un abuelo de 40 meses con su nieto de 5, ocuparan los extremos y el primer puesto no variara.

Lo que queremos es simular la formacion de una de estas bandadas de pajaros que comienza con un unico ejemplar y a la que se van añadiendo nuevas parejas. Cada vez que se añade una pareja queremos determinar la edad del ave que ocupa la punta de la bandada.

**Entrada**

La entrada estara compuesta por una serie de casos de prueba, cada uno con la informacion de creacion de una bandada de pajaros. Cada caso consta de dos lıneas: la primera contiene la edad del primer pajaro que echa a volar seguido del numero de parejas que se iran uniendo despu ́es (al menos una y hasta 100.000 parejas); en la lınea siguiente aparecen las edades de cada pareja. Se garantiza que las edades de cada uno de los pajaros que entran en la bandada son distintas. Para eso  ́éstas vienen expresadas en segundos, y nunca sera un numero mayor a 100.000.000. La entrada termina con una lınea con dos ceros.

**Salida**

Para cada caso de prueba se escribira una lınea que tendra tantos numeros como parejas se incorporan a la bandada, indicando la edad del pajaro que ocupa la primera posicion tras la incorporacion de cada pareja.

**Entrada de ejemplo**

    30 3
    10 20 35 25 5 40
    0 0

**Salida de ejemplo**

    20 25 25

**Autor del problema:** Alberto Verdejo.
