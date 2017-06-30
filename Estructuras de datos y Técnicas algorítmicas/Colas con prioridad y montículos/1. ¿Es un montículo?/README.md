# ¿Es un montículo?

Un arbol binario es completo cuando todos sus nodos internos tienen dos hijos no vacıos, y todas sus hojas estan al mismo nivel; y es semicompleto si o bien es completo o tiene vacantes una serie deposiciones consecutivas del ultimo nivel empezando por la derecha, de tal manera que al rellenar dichas posiciones con nuevas hojas se obtiene un arbol completo.

Un montıculo de mınimos es un arbol binario semicompleto donde cada elemento es menor o igual que sus hijos (si los tiene).

**Entrada**

La entrada comienza con el numero de casos que vienen a continuacion. Cada caso de prueba consiste en una lınea con la descripcion de un arbol binario: primero aparece su raız (un entero no negativo), y a continuacion la descripcion del hijo izquierdo y despues la del hijo derecho. El numero –1 indica el arbol vacıo. Los arboles nunca contendran mas de 20.000 nodos.

**Salida**

Para cada arbol se escribira SI si es un montıculo de mınimos y NO en caso contrario.

**Entrada de ejemplo**

    3
    15 20 34 -1 -1 44 -1 -1 17 40 -1 -1 -1
    15 20 34 -1 -1 44 -1 -1 17 -1 40 -1 -1
    15 41 34 -1 -1 20 -1 -1 17 40 -1 -1 -1

**Salida de ejemplo**

    SI
    NO
    NO

**Autor del problema:** Alberto Verdejo.
