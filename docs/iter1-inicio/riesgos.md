# Análisis de riesgos por fase de RUP

## 1. Objetivo

Identificar los riesgos que podrían afectar al desarrollo del Sistema de Asistencia Dasyar para la fábrica de caramelos, evaluar su probabilidad e impacto y establecer medidas preventivas o correctivas.

## 2. Escala de evaluación

**Probabilidad**
- Baja: es poco probable que ocurra.
- Media: podría ocurrir durante el proyecto.
- Alta: existe una posibilidad importante de que ocurra.

**Impacto**
- Bajo: ocasiona una dificultad menor.
- Medio: requiere correcciones o genera retrasos moderados.
- Alto: puede impedir una función importante, comprometer registros o retrasar la entrega.

## 3. Matriz de riesgos

| ID | Fase RUP | Riesgo | Probabilidad | Impacto | Mitigación | Responsable propuesto |
|---|---|---|---|---|---|---|
| RSK-001 | Inicio | No identificar correctamente las necesidades de los trabajadores y administradores. | Media | Alto | Entrevistar al administrador, observar el proceso manual y validar los requisitos con los interesados. | Analista de requisitos |
| RSK-002 | Inicio | Definir un alcance demasiado amplio para el tiempo disponible. | Media | Alto | Priorizar el registro de asistencia, la detección de tardanzas y la consulta de registros. | Líder del proyecto |
| RSK-003 | Elaboración | Diseñar incorrectamente los flujos de autenticación por huella y DNI + PIN. | Media | Alto | Revisar los casos de uso, los flujos alternativos y las excepciones antes de implementar. | Diseñador del sistema |
| RSK-004 | Elaboración | Configurar incorrectamente los cuatro bloques horarios o la tolerancia de tardanza. | Media | Alto | Documentar las reglas horarias, validar ejemplos y revisar los límites con el administrador. | Analista de requisitos |
| RSK-005 | Construcción | El lector de huellas no funciona correctamente o presenta incompatibilidades. | Media | Alto | Probar el dispositivo con anticipación y verificar el método alternativo DNI + PIN. | Desarrollador |
| RSK-006 | Construcción | La base de datos pierde registros o no guarda una marcación. | Baja | Alto | Implementar validaciones, comprobar el resultado del guardado, realizar copias de seguridad y probar la recuperación. | Desarrollador de base de datos |
| RSK-007 | Construcción | El registro tarda demasiado y genera colas en la entrada. | Media | Alto | Medir el tiempo de registro, probar con varios trabajadores y optimizar las operaciones necesarias. | Equipo de desarrollo |
| RSK-008 | Construcción | El sistema registra duplicados o calcula mal las tardanzas. | Media | Alto | Probar marcaciones repetidas, cambios de bloque horario, tolerancias y casos límite. | Equipo de pruebas |
| RSK-009 | Transición | Los trabajadores no comprenden cómo registrar su asistencia. | Media | Medio | Preparar instrucciones breves, realizar una demostración y explicar el método alternativo. | Responsable de capacitación |
| RSK-010 | Transición | El sistema no está listo para la entrega o faltan evidencias y documentación. | Media | Medio | Ejecutar una lista de comprobación, verificar los resultados de pruebas y revisar los entregables. | Líder del proyecto |

## 4. Plan de seguimiento

1. Revisar los riesgos en las reuniones del equipo.
2. Actualizar la probabilidad y el impacto si cambia la situación del proyecto.
3. Asignar cada riesgo a una persona responsable.
4. Registrar en Trello las tareas de mitigación pendientes.
5. Verificar que las acciones preventivas se completen durante la iteración correspondiente.

## 5. Riesgos prioritarios

Se recomienda prestar especial atención a:

- **RSK-003:** autenticación correcta del trabajador.
- **RSK-004:** configuración de horarios y tardanzas.
- **RSK-005:** disponibilidad del lector de huellas.
- **RSK-006:** integridad y conservación de las marcaciones.
- **RSK-008:** prevención de duplicados y errores de cálculo.

Estos riesgos pueden afectar directamente la confiabilidad del sistema de asistencia.
