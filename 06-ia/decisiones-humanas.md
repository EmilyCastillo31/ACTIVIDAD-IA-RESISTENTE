# Registro de Decisiones Humanas frente a la IA

Tabla consolidada **IA propone → equipo verifica → evidencia → decisión final** de todas las fases.

## Fase 1 — Stakeholders

| Propuesta IA | Qué verificamos | Evidencia | Decisión del equipo | Razón |
| :--- | :--- | :--- | :--- | :--- |
| **Incluir Oficina de TI / Soporte** (Poder Alto, Interés Medio-Alto) | Si la duplicidad o los fallos por múltiples canales afectan la carga de un área específica. | El caso reporta múltiples canales y solicitudes duplicadas o perdidas. | **Aceptado (solo visibilidad)** | TI asume la carga técnica si el sistema falla. Solo necesita logs y métricas, no resolver casos académicos. |
| **Incluir Control Interno / Auditoría** (Poder Alto, Interés Medio) | Si entra en el alcance y la prioridad del problema según las restricciones del caso. | El caso se centra en la operación de las solicitudes (ventanilla y coordinación), no en gobernanza. | **Rechazado** | La IA asume un enfoque de gobernanza corporativa. Incluirla desenfoca el alcance. |
| **Incluir Bienestar Estudiantil** como posible resolutor parcial | La ruta real de los trámites excepcionales (ej. aplazamientos por salud). | Conocimiento institucional del equipo: Bienestar emite un concepto y el Coordinador decide. | **Aceptado con modificación** | Bienestar solo necesita visibilidad; no resuelve el trámite final. |
| **Clasificar a TI con Poder Alto / Interés Medio-Alto** | Si TI aprueba, bloquea o solo da soporte a los trámites. | Reglas de negocio de la institución: TI no tiene autoridad para aprobar o rechazar trámites académicos. | **Modificado (Poder Bajo / Interés Bajo)** | TI no decide sobre la solicitud (Poder Bajo) y solo interviene si hay fallos técnicos, sin interesarle el resultado final del trámite (Interés Bajo). |

## Fase 2 — PESTEL

# Análisis PESTEL

El análisis PESTEL permite identificar factores externos que pueden influir en el sistema de gestión de solicitudes estudiantiles. Las propuestas generadas por la IA fueron revisadas por el equipo y clasificadas según la evidencia disponible en el caso.

| Factor PESTEL | IA propone | Qué verificamos | Decisión del equipo | Razón |
|---|---|---|---|---|
| **Político** | Existencia de políticas y procedimientos institucionales que pueden influir en la gestión de solicitudes. | El sistema debe funcionar de acuerdo con los procedimientos establecidos por la institución. | **Aceptar como factor a considerar** | Las decisiones y trámites académicos dependen de procedimientos institucionales. |
| **Económico** | Los procesos manuales pueden generar costos asociados al tiempo del personal y al reproceso de solicitudes. | No se cuenta con información concreta sobre costos económicos actuales. | **Modificar** | Se mantiene como posible impacto operativo, pero no se presenta como un costo comprobado. |
| **Social** | Preferencia de los usuarios por diferentes canales de atención y posible resistencia al cambio. | El caso indica la existencia de diferentes canales y la necesidad de considerar la adaptación de los usuarios. | **Aceptar** | Está directamente relacionado con la forma en que los estudiantes y funcionarios interactúan con el proceso. |
| **Tecnológico** | La infraestructura tecnológica puede afectar el funcionamiento del sistema. | No existe evidencia suficiente de fallas tecnológicas actuales en el caso. | **Modificar** | Se considera una condición que debe verificarse, pero no se afirma que actualmente exista una falla tecnológica. |
| **Ambiental** | Reducción del uso de papel mediante la digitalización de las solicitudes. | El uso de papel no aparece como un problema central del caso. | **Rechazar** | No se identifica como un factor que condicione significativamente el problema principal analizado. |
| **Legal** | Protección de los datos personales y de la información de los estudiantes. | Es necesario verificar las normas institucionales y legales aplicables al manejo de información estudiantil. | **Pendiente de verificar** | Es un factor relevante, pero el caso suministrado no contiene suficiente información normativa para afirmarlo como una condición específica. |

