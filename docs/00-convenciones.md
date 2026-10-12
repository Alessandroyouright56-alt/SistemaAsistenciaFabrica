# Convenciones del proyecto

## 1. Nombre del proyecto

Sistema de Control de Asistencia Dasyar para una Fábrica de Caramelos.

## 2. Convenciones de identificadores

| Elemento | Formato | Ejemplo |
|---|---|---|
| Requisito de alto nivel | REQ-### | REQ-001 |
| Requisito funcional | RF## | RF01 |
| Requisito no funcional | RNF## | RNF01 |
| Caso de uso | CU-### | CU-002 |
| Riesgo | RSK-### | RSK-005 |
| Iteración | ITER-# | ITER-1 |
| Excepción | E# | E1 |
| Clase UML | CLS-Nombre | CLS-Trabajador |

Los identificadores deben ser únicos dentro de su categoría. Si un elemento cambia, se deben revisar los documentos relacionados para mantener la trazabilidad.

## 3. Convenciones para archivos y carpetas

- Utilizar nombres descriptivos y minúsculas en los nombres de archivos Markdown.
- Separar las palabras de los nombres de archivo con guiones.
- Guardar los documentos de la primera iteración en `docs/iter1-inicio/`.
- Guardar los diagramas de la primera iteración en `modelos/iter1/`.
- Conservar el archivo fuente `.drawio` y su exportación `.png`.
- Mantener la misma denominación para los actores y los casos de uso en todos los artefactos.

## 4. Convenciones de documentación

- Los documentos deben incluir un título y un objetivo cuando corresponda.
- Los requisitos deben redactarse de forma clara y verificable.
- Los diagramas deben utilizar nombres coherentes con los requisitos y casos de uso.
- Los riesgos deben incluir probabilidad, impacto, mitigación y responsable.
- Los cambios importantes deben revisarse en los documentos relacionados.

## 5. Convención de commits

Se recomienda utilizar mensajes breves que indiquen la acción realizada.

Ejemplos:

- `docs: agregar documento de vision`
- `docs: organizar roadmap de iteracion`
- `docs: agregar matriz de riesgos`
- `docs: actualizar diagrama de actividades`

## 6. Convención de versiones

Las versiones de las iteraciones se identificarán con el formato `vX.Y-iterN`.

Ejemplo de la primera entrega:

`v1.0-iter1`

La etiqueta de versión se creará cuando los artefactos de la iteración estén revisados y listos para su entrega.

## 7. Responsabilidad del equipo

Todos los integrantes deben respetar estas convenciones y comunicar los cambios que afecten a requisitos, diagramas o documentos compartidos.
