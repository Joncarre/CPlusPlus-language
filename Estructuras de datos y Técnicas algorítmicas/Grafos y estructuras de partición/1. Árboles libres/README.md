# Árboles libres

Se dice que un grafo no dirigido es un arbol libre si es acıclico y conexo (o dicho de otra manera, todo par de vertices esta conectado por exactamente un camino).

**Entrada**

La entrada esta compuesta por diversos casos de prueba. Para cada caso, la primera lınea contiene
el numero de vertices del grafo, V (entre 1 y 10.000), y la segunda el numero de aristas, A (entre 0
y 100.000). A continuacion aparecen A lıneas, cada una con dos enteros que representan los extremos
de cada una de las aristas (valores entre 0 y V 1). Los grafos no contienen aristas de un vertice a sı
mismo ni mas de una arista que conecte un mismo par de vertices.

**Salida**

Para cada caso de prueba se escribira SI si el grafo es arbol libre y NO en caso contrario.

**Entrada de ejemplo**

    6
    5
    0 5
    0 2
    2 1
    2 3
    4 3
    6
    5
    0 1
    1 2
    2 3
    3 0
    4 5

**Salida de ejemplo**

    SI
    NO

**Autor del problema:** Alberto Verdejo.
