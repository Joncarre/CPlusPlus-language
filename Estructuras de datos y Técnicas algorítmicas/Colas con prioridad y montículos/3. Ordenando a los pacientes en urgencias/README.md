# Ordenando a los pacientes en urgencias

En el Hospital ACR (Aquı Curamos Rapido) se han puesto a mejorar las Urgencias para que los enfermos que llegan con dolencias mas graves sean atendidos antes que los demas. Para eso, han comprado una UCM (Unidad de Catalogacion Medica) que es capaz de valorar instantaneamente el estado de un paciente con un numero entero entre 0 y 1.000.000, donde 0 indica que su dolencia es menor (quiza incluso inexistente y sea un mero hipocondrıaco) y 1.000.000 indica que el enfermo esta casi caminando hacia la luz.

Por desgracia, la afluencia de enfermos es tal que incluso ası es muy complicado saber rapidamente quien deberıa ser el proximo en ser atendido. No hacen mas que entrar pacientes nuevos a la vez que los mas graves son atendidos, y no es facil mantenerlos ordenados. Cuando un medico queda libre, debe ser atendido el enfermo a la espera con una valoracion mas grave. Si hay dos pacientes evaluados con la misma gravedad, debera ser atendido el que mas tiempo lleve esperando.

Para ayudar en la tarea de decidir quien es el proximo, desde ACR se ha hecho un llamamiento para buscar ayuda entre los mejores programadores. ¿Eres tu uno de ellos?

**Entrada**

La entrada esta formada por diversos casos de prueba. Cada caso comienza con una lınea indicando el numero n de eventos que ocurriran (como mucho 200.000), y a continuacion aparecen n lıneas cada
una con un evento. Un evento puede ser la llegada de un paciente nuevo, o la atencion por parte de un medico que ha quedado libre del paciente mas urgente. Los ingresos de pacientes nuevos se indican de la forma I nombre gravedad, donde nombre es una cadena de como mucho 20 caracteres (sin espacios) y gravedad es un numero entre 0 y 1.000.000 con su estado (0 leve, 1.000.000 muy grave). Los eventos en los que se atiende al siguiente paciente se indican con el caracter A. Se garantiza que no habra nunca eventos de tipo A si no quedan pacientes esperando. La entrada termina cuando el numero de eventos es 0.

**Salida**

Para cada evento de tipo A de cada caso de prueba se escribira el nombre del paciente que es atendido en ese momento. Se atiende primero al paciente mas grave y, en caso de igualdad entre dos o mas
pacientes, se elegira entre ellos al que mas tiempo lleve esperando. Al finalizar el tratamiento de cada caso se escribira una lınea mas con cuatro guiones (----).

**Entrada de ejemplo**

    9
    I Alberto 4000
    I Pepe 3000
    A
    I Rosa 2000
    I Laura 5000
    A
    I Sara 3000
    A
    A
    0

**Salida de ejemplo**

    Alberto
    Laura
    Pepe
    Sara
    ----

**Autor del problema:** Alberto Verdejo.
