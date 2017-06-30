# Planificación de conferencias

La Universidad Imponente tiene que planificar un evento cultural que consiste en una serie de conferencias. Para cada conferencia se conoce la hora de comienzo y la de finalizacion fijadas por los ponentes. Se ha pedido al Departamento de Informatica que planifique las conferencias distribuyendolas entre las distintas salas disponibles, de forma que, claro esta, no haya dos conferencias en una misma sala al mismo tiempo. El objetivo es minimizar el numero de salas utilizadas, para así causar el menor trastorno al resto de las actividades academicas.

**Entrada**

La entrada consta de una serie de casos de prueba. Cada uno comienza con una l ́ınea con el numero N de conferencias (1 <= N <= 250.000). A continuacion aparecen N lıneas, cada una con dos numeros que representan la hora de comienzo y de finalizacion de una de las conferencia (la hora de comienzo siempre es estrictamente menor que la de finalizacion). Estos tiempos son numeros enteros entre 0 y 10^9. La entrada terminara con un caso sin conferencias, que no debe procesarse.

**Salida**

Para cada caso de prueba se escribira una lınea con el mınimo numero de salas necesarias para la planificacion de las conferencias, de forma que no se solapen conferencias dentro de una misma sala. Se puede suponer que la Universidad Imponente siempre contara con suficientes salas disponibles.

**Entrada de ejemplo**

    3
    1 5
    3 10
    6 12
    2
    5 10
    1 5
    3
    1 5
    2 6
    3 7
    0

**Salida de ejemplo**

    2
    1
    3

**Autor del problema:** Alberto Verdejo.
