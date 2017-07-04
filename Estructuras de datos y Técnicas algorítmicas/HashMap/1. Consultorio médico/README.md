# Consultorio médico

Se desea implementar un TAD (Tipo de Dato Abstracto) que simule el comportamiento de un consultorio método simplificado. La especificación hará uso de los tipos *Medio* y *Paciente* que se representan con un string, y *Fecha* que es una clase con tres datos: dia, hora y minuto. Las operaciones del consultorio son las siguientes:

- nuevoMedico(m): da de alta un nuevo médico. Si el nuevo médico ya existía, no se notifica.
- pideConsulta(p, m, f): un paciente (p) pide consulta a un médico (m) para una fecha (f). Se comprobará que existe el paciente y el médico y que el médico tiene disponible la fecha para atender al paciente.
- siguientePaciente(m): el médico (m) consulta al paciente al que le toque en ese momento, que será el que tenga la fehca menor.
- atiendePaciente(m): elimina el siguiente paciente de un médico (m).
- listaPacientes(m, f): devuelve una lista de pacientes de un cierto médico (m) que tienen cita el día (f).

**Ejemplo de entrada**

    12
    nuevoMedico Hernandez
    nuevoMedico Alvarez
    pideConsulta Ana Alvarez 16 12 30
    pideConsulta Antonio Alvarez 16 12 10
    pideConsulta Alvaro Alvarez 17 10 00
    pideConsulta Alba Alvarez 17 10 15
    pideConsulta Anacleto Alvarez 17 10 55
    listaPacientes Alvarez 16
    siguientePaciente Alvarez
    atiendeConsulta Alvarez
    listaPacientes Alvarez 16
    listaPacientes Alvarez 17
    6
    nuevoMedico Hernandez
    pideConsulta Alvarez Ana 16 12 30
    pideConsulta Helena Hernandez 17 10 00
    atiendeConsulta Hernandez
    listaPacientes Hernandez 17
    atiendeConsulta Hernandez

**Ejemplo de salida**

    Doctor Alvarez dia 16
    Antonio 12:10
    Ana 12:30
    ---
    Siguiente Paciente doctor Alvarez
    Antonio
    ---
    Doctor Alvarez dia 16
    Ana 12:30
    ---
    Doctor Alvarez dia 17
    Alvaro 10:00
    Alba 10:15
    Anacleto 10:55
    ---
    ------
    Medico no existente
    ---
    Doctor Hernandez dia 17

    ---
    No hay pacientes
    ---
    ------
