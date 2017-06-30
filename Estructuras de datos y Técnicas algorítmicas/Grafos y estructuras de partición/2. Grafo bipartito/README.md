# Grafo bipartito

Un grafo no dirigido es bipartito si sus vertices pueden repartirse en dos conjuntos disjuntos de tal forma que todas las aristas tengan un extremo en cada uno de esos conjuntos. Dicho de otra forma, un grafo es bipartito si sus vertices pueden colorearse utilizando dos colores de tal forma que no exista ninguna arista que conecte dos vertices del mismo color.

**Entrada**

La entrada esta compuesta por diversos casos de prueba. Para cada caso, la primera lınea contiene el numero de vertices del grafo, V (entre 1 y 10.000), y la segunda el numero de aristas, A (entre 0 y 100.000). A continuacion aparecen A lıneas, cada una con dos enteros que representan los extremos de cada una de las aristas (valores entre 0 y V 1). Los grafos no contienen aristas de un vertice a sı mismo ni mas de una arista que conecte un mismo par de vertices.

**Salida**

Para cada caso de prueba se escribira en una lınea independiente la palabra SI si el grafo es bipartito y NO en caso contrario.

**Entrada de ejemplo**

    7
    9
    0 2
    0 4
    1 6
    1 3
    2 6
    2 5
    4 6
    4 5
    4 3
    6
    8
    0 2
    0 3
    2 3
    2 4
    4 3
    3 1
    3 5
    1 5

**Salida de ejemplo**

    SI
    NO

**Autor del problema:** Alberto Verdejo.