## Decisiones humanas frente a las propuestas de IA

El equipo no tomó todas las propuestas de la IA como hechos. Se revisó si cada factor tenía relación directa con el caso y si existía evidencia suficiente para sostenerlo.

En particular, los factores tecnológico y económico fueron modificados porque pueden ser relevantes para el sistema, pero no existen evidencias suficientes para afirmar que actualmente existan fallas tecnológicas o costos económicos específicos.

El factor ambiental fue rechazado debido a que la reducción del uso de papel no constituye un problema central dentro del caso analizado.

El factor legal quedó pendiente de verificación porque la protección de los datos estudiantiles es relevante, pero se requiere consultar la normativa correspondiente antes de establecer conclusiones.

## Aspectos pendientes de validación

- Verificar las políticas y procedimientos institucionales relacionados con las solicitudes.
- Validar si existen costos o tiempos significativos asociados al reproceso de solicitudes.
- Verificar las condiciones actuales de la infraestructura tecnológica.
- Consultar las normas aplicables al tratamiento y protección de los datos de los estudiantes.
- Validar con los usuarios si existe resistencia al cambio o preferencia por determinados canales de atención.

## Fase 3 — Pain Points

| Propuesta IA | Qué verificamos | Evidencia | Decisión del equipo | Razón |
| :--- | :--- | :--- | :--- | :--- |
| **Pain points de TI (PP-07) y Bienestar (PP-08)**, derivados de los stakeholders propuestos por la IA | Si el caso da evidencia directa de fallas técnicas o del proceso de trámites excepcionales. | El caso menciona duplicidad reportada por funcionarios, pero no fallas técnicas ni el proceso excepcional. | **Mantener solo como hipótesis pendiente de validación** | No hay evidencia directa. |

### Decisiones adicionales sobre los Pain Points

Durante esta fase, el equipo revisó los pain points propuestos por la IA y los contrastó con la evidencia disponible en el caso y con los stakeholders identificados.

La IA propuso pain points relacionados principalmente con TI / Soporte y Bienestar Estudiantil. Sin embargo, el equipo determinó que estos no podían presentarse como problemas confirmados, debido a que no existe evidencia directa suficiente sobre fallas técnicas o sobre dificultades específicas en el proceso de trámites excepcionales.

Por esta razón, los pain points de TI y Bienestar se mantienen únicamente como hipótesis pendientes de validación.

En el caso del estudiante, se mantiene como pain point principal la necesidad de conocer el estado y avance de sus solicitudes, debido a que este se relaciona directamente con la regla del sistema identificada en la fase de stakeholders: el estudiante necesita visibilidad sobre su trámite.

Además, se evita presentar las solicitudes perdidas o duplicadas como hechos comprobados. Estas situaciones se consideran hipótesis que requieren ser cuantificadas y verificadas mediante evidencia adicional.


## Fase 4 — Problem/Solution Fit

### 1. Problema identificado

Los estudiantes pueden tener dificultades para conocer el estado y avance de sus solicitudes académicas, lo que puede generar incertidumbre y la necesidad de realizar consultas para obtener información sobre sus trámites.

Este problema se relaciona con el principal pain point identificado para el estudiante: la necesidad de visibilidad sobre el estado de su solicitud.

### 2. Stakeholders afectados

Los principales stakeholders relacionados con el problema son:

- **Estudiante:** Es el usuario principal y necesita conocer el estado de su solicitud.
- **Secretaría de Coordinación:** Puede recibir consultas relacionadas con el estado de las solicitudes y necesita visibilidad para informar al estudiante y organizar el flujo.
- **Coordinador del Proyecto Curricular:** Es responsable de evaluar y aprobar o rechazar las solicitudes académicas.
- **Oficina de Admisiones y Registro:** Ejecuta a nivel central y legal las decisiones aprobadas por la coordinación.

