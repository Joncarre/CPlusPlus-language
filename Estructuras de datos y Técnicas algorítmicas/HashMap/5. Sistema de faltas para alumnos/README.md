# Sistema de faltas

Cada uno de los profesores de distintas asignaturas de un mismo grupo de alumnos tiene una lista de faltas, es decir, para cada alumno van anotando cuantas veces ha faltado en esa asignatura (0 si no ha faltado nunca). Para gestionar esta información diseñan un tipo abstracto de datos *Faltas* con tres operaciones generadoras:

- anadirAlumno: que añade un alumno en todas las asignaturas con 0 faltas.

- anadirFalta: que incrementa en 1 el número de faltas de un alumno en una asignatura.

- anadirAsignatura: que construye una lista con los mismos alumnos de las demás asignaturas, cada uno de ellos con 0 faltas.

