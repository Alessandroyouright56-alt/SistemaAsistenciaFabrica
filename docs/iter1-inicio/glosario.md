# Glosario del Sistema de Asistencia Dasyar

## 1. Objetivo

Establecer términos oficiales para que todos los integrantes del equipo utilicen el mismo vocabulario en los documentos, requisitos y diagramas del Sistema de Asistencia Dasyar para la fábrica de caramelos.

## 2. Términos oficiales

| Término oficial | Significado | No utilizar |
|---|---|---|
| Sistema de Asistencia Dasyar | Sistema informático que registra y permite consultar la asistencia de los trabajadores. | Sistema de control, aplicación de marcación, sistema de reloj, como nombres intercambiables del proyecto. |
| Trabajador | Persona que registra su asistencia en la fábrica. | Usuario, empleado o personal cuando se quiera identificar específicamente al actor del sistema. |
| Administrador | Persona autorizada para gestionar trabajadores, consultar asistencias y configurar horarios. | Jefe, operador o encargado como nombres alternativos del actor, salvo que se definan formalmente. |
| Marcación | Registro de asistencia asociado a un trabajador, fecha, hora, bloque horario y estado. | Firma, fichaje o marca cuando se refiera al registro informático. |
| Huella dactilar | Método principal para identificar al trabajador mediante el lector conectado al dispositivo. | Huella, dedo o biometría como términos ambiguos en los requisitos formales. |
| DNI + PIN | Método alternativo de identificación mediante el documento de identidad y un PIN secreto. | Clave, contraseña o código cuando no se esté hablando específicamente del PIN. |
| Bloque horario | Uno de los momentos establecidos para registrar la asistencia durante la jornada. | Turno cuando se quiera identificar una marcación concreta. |
| Tardanza | Estado asignado cuando una marcación incumple la regla de puntualidad definida para el bloque horario. | Retraso o demora como etiquetas alternativas del estado. |
| Tolerancia | Minutos permitidos según la configuración del horario antes de considerar una marcación como tardanza. | Margen o tiempo extra en los documentos formales. |
| Registro de asistencia | Información almacenada de una marcación realizada por un trabajador. | Fila, dato o apunte como denominación oficial. |
| Caso de uso (CU) | Descripción de una interacción entre un actor y el sistema para alcanzar un objetivo. | Función cuando se haga referencia a un caso de uso identificado. |
| Requisito funcional (RF) | Función o comportamiento que el sistema debe proporcionar. | Característica cuando se cite un requisito identificado. |
| Requisito no funcional (RNF) | Condición de calidad o restricción que debe cumplir el sistema. | Función secundaria o requisito opcional. |
| Excepción | Situación alternativa o de error que interrumpe o modifica el flujo normal. | Error cuando se trate de una situación alternativa que no necesariamente sea un fallo técnico. |

## 3. Convenciones de identificación

- `REQ-###`: identificador de requisito de alto nivel.
- `RF##`: requisito funcional.
- `RNF##`: requisito no funcional.
- `CU-###`: identificador de caso de uso.
- `RSK-###`: identificador de riesgo.
- `ITER-#`: identificador de iteración.
- `E#`: identificador de excepción en los diagramas, cuando corresponda.

## 4. Reglas de uso

1. Utilizar los mismos nombres para los actores en todos los diagramas.
2. Mantener el nombre oficial del sistema en los documentos del proyecto.
3. No cambiar los identificadores de requisitos, casos de uso o riesgos sin actualizar los documentos relacionados.
4. Utilizar los términos definidos en este glosario en la Visión, los requisitos y los diagramas.
5. Si el equipo necesita incorporar un término nuevo, debe acordar su significado antes de utilizarlo.
