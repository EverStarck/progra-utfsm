Reglamento de evaluaciones
==========================

*Este problema apareció en el certamen 1 del segundo semestre de 2011 en el campus Vitacura.*

La Universidad Tropical Filomena Santa Marta
ha instaurado un nuevo reglamento de evaluaciones.
Todas las asignaturas deben tener tres certámenes y un examen.
Las notas van entre 0 y 10, con un decimal.

Después de los tres certámenes,
los alumnos con promedio menor que 3 reprueban y
los con promedio mayor o igual que 7 aprueban.
El resto va al examen,
en el que deben sacarse por lo menos un 5 para aprobar.

Además,
para reducir el trabajo de los profesores,
se decidió que los alumnos que se sacan menos de un 2
en los dos primeros certámenes
están automáticamente reprobados.
A su vez,
los que obtienen más de un 9
en los dos primeros certámenes
están automáticamente aprobados.
En ambos casos,
no deben rendir el tercer certamen.

Escriba un programa que pregunte a un estudiante
las notas de las evaluaciones que rindió,
y le diga si está aprobado o reprobado.

.. testcase::

    C1: `1.8`
    C2: `0.9`
    Reprobado

.. testcase::

    C1: `0.5`
    C2: `2.0`
    C3: `2.5`
    Reprobado

.. testcase::

    C1: `1.5`
    C2: `3.5`
    C3: `4.5`
    Examen: `5.1`
    Aprobado

.. testcase::

    C1: `1.5`
    C2: `3.5`
    C3: `4.5`
    Examen: `4.9`
    Reprobado

.. testcase::

    C1: `9.3`
    C2: `9.4`
    Aprobado

