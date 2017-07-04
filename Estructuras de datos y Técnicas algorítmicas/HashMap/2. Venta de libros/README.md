# Venta de libros

Se desea implementar una aplicación para gestionar un sistema de venta de libros por Internet. La implementación hará uso del tipo *Libro* que representa con un string. Las operaciones permitidas son las siguientes:

- nuevoLibro(x, n): añade n ejemplares de un libro (x) al sistema. Si n toma el valor 0 significa que el libro está en el sistema.
- comprar(x): un usuario compra un libro (x). Se comprueba que existe el libro y hay ejemplares.
- estaLibro(x): indica si un libro (x) se ha añadido al sistema.
- elimLibro(x): elimina el libro (x) del sistema.
- numEjemplares(x): devuelve el número de ejemplares de un libro (x) que hay disponibles en el sistema.

**Entrada de ejemplo**

    5
    nuevoLibro 20 Heidi
    nuevoLibro 30 Caperucita roja
    comprar Heidi
    numEjemplares Caperucita roja
    7
    nuevoLibro 1 La vuelta al mundo en 80 dias
    comprar La vuelta al mundo en 80 dias
    estaLibro La vuelta al mundo en 80 dias
    nuevoLibro 5 Viaje al centro de la tierra
    comprar Viaje al centro de la tierra
    comprar Viaje al centro de la tierra

**Salida de ejemplo**