Otros stakeholders, como TI / Soporte y Bienestar Estudiantil, pueden participar en situaciones específicas, pero sus pain points se mantienen como hipótesis pendientes de validación.

### 3. Formulaciones alternativas del problema

#### Alternativa 1 — Enfoque en el estudiante

Los estudiantes pueden tener dificultades para conocer el estado y avance de sus solicitudes académicas, lo que genera incertidumbre y la necesidad de realizar consultas para obtener información sobre sus trámites.

#### Alternativa 2 — Enfoque en el proceso

La gestión de solicitudes estudiantiles puede presentar dificultades de seguimiento y coordinación entre las áreas involucradas, especialmente cuando la información del trámite no se encuentra disponible de forma clara y organizada.

#### Alternativa 3 — Enfoque en la trazabilidad

La falta de información suficiente sobre el registro, seguimiento y estado de las solicitudes estudiantiles puede dificultar la identificación oportuna de problemas y la coordinación de las decisiones entre los responsables del trámite.

### 4. Comparación de alternativas

| Criterio | Alternativa 1 | Alternativa 2 | Alternativa 3 |
|---|---|---|---|
| Enfoque principal | Estudiante | Proceso institucional | Trazabilidad |
| Relación con stakeholders | Directamente relacionada con el usuario principal | Involucra varias áreas | Involucra varios responsables |
| Relación con pain points | Se relaciona directamente con PP-01 | Requiere validar dificultades de coordinación | Requiere validar problemas de registro |
| Evidencia disponible | Existe una necesidad de visibilidad identificada | Se necesita mayor evidencia sobre la coordinación | Se necesita mayor evidencia sobre la trazabilidad |
| Alcance | Más delimitado | Más amplio | Centrado en el seguimiento |
| Supuestos | Necesita validar frecuencia e impacto | Necesita validar cómo funciona actualmente el proceso | Necesita comprobar posibles deficiencias de registro |

### 5. Formulación seleccionada

El equipo seleccionó la **Alternativa 1, centrada en el estudiante**.

La formulación seleccionada es:

> Los estudiantes pueden tener dificultades para conocer el estado y avance de sus solicitudes académicas, lo que genera incertidumbre y la necesidad de realizar consultas para obtener información sobre sus trámites.

### 6. Justificación de la decisión humana

El equipo decidió seleccionar la primera alternativa porque tiene un enfoque directo en los estudiantes, quienes son los principales usuarios del sistema y con quienes tenemos mayor cercanía al formar parte de la comunidad estudiantil.

Nuestra experiencia como estudiantes nos permite comprender de manera más cercana situaciones en las que una persona necesita conocer qué está ocurriendo con una solicitud académica y no cuenta con suficiente información sobre su estado.

Además, esta alternativa se relaciona directamente con el pain point principal identificado para el estudiante: la necesidad de visibilidad sobre el estado de su trámite.

Consideramos que esta formulación permite delimitar el problema de manera clara y evita ampliar innecesariamente el alcance hacia problemas de coordinación o de trazabilidad que todavía requieren mayor evidencia.

La Alternativa 2 fue descartada porque tiene un alcance más amplio y requiere validar con mayor profundidad cómo se coordinan actualmente las diferentes áreas involucradas en el proceso.

La Alternativa 3 fue descartada porque depende de confirmar deficiencias relacionadas con el registro y la trazabilidad de las solicitudes. Aunque pueden existir solicitudes perdidas o duplicadas según el contexto del caso, el equipo decidió no presentarlas como hechos comprobados mientras no exista suficiente evidencia para demostrar su frecuencia e impacto.

### 7. Cómo el sistema podría cambiar o mejorar la situación

