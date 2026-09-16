
# Pain Points (Fase 3)

## 1. Contexto del sistema

El sistema de información seleccionado es un sistema de gestión de solicitudes estudiantiles. Su propósito de análisis es comprender las dificultades de los stakeholders en el registro, seguimiento, evaluación y resolución de solicitudes académicas.

Los pain points se identifican a partir del documento de stakeholders, el contexto del caso y las propuestas generadas por IA. Las propuestas que no cuentan con evidencia directa se consideran hipótesis pendientes de validación.

## 2. Pain points por stakeholder

### PP-01. Estudiante

- **Stakeholder:** Estudiante.
- **Tipo:** Primario.
- **Pain point:** Dificultad para conocer el estado y avance de una solicitud académica.
- **Impacto:** Incertidumbre sobre el trámite, consultas repetidas y posible retraso en la toma de decisiones personales.
- **Origen:** Análisis del equipo y contexto del caso.
- **Evidencia:** El documento de stakeholders establece la necesidad de visibilidad.
- **Estado:** Conservar como pain point que requiere validación de su frecuencia e impacto.

### PP-02. Secretaría de Coordinación

- **Stakeholder:** Secretaría de Coordinación.
- **Tipo:** Secundario.
- **Pain point:** Carga operativa relacionada con las consultas de los estudiantes sobre solicitudes que no pueden localizarse o cuyo estado no es claro.
- **Impacto:** Mayor tiempo dedicado a responder consultas y organizar el flujo de solicitudes.
- **Origen:** Documento de stakeholders.
- **Evidencia:** Se describe una carga operativa por quejas sobre solicitudes perdidas.
- **Estado:** Conservar como hipótesis defendible; se requiere verificar la frecuencia y el volumen de consultas.

### PP-03. Coordinador del Proyecto Curricular

- **Stakeholder:** Coordinador del Proyecto Curricular.
- **Tipo:** Clave / Decisor.
- **Pain point:** Necesidad de disponer de información confiable y organizada para evaluar y decidir sobre las solicitudes académicas.
- **Impacto:** Posibles dificultades para dar seguimiento a los trámites y tomar decisiones oportunas.
- **Origen:** Análisis del rol del stakeholder.
- **Evidencia:** El documento lo identifica como responsable de evaluar y aprobar o rechazar solicitudes.
- **Estado:** Conservar como hipótesis; validar si existen dificultades de acceso, organización o seguimiento.

### PP-04. Oficina de Admisiones y Registro

- **Stakeholder:** Oficina de Admisiones y Registro.
- **Tipo:** Clave / Decisor.
- **Pain point:** Posible dificultad para recibir y ejecutar de forma consistente las decisiones aprobadas por la coordinación.
- **Impacto:** Retrasos, reprocesos o inconsistencias en los trámites oficiales, si se presentan fallas en la comunicación o transferencia de información.
- **Origen:** Análisis del rol del stakeholder.
- **Evidencia:** El documento de stakeholders establece su responsabilidad en la ejecución de decisiones a nivel central y legal.
- **Estado:** Conservar como hipótesis pendiente de validación.

### PP-05. Docente

- **Stakeholder:** Docente.
- **Tipo:** Secundario.
- **Pain point:** Acceso limitado a la información final de los trámites que afectan sus listas académicas.
- **Impacto:** Dificultades para conocer oportunamente cambios que afectan la organización académica.
- **Origen:** Documento de stakeholders.
- **Evidencia:** Se indica que necesita visibilidad del resultado que le afecte.
- **Estado:** Conservar como posible pain point; validar qué información necesita y con qué frecuencia.

### PP-06. Decano

- **Stakeholder:** Decano.
- **Tipo:** Externo / Directivo.
- **Pain point:** Falta de visibilidad consolidada sobre problemas graves o solicitudes que requieren escalamiento.
- **Impacto:** Dificultad potencial para supervisar situaciones que requieren intervención directiva.
- **Origen:** Análisis del rol del stakeholder.
- **Evidencia:** El documento señala que interviene en situaciones graves o escalamientos.
- **Estado:** Conservar como hipótesis; validar las necesidades reales de información directiva.

### PP-07. Oficina de TI / Soporte

- **Stakeholder:** Oficina de TI / Soporte.
- **Tipo:** Secundario.
- **Pain point:** Posible dificultad para detectar y rastrear errores, fallas o duplicidad de registros.
- **Impacto:** Mayor tiempo de diagnóstico y atención de incidentes, si estos problemas se presentan.
- **Origen:** Propuesta de IA y documento de stakeholders.
- **Evidencia:** La IA propuso este stakeholder y el documento indica su relación con fallas o duplicidad.
- **Estado:** Mantener como hipótesis; validar si el sistema actual presenta estos incidentes y qué capacidades de monitoreo existen.

### PP-08. Bienestar Estudiantil

- **Stakeholder:** Bienestar Estudiantil.
- **Tipo:** Secundario.
- **Pain point:** Posible dificultad para consultar o dar seguimiento a los conceptos emitidos para trámites excepcionales.
- **Impacto:** Posibles retrasos o reprocesos en la comunicación de conceptos, si existen dificultades de seguimiento.
- **Origen:** Propuesta de IA y documento de stakeholders.
- **Evidencia:** Se identifica su participación en trámites excepcionales y su necesidad de visibilidad.
- **Estado:** Pendiente de validación con el área o con evidencia del proceso real.

## 3. Síntomas vs. problemas

| Síntoma observado o supuesto | Posible problema subyacente | Estado |
|---|---|---|
| El estudiante consulta repetidamente el estado de una solicitud. | Información insuficiente o poco accesible sobre el seguimiento del trámite. | Hipótesis por validar |
| Se presentan quejas por solicitudes perdidas. | Posibles deficiencias en el registro, localización o trazabilidad de solicitudes. | Requiere evidencia |
| Se menciona duplicidad de registros. | Posible falta de controles o inconsistencias en el registro de solicitudes. | No comprobado |
| Hay necesidad de conocer los resultados de los trámites. | Falta de visibilidad sobre decisiones o cambios que afectan a los usuarios. | Requiere validación |

## 4. Decisiones humanas

El equipo revisó los pain points propuestos y los clasificó según la evidencia disponible. Se conservaron los problemas relacionados con la visibilidad, seguimiento y gestión de solicitudes, porque se relacionan con los roles identificados y con las restricciones del caso.

Las posibles fallas de infraestructura, duplicidad de registros y problemas específicos de cada área no se presentan como hechos comprobados. Se mantienen como hipótesis cuando tienen una relación razonable con el sistema, pero requieren evidencia adicional.

Los pain points que no se puedan relacionar con una necesidad real de los stakeholders o que no cuenten con una justificación suficiente deberán descartarse o reformularse.

## 5. Conclusión

El pain point transversal identificado es la necesidad de contar con información confiable y accesible sobre el estado y seguimiento de las solicitudes estudiantiles. Esta necesidad afecta de manera diferente a los estudiantes, las áreas administrativas y los responsables de la toma de decisiones.

El equipo debe validar la existencia, frecuencia e impacto de cada dificultad antes de considerarla un problema confirmado.
