# Lista de verificación de coherencia

## 1. Objetivo

Comprobar que la Visión, los requisitos, los casos de uso, los diagramas y los demás artefactos del Sistema de Asistencia Dasyar sean coherentes entre sí.

## 2. Lista de verificación

### A. Coherencia con la Visión

- [X]  El propósito del sistema coincide con la automatización del registro de asistencia de la fábrica.
- [ ] El alcance contempla la identificación mediante huella dactilar y DNI + PIN.
- [ ] Los cuatro bloques horarios están contemplados: entrada de mañana, salida al almuerzo, retorno del almuerzo y salida de la tarde.
- [ ] La detección de tardanzas utiliza horarios y tolerancias configurables.
- [ ] Las funciones representadas en los diagramas están dentro del alcance aprobado.
- [ ] No se incorporan funciones excluidas de la Visión, como una aplicación móvil para marcar asistencia remotamente.

### B. Coherencia de requisitos

- [ ] Los requisitos funcionales mantienen identificadores únicos y consistentes.
- [ ] Los requisitos funcionales principales están representados en casos de uso o artefactos relacionados.
- [ ] Los requisitos no funcionales tienen una forma prevista de verificación.
- [ ] La consulta y exportación de registros a Excel aparecen de manera coherente en los documentos del proyecto.
- [ ] Las reglas de tardanza y tolerancia están descritas sin contradicciones.

### C. Coherencia de los casos de uso y diagramas

- [ ] Los actores mantienen los mismos nombres en todos los diagramas.
- [ ] Cada caso de uso tiene un identificador único, como `CU-002`.
- [ ] El caso de uso «Registrar asistencia» contempla la identificación del trabajador.
- [ ] El flujo alternativo de DNI + PIN está representado.
- [ ] Los errores de autenticación están contemplados.
- [ ] La marcación duplicada se controla antes de guardar otro registro.
- [ ] Los estados `OK` y `TARDANZA` se asignan según las reglas establecidas.
- [ ] Las excepciones del diagrama también están descritas en el caso de uso correspondiente.
- [ ] El flujo de guardado contempla tanto el éxito como el error.
- [ ] Las relaciones entre casos de uso, cuando existen, utilizan correctamente `include` y `extend`.

### D. Convenciones y trazabilidad

- [ ] Los requisitos utilizan la convención de identificadores acordada.
- [ ] Los casos de uso utilizan el formato `CU-###`.
- [ ] Los riesgos utilizan el formato `RSK-###`.
- [ ] Los términos de los documentos coinciden con el glosario.
- [ ] Los requisitos de la Visión pueden rastrearse hasta los artefactos que los desarrollan.
- [ ] Los cambios realizados en un documento se revisan también en los artefactos relacionados.

## 3. Registro de inconsistencias

| N.º | Inconsistencia encontrada | Documento o diagrama afectado | Corrección realizada | Responsable |
|---|---|---|---|---|
| 1 | Pendiente de revisión | Por identificar | Por definir | Por asignar |
| 2 | Pendiente de revisión | Por identificar | Por definir | Por asignar |

## 4. Resultado de la revisión

- **Estado:** Pendiente de revisión del equipo.
- **Inconsistencias detectadas:** Completar después de revisar los artefactos.
- **Correcciones pendientes:** Completar después de la revisión.
- **Fecha de revisión:** Por registrar.
- **Responsables de revisión:** Por registrar.
