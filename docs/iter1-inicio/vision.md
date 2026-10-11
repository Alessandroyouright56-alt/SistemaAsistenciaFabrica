DOCUMENTO DE VISIÓN — VERSIÓN 1.0
Proyecto: Sistema de Control de Asistencia para una Fábrica de Caramelos
Versión: 1.0
Iteración: ITER-1 — Inicio
Estado: Borrador inicial

1. Propósito del proyecto
Desarrollar un sistema digital de control de asistencia para una fábrica de caramelos que permita registrar las entradas y salidas de los trabajadores de manera rápida, confiable y automatizada.

El sistema utilizará un lector de huella dactilar como método principal de identificación y permitirá el uso de DNI y PIN como alternativa. Además, facilitará el control de tardanzas, el cálculo de horas trabajadas y la consulta de registros por parte del administrador.

2. Problema que se busca resolver
Actualmente, la fábrica registra la asistencia de sus trabajadores mediante un cuaderno físico. Cada trabajador debe firmar cuatro veces durante la jornada:
- 7:00 a. m.: Entrada de la mañana.
- 12:30 p. m.: Salida para el almuerzo.
- 2:00 p. m.: Retorno del almuerzo.
- 7:30 p. m.: Salida de la tarde.

Este procedimiento presenta los siguientes problemas:
- Deterioro o pérdida del cuaderno de asistencia.
- Formación de colas durante el registro de entradas y salidas.
- Olvido de firmas y errores en los registros.
- Trabajo administrativo excesivo para revisar las asistencias y calcular las horas trabajadas y las tardanzas.
- Dificultad para consultar los registros históricos de los trabajadores.

Por estos motivos, se necesita un sistema digital que reduzca la dependencia del registro manual y facilite la gestión de la asistencia.

3. Alcance del sistema
3.1. Funcionalidades incluidas
- Registrar a los trabajadores con sus nombres, DNI, PIN de cuatro dígitos, huella dactilar, cargo y área.
- Registrar la asistencia mediante huella dactilar o mediante DNI y PIN.
- Registrar automáticamente la fecha y hora de cada marcación.
- Identificar el bloque horario correspondiente a cada marcación.
- Detectar las tardanzas de acuerdo con el horario y la tolerancia configurada.
- Calcular las horas trabajadas y descontar el tiempo del almuerzo.
- Permitir al administrador consultar las asistencias del día y buscar registros por trabajador o rango de fechas.
- Resaltar las tardanzas en la consulta de asistencias.
- Exportar los registros de asistencia a Excel.
- Permitir la configuración de los horarios y los minutos de tolerancia.

3.2. Funcionalidades no incluidas
Para la primera versión del proyecto:
- No se desarrollará una aplicación móvil para registrar asistencia de manera remota.
  
Esta exclusión corresponde a la priorización de requisitos realizada mediante la técnica MoSCoW.

4. Interesados del sistema
| Interesado      |  Necesidad |
| Trabajadores| 	| Registrar sus entradas y salidas de forma rápida y sencilla |
| Administrador| 	| Gestionar trabajadores, consultar asistencias, controlar tardanzas, configurar horarios y exportar registros |
  
5. Objetivos del proyecto
1.Digitalizar el registro de asistencia: permitir que los trabajadores registren sus marcaciones mediante huella dactilar o DNI y PIN.
2.Automatizar el control horario: registrar la fecha y hora de cada marcación e identificar el bloque correspondiente.
3.Controlar las tardanzas: detectar las marcaciones tardías según el horario y la tolerancia establecidos.
4.Facilitar el cálculo de horas trabajadas: calcular las horas correspondientes a la jornada y descontar el tiempo del almuerzo.
5.Mejorar la consulta de información: permitir que el administrador consulte registros por fecha y trabajador.
6.Facilitar la generación de reportes: permitir la exportación de los registros a Excel.

6. Requisitos de alto nivel
Para mantener la nomenclatura solicitada en la guía del Tema 6, se utilizarán identificadores con el formato REQ-###.
| Código	| Requisito | 
| REQ-001	| El sistema permitirá registrar la asistencia de los trabajadores.|
| REQ-002	  | El sistema identificará a los trabajadores mediante huella dactilar o mediante DNI y PIN.|
| REQ-003  	| El sistema registrará automáticamente la fecha y hora de cada marcación.|
| REQ-004	  | El sistema detectará las tardanzas de acuerdo con el horario y la tolerancia configurados.|
| REQ-005	  | El administrador podrá consultar los registros de asistencia por fecha y trabajador.|
| REQ-006	  | El administrador podrá configurar los horarios y los minutos de tolerancia.|
| REQ-007	  | El sistema permitirá exportar los registros de asistencia a Excel.|

7. Restricciones del proyecto
- Se utilizará una tablet o computadora ubicada en la entrada principal de la fábrica.
- El dispositivo contará con un lector de huella dactilar conectado por USB.
- La huella dactilar será el método principal de identificación.
- El DNI y el PIN de cuatro dígitos servirán como método alternativo de identificación.
- El sistema deberá considerar los cuatro bloques horarios de la jornada: entrada de la mañana, salida al almuerzo, retorno del almuerzo y salida de la tarde.
- El control de tardanzas dependerá de los horarios y minutos de tolerancia configurados.

8. Resultado esperado
Se espera disponer de un sistema de control de asistencia que permita registrar las marcaciones de los trabajadores digitalmente, identificar tardanzas, calcular las horas trabajadas y consultar o exportar los registros sin depender exclusivamente del cuaderno físico.

Este documento constituye la visión inicial del proyecto y servirá como referencia para organizar las iteraciones, elaborar los modelos UML y comprobar la coherencia entre los requisitos y los demás artefactos del sistema.
