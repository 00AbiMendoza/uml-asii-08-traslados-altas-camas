# Declaración de uso de inteligencia artificial

## 1. Identificación del trabajo

- **Estudiante:** Esaú Abimael de la Cruz Mendoza
- **Asignación:** Diagramas UML por módulo
- **Módulo:** ASII-08 — Traslados, altas y liberación de camas
- **Proceso modelado:** Traslado o alta del paciente con liberación consistente de cama

## 2. Herramienta utilizada

Durante el desarrollo del trabajo se utilizó **ChatGPT, herramienta de inteligencia artificial de OpenAI**, como apoyo técnico y metodológico.

También se utilizaron las siguientes herramientas convencionales:

- PlantUML para elaborar y generar los diagramas UML.
- Java para ejecutar PlantUML.
- PowerShell para crear archivos y ejecutar comandos.
- Git y GitHub para el control de versiones y la publicación del repositorio.

## 3. Propósito del uso de inteligencia artificial

La inteligencia artificial se utilizó para apoyar las siguientes actividades:

1. Interpretar y organizar los requisitos de la asignación.
2. Estructurar los requisitos funcionales, reglas de negocio y excepciones del módulo.
3. Proponer código PlantUML para los diagramas de casos de uso, actividad y secuencia.
4. Revisar la coherencia entre los tres diagramas.
5. Construir una matriz de trazabilidad entre requisitos y elementos UML.
6. Identificar la necesidad de representar el fallo de notificaciones sin revertir la operación principal.
7. Proponer comandos de PowerShell y Git para crear, validar y versionar los archivos.
8. Apoyar la redacción técnica de la documentación.

## 4. Consultas relevantes realizadas

Entre las consultas e instrucciones utilizadas durante el trabajo se encuentran las siguientes:

- Solicitud de acompañamiento paso a paso para desarrollar la tarea individual del módulo ASII-08.
- Solicitud de definición de requisitos funcionales, reglas de negocio y excepciones.
- Solicitud de elaboración de un diagrama de casos de uso editable en PlantUML.
- Solicitud de elaboración de un diagrama de actividad con decisiones, excepciones y resultados.
- Solicitud de elaboración de un diagrama de secuencia con participantes, mensajes, validaciones y respuestas.
- Solicitud de revisión de legibilidad, coherencia y cobertura de los diagramas.
- Solicitud de construcción de una matriz requisito–diagrama–elemento.
- Solicitud de comandos de Git para registrar y publicar los cambios.

Estas consultas fueron realizadas de manera progresiva. Cada resultado fue revisado antes de continuar con el siguiente paso.

## 5. Contenido aceptado

Se aceptaron como apoyo los siguientes elementos propuestos por la inteligencia artificial:

- La estructura general del repositorio.
- La organización de requisitos, reglas y excepciones.
- La sintaxis base de los archivos PlantUML.
- La estructura de la matriz de trazabilidad.
- La propuesta para manejar fallos de notificación mediante auditoría y reintento.
- La secuencia de comandos para validar, registrar y publicar los archivos.

## 6. Contenido revisado o modificado

Los resultados no fueron utilizados de forma automática. Durante el proceso se realizaron revisiones y ajustes humanos, entre ellos:

- Selección y confirmación del proceso específico del módulo ASII-08.
- Revisión de actores, participantes, requisitos y excepciones.
- Uso exclusivo de identificadores ficticios como `PAC-DEM-001`, `ADM-DEM-001`, `HOSP-DEMO-01`, `CAM-A-101` y `CAM-B-204`.
- Revisión visual de cada diagrama generado.
- Ajuste del tamaño y nivel de detalle del diagrama de secuencia.
- Inclusión explícita del registro del fallo de notificación y su reintento.
- Verificación de que la operación principal no se revierta cuando falla una notificación posterior.
- Revisión de la matriz de trazabilidad hasta obtener cobertura completa.

## 7. Validación humana realizada

La validación final fue responsabilidad del estudiante. Para ello se realizaron las siguientes acciones:

- Lectura de los archivos editables `.puml`.
- Generación de versiones PNG y SVG mediante PlantUML.
- Revisión visual de los diagramas para detectar cortes, superposiciones o inconsistencias.
- Comparación de los diagramas con los requisitos y excepciones definidos.
- Verificación de la cobertura mediante la matriz de trazabilidad.
- Ejecución personal de los comandos en PowerShell.
- Revisión de `git status` antes de cada commit.
- Creación y publicación personal de los commits en GitHub.

La herramienta de inteligencia artificial no tuvo acceso directo al equipo local ni realizó por sí misma los commits o publicaciones. Estas acciones fueron ejecutadas y verificadas por el estudiante.