A partir del problema identificado, el sistema podría contribuir a mejorar la visibilidad que tienen los estudiantes sobre el estado de sus solicitudes y facilitar el seguimiento del trámite.

Esta mejora también podría beneficiar a las áreas involucradas, ya que una mayor visibilidad del estado de las solicitudes podría facilitar la comunicación con los estudiantes y el seguimiento interno.

En esta fase no se define todavía una solución técnica específica. El objetivo es establecer con claridad el problema y los afectados antes de determinar las características o tecnologías que debería tener el sistema.

### 8. Supuestos y aspectos pendientes de validación

El equipo reconoce que todavía existen aspectos que requieren validación:

- Frecuencia con la que los estudiantes consultan el estado de sus solicitudes.
- Impacto real de la falta de visibilidad.
- Existencia y frecuencia de solicitudes perdidas o duplicadas.
- Dificultades reales de coordinación entre las áreas.
- Participación concreta de TI y Bienestar Estudiantil en los diferentes tipos de solicitudes.

Por lo tanto, estos aspectos no se presentan como hechos definitivos, sino como hipótesis o puntos pendientes de investigación.

## Fase 5 — Lean Canvas

| Propuesta IA | Qué verificamos | Evidencia | Decisión del equipo | Razón |
| :--- | :--- | :--- | :--- | :--- |
| **Bloque de "Ingresos"** con enfoque comercial | Si aplica a un sistema interno de una universidad pública. | No se definió ningún modelo de cobro a estudiantes ni a las áreas. | **Modificado a "Beneficio institucional / operativo"** | Los beneficios esperados son menos consultas repetidas, menos reprocesos y más visibilidad. |
| **Presentar solicitudes perdidas o duplicadas como hechos** en el Canvas | Si las fases anteriores lo respaldan. | En pain points están como hipótesis por cuantificar (evidencia testimonial del caso). | **Rechazado como hecho; se mantiene como hipótesis** | Evita convertir suposiciones en hechos. |
| **Tres formulaciones del problema** (centrada en el estudiante, en el proceso y en la trazabilidad) | Claridad, relación con stakeholders y pain points, evidencia disponible, alcance y nivel de suposiciones. | PP-01 y el caso. | **Elegida la Alternativa 1 (centrada en el estudiante); descartadas la 2 y la 3** | La 1 se relaciona con el usuario principal y con PP-01, y delimita el alcance. La 2 es más amplia y exige validar cómo se coordinan hoy las áreas. La 3 depende de deficiencias de registro que aún necesitan evidencia. |
| **Segmentos**: estudiantes y áreas institucionales | Quiénes usarían el sistema directamente. | Necesidades identificadas en stakeholders. | **Se mantienen Estudiante, Secretaría, Coordinador y Admisiones; se excluyen Decano y Docente como clientes principales** | Decano y Docente solo necesitan información puntual o reportes. |

