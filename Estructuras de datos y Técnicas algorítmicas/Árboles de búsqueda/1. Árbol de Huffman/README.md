# Árbol de Huffman

Es posible reducir significativamente el número de bits requeridos para representar un texto si, en lugar de emplear un código de longitud fija como ASCII, se emplea un codigo de longitud variable. En este caso, el número de bits requeridos puede variar de carácter en carácter. El objetivo es codificar los caracteres que aparecen más frecuentemente usando cadenas de bits más cortas. Sin embargo, cuando el código es de longitud variable se necesita algún método para determinar los bits de inicio y de fin de un código.

La técnica de los códigos de Huffman nos permite construir códigos sin prefijos, que además serán óptimos, en el sentido de que se elegirán las menores longitudes de código para aquellos caracteres que aparezcan un mayor número de veces. El método de compresión/descompresión de datos consiste en lo siguiente:

- Calcular las frecuencias de todos los caracteres de un mensaje dado (tablad e frecuencias).
- Construir el "árbol de Huffman" a partir de la tabla de frecuencias.
- Construir una tabla de código de longitud variable utilizando el "árbol de Huffman".
- Una vez obtenidos los código de cada carácter se codifica el mensaje.
- El mensaje codificado se decodifica de forma directa usando el árbol de Huffman.


