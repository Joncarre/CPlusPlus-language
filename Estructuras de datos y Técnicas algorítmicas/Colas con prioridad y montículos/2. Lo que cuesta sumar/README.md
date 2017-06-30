# Lo que cuesta sumar

Johnny Calculın sabe sumar numeros mentalmente a gran velocidad, pero el esfuerzo que le supone realizar una suma depende del valor de los sumandos. En concreto, sumar a mas b le supone un esfuerzo igual a a + b (independientemente
de los valores concretos de a y b). Sencillo.

Cuando tiene que sumar mas de dos numeros la cosa se complica, ya que el orden en que va realizando las sumas afectan al esfuerzo total empleado. Por ejemplo, si tiene que sumar 1, 2 y 3, puede sumar 1 + 2 con un esfuerzo igual a 3, y despues sumar 3 + 3 con un esfuerzo igual a 6, lo que supone un esfuerzo total igual a 9. En cambio, si suma primero 2 + 3 con un esfuerzo igual a 5 y despu ́es 5 + 1 con un esfuerzo igual a 6, el esfuerzo total asciende a 11. Obviamente el resultado de la suma es siempre 6, por las propiedades conmutativa y asociativa de la suma.

Johnny se esta preparando para un concurso de sumas y quiere averiguar como deberıa ir sumando los numeros para necesitar el mınimo esfuerzo. ¿Puedes ayudarle?

**Entrada**

La entrada esta compuesta por diversos casos de prueba, ocupando cada uno de ellos dos lıneas: la primera lınea contiene un entero N (entre 1 y 100.000) que representa el numero de sumandos, y la segunda contiene esos N sumandos, numeros enteros entre 1 y 1.000.000. La entrada termina con un caso donde N es 0 que no debe procesarse.

**Salida**

Para cada caso de prueba se debe escribir una lınea con el esfuerzo mınimo necesario para sumar los numeros de la entrada.

**Entrada de ejemplo**

    3
    1 2 3
    4
    3 1 4 2
    4
    3 4 5 6
    0

**Salida de ejemplo**

    9
    19
    36

**Autor del problema:** Alberto Verdejo.