## Fase 7 - Defensa
| Pregunta / reto de defensa                                                          | Qué debemos verificar                                                                                                  | Evidencia                                                                     | Decisión / respuesta del equipo                                                                      | Razón                                                                                                                             |
| ----------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **¿Por qué este stakeholder tiene ese nivel de poder y no otro?**                   | Que la clasificación Poder/Interés corresponda realmente con su capacidad de afectar el sistema y su nivel de interés. | Matriz Poder/Interés y justificación de stakeholders.                         | Defender la clasificación asignada al stakeholder y explicar por qué no corresponde a otro nivel.    | La clasificación debe basarse en su influencia real sobre el sistema, no en una elección arbitraria.                              |
| **¿Qué propuesta de la IA rechazaron y por qué?**                                   | Que el equipo realmente haya evaluado críticamente las propuestas de la IA.                                            | Registro de decisiones y tabla “IA propone → nosotros decidimos”.             | Rechazar/modificar la propuesta de **[propuesta concreta]**.                                         | La propuesta no estaba suficientemente respaldada por evidencia o no era coherente con el contexto del proyecto.                  |
| **¿Qué decisión cambió después de utilizar IA?**                                    | Que la IA haya servido para generar alternativas y no simplemente para copiar respuestas.                              | Comparación entre propuesta inicial, propuesta de IA y decisión final.        | Explicar qué modificamos y qué criterio utilizamos para hacerlo.                                     | La decisión final fue tomada por el equipo después de contrastar la propuesta con la evidencia disponible.                        |
| **¿Qué evidencia tienen para afirmar que este pain point es real?**                 | Diferenciar evidencia de supuesto.                                                                                     | Evidencia asociada al pain point y trazabilidad con el stakeholder.           | Defender el pain point **[PP-01 / nombre]** como el problema respaldado por la evidencia disponible. | Evitamos presentar una hipótesis como un hecho y explicamos qué información la respalda.                                          |
| **¿Cuál es la diferencia entre el síntoma y el problema que identificaron?**        | Que el equipo comprenda realmente el problema y no solamente su manifestación.                                         | Pain points y formulación final del problema.                                 | Explicar cuál era el síntoma y cuál fue el problema que finalmente seleccionamos.                    | El problema describe la situación que afecta al stakeholder, mientras que el síntoma es una manifestación observable de ella.     |
| **¿Qué parte de su análisis sigue siendo un supuesto?**                             | Que podamos reconocer las limitaciones del análisis.                                                                   | Tabla de evidencias y supuestos.                                              | Identificar explícitamente **[supuesto concreto]** como no validado completamente.                   | Reconocer un supuesto demuestra que no estamos presentando como hecho algo que todavía necesita validación.                       |
| **¿Qué factor PESTEL podría cambiar la viabilidad del sistema?**                    | Que podamos explicar la relación entre contexto externo y sistema.                                                     | Análisis PESTEL y evidencia asociada.                                         | Defender el factor **[factor concreto]** y explicar su impacto.                                      | Ese factor puede modificar las condiciones bajo las cuales el sistema sería viable.                                               |
| **¿Qué bloque del Lean Canvas depende más directamente del stakeholder principal?** | Que exista trazabilidad entre stakeholders y Lean Canvas.                                                              | Lean Canvas y análisis de stakeholders.                                       | Explicar la relación entre **[stakeholder]** y **[bloque]**.                                         | El bloque debe responder a una necesidad o condición identificada previamente en el análisis.                                     |
| **¿Qué incoherencia encontraron en el Lean Canvas y cómo la corrigieron?**          | Que el Canvas sea coherente con los hallazgos anteriores.                                                              | Lean Canvas antes/después y decisiones del Canvas.                            | Explicar el cambio realizado en **[bloque]**.                                                        | La modificación permite que el Canvas sea coherente con los stakeholders y pain points identificados.                             |
| **¿Qué decisión tomó el equipo que la IA no podía tomar por ustedes?**              | Demostrar el criterio humano exigido por IA Resistente Nivel 3.                                                        | Registro de decisiones humanas, evidencia y comparación con propuestas de IA. | Explicar la decisión final y los criterios utilizados.                                               | La IA podía generar alternativas, pero la validación y decisión dependían de la evidencia y del contexto específico del proyecto. |


## Reflexión

**¿En qué se equivocó o quedó corta la IA?**
* Propuso a Control Interno / Auditoría con un enfoque de gobernanza corporativa que no corresponde al problema operativo del caso.
* Planteó a Bienestar como posible resolutor, cuando en la práctica solo emite un concepto.
* En el Lean Canvas presentó como hechos situaciones que en el análisis previo eran hipótesis, y planteó un bloque de ingresos comercial para un sistema institucional.

**¿Qué aportó el equipo que la IA no podía decidir por sí sola?**
* El criterio institucional sobre quién decide y quién solo aporta un concepto.
* Delimitar el alcance (dejar fuera Control Interno, priorizar el problema del estudiante).
* Distinguir entre evidencia, supuesto y propuesta de IA, y decidir qué se presenta como hecho.
