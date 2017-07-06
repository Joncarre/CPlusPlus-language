# Sistema de faltas

Cada uno de los profesores de distintas asignaturas de un mismo grupo de alumnos tiene una lista de faltas, es decir, para cada alumno van anotando cuantas veces ha faltado en esa asignatura (0 si no ha faltado nunca). Para gestionar esta información diseñan un tipo abstracto de datos *Faltas* con tres operaciones generadoras:

- *anadirAlumno*: que añade un alumno en todas las asignaturas con 0 faltas.

- *anadirFalta*: que incrementa en 1 el número de faltas de un alumno en una asignatura.

- *anadirAsignatura*: que construye una lista con los mismos alumnos de las demás asignaturas, cada uno de ellos con 0 faltas.

- *noFaltas*: que por orden alfabético (el dado sobre IdAlumno) devuelve una lista con todos los alumnos que no han faltado a ninguna clase en ninguna de las asignaturas.

- *totalFaltas*: que dado un alumno, devuelve el número de faltas que acumula entre todas las asignaturas.

- *maxFaltas*: que devuelve la asignatura donde mayor número de faltas hay entre todos los alumnos; si hay varias con el máximo número de faltas devuelve una cualquiera.

**Elementos a tener en cuenta**

A la hora de implementar este TAD han decidido que la lista de faltas de una asignatura viene representada por un diccionario con clave IdAlumno y valor asociado el número de faltas del alumno en esa asignatura; y que todas las listas de faltas se hallan almacenadas en un diccionario con clave IdAsignatura (identificador de la asignatura) y valor asociado la lista de faltas de esa asignatura. El invariante de la representación incluye el hecho de que las listas de todas las asignaturas contienen exactamente los mismos alumnos
