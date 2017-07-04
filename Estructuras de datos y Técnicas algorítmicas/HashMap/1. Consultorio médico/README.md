# Consultorio médico

Se desea implementar un TAD (Tipo de Dato Abstracto) que simule el comportamiento de un consultorio método simplificado. La especificación hará uso de los tipos *Medio* y *Paciente* que se representan con un string, y *Fecha* que es una clase con tres datos: dia, hora y minuto. Las operaciones del consultorio son las siguientes:

- nuevoMedico(m): da de alta un nuevo médico. Si el nuevo médico ya existía, no se notifica.
- pideConsulta(p, m, f): un paciente (p) pide consulta a un médico (m) para una fecha (f). Se comprobará que existe el paciente y el médico y que el médico tiene disponible la fecha para atender al paciente.
- siguientePaciente(m): el médico (m) consulta al paciente al que le toque en ese momento, que será el que tenga la fehca menor.
- atiendePaciente(m): elimina el siguiente paciente de un médico (m).
- listaPacientes(m, f): devuelve una lista de pacientes de un cierto médico (m) que tienen cita el día (f).