## 8. Responsabilidad académica

El estudiante declara que comprende los diagramas, las reglas modeladas y las decisiones tomadas. También asume la responsabilidad de explicar, defender y modificar los elementos del trabajo durante la evaluación oral.

No se utilizaron datos clínicos reales ni información identificable de pacientes. Todos los nombres, códigos y situaciones utilizados como ejemplo son ficticios.
---

# Ampliación de declaración de IA — Actividad SOLID / LSP

## 9. Identificación de la nueva actividad

- **Actividad:** Aplicación del principio SOLID Liskov Substitution Principle (LSP)
- **Módulo:** ASII-08 — Traslados, altas y liberación de camas
- **Flujo analizado:** Traslado o alta del paciente con liberación consistente de cama
- **Principio asignado:** Liskov Substitution Principle (LSP)

Esta sección complementa la declaración anterior y corresponde específicamente a la actividad de mejora de diseño mediante un principio SOLID.

## 10. Herramienta y propósito

Se utilizó **ChatGPT, herramienta de inteligencia artificial de OpenAI**, como apoyo para:

1. Analizar las instrucciones de la actividad.
2. Organizar requisitos funcionales y no funcionales.
3. Formular criterios de aceptación verificables.
4. Identificar invariantes comunes entre traslado y alta.
5. Analizar un diseño que incumple LSP.
6. Proponer un rediseño compatible con sustituibilidad.
7. Elaborar fuentes editables PlantUML del diseño antes y después.
8. Proponer comandos de PowerShell, PlantUML y Git.
9. Apoyar la redacción de la documentación técnica y la preparación de evidencia.

## 11. Consultas e instrucciones relevantes

Entre las instrucciones realizadas a la herramienta durante esta actividad se incluyen:

- Acompañamiento paso a paso para desarrollar la asignación individual.
- Revisión de los archivos existentes del repositorio personal.
- Definición de RF, RNF y criterios de aceptación para el flujo asignado.
- Análisis de las diferencias entre traslado interno y alta hospitalaria.
- Identificación de una posible violación de LSP en una jerarquía demasiado específica.
- Diseño de una abstracción común que permita sustituir traslado y alta sin romper las invariantes compartidas.
- Elaboración de diagramas editables de diseño antes y diseño después.
- Generación de comandos para validar y versionar los artefactos.

Las instrucciones fueron aplicadas progresivamente y los resultados fueron revisados antes de continuar.

## 12. Partes aceptadas

Se aceptaron como apoyo:

- La estructura de los documentos de requisitos y diseño.
- La separación entre invariantes comunes y comportamientos específicos.
- La propuesta conceptual de `OperacionDisposicionPaciente`.
- Las implementaciones conceptuales `OperacionTraslado` y `OperacionAlta`.
- La representación PlantUML del diseño antes y después.
- La secuencia de comandos para creación, generación y control de versiones.

## 13. Partes revisadas o modificadas por el estudiante

El estudiante realizó o verificó personalmente:

- La correspondencia del diseño con el módulo ASII-08.
- Las reglas que distinguen traslado de alta.
- Que un traslado conserve activa la admisión.
- Que un alta cierre la admisión.
- Que la cama origen quede en `limpieza` y no pase directamente a `disponible`.
- La generación local de los diagramas mediante PlantUML.
- La revisión de los archivos creados.
- La ejecución de los comandos Git.
- La selección de los cambios que se incorporaron al repositorio.

## 14. Validación humana

La validación humana incluye:

- revisión de los requisitos y criterios de aceptación;
- lectura de los documentos técnicos;
- revisión del código PlantUML;
- generación local de los diagramas PNG;
- comprobación de que PlantUML procesó los archivos sin errores;
- revisión del estado del repositorio antes de registrar cambios;
- verificación de que los artefactos utilizan únicamente datos ficticios;
- comprensión de la diferencia entre el diseño que viola LSP y el diseño corregido.

La inteligencia artificial fue utilizada como herramienta de apoyo. La ejecución, revisión, aceptación de cambios y responsabilidad académica corresponden al estudiante.

## 15. Preparación para defensa

El estudiante se compromete a poder explicar:

- qué establece LSP;
- por qué el diseño inicial presenta un problema de sustituibilidad;
- qué elementos fueron modificados;
- cuáles son las invariantes comunes;
- qué comportamiento pertenece específicamente al traslado;
- qué comportamiento pertenece específicamente al alta;
- por qué el consumidor ya no necesita identificar el subtipo para corregir su comportamiento.

También deberá poder realizar una modificación sencilla sobre los artefactos técnicos durante la defensa si fuera requerida.