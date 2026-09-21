# Registro de Prompts de IA

Aquí van los prompts **realmente usados**, en el orden de las fases. Cada fase debe tener los tres ciclos: Generar → Criticar → Decidir. Lo que aparece como **[COMPLETAR]** aún no está registrado.

---

## Fase 1 — Stakeholders

**Herramienta:** Gemini
**Fecha de uso:** 15 de septiembre de 2026
**Propósito:** Generar alternativas, detectar posibles omisiones en la lista inicial de stakeholders e identificar quién necesita visibilidad del estado y quién debe resolver las solicitudes.

### Ciclo 1 — Generar

> Actúa como analista de sistemas crítico. Este es el contexto de nuestro proyecto: Una institución recibe diariamente solicitudes estudiantiles (certificados, matrículas, problemas académicos, cambios de grupo) por múltiples canales (correo, formularios, atención presencial). Los funcionarios reportan solicitudes duplicadas o perdidas. Tenemos la restricción de que debemos identificar qué stakeholder necesita visibilidad del estado del trámite y cuál necesita realmente resolverlo.
>
> Estos son mis 6 stakeholders actuales:
> 1. Estudiante
> 2. Secretaría de Coordinación
> 3. Coordinador del Proyecto Curricular
> 4. Docente
> 5. Decano
> 6. Oficina de Admisiones y Registro.
>
> Genera 3 stakeholders que podríamos estar omitiendo. Para cada uno indica tipo (primario, secundario, clave/decisor o externo), nivel de poder, nivel de interés, y por qué podría afectar o ser afectado. Además, especifica si ese nuevo actor necesita visibilidad del estado o necesita resolver la solicitud. No decidas por mí; plantea alternativas.

### Ciclo 2 — Criticar

**Herramienta:** Gemini
**Fecha de uso:** 15 de septiembre de 2026

> Actúa como revisor crítico de nuestro mapa final de 8 stakeholders (Estudiante, Secretaría de Coordinación, Coordinador del Proyecto Curricular, Docente, Decano, Oficina de Admisiones y Registro, Oficina de TI, Bienestar Estudiantil). Busca inconsistencias en nuestra clasificación de Poder/Interés. Propón cambios o advierte sobre posibles errores en nuestra regla de quién necesita "Visibilidad" vs. quién necesita "Resolver" el trámite. Separa claramente hechos institucionales, supuestos y tus recomendaciones.

### Ciclo 3 — Decidir

Decisión humana registrada en [`../01-stakeholders/decisiones-stakeholders.md`](../01-stakeholders/decisiones-stakeholders.md) y en [`decisiones-humanas.md`](./decisiones-humanas.md).

---

## Fase 2 — PESTEL

**[COMPLETAR por quienes desarrollan la Unidad 2: herramienta, fecha, prompts de los ciclos 1, 2 y 3.]**

---

## Fase 3 — Pain Points

**[COMPLETAR: herramienta, fecha y prompts.]** En `pain-points.md`, PP-07 y PP-08 figuran con origen en una propuesta de IA, por lo que existió al menos un prompt. Prompt sugerido por la guía:

> Estos son nuestros pain points [LISTA]. Diferencia cuáles parecen síntomas, cuáles son problemas y cuáles son oportunidades. Explica qué evidencia necesitaríamos para validar cada uno.

---

## Fase 4 — Problem/Solution Fit

**[COMPLETAR por quienes desarrollan la Unidad 4: herramienta, fecha y prompts.]** Prompt sugerido por la guía:

> Compara estas tres formulaciones del problema [A, B, C]. Evalúalas usando: stakeholder afectado, evidencia, impacto, claridad y relación con el sistema. Recomienda una, pero deja explícito qué debería verificar el equipo antes de adoptarla.

---

## Fase 5 — Lean Canvas

**Herramienta:** **[COMPLETAR]**
**Fecha de uso:** **[COMPLETAR]**

### Ciclo 1 — Generar

> Actúa como un analista de sistemas experto en modelado de negocios y metodologías agiles. Estamos desarrollando un proyecto universitario en la Universidad Distrital sobre un "Sistema de atención de solicitudes estudiantiles".
>
> Aquí tienes el contexto clave de nuestro análisis previo:
> - Stakeholder principal: Estudiante (Primario, poder bajo, interés alto - necesita visibilidad del estado de sus trámites).
> - Stakeholders secundarios/clave: Secretaría de Coordinación, Coordinador del Proyecto Curricular, Oficina de Admisiones y Registro, Docentes, Bienestar Estudiantil, TI.
> - Problema validado: "Los estudiantes pueden tener dificultades para conocer el estado y avance de sus solicitudes académicas, lo que genera incertidumbre y la necesidad de realizar consultas repetidas."
> - Factores PESTEL relevantes: Preferencia de los estudiantes por múltiples canales de atención (riesgo de resistencia al cambio) y dependencia de una infraestructura tecnológica confiable.
>
> Por favor, genera una propuesta para los 9 bloques del Lean Canvas adaptada a este sistema universitario:
> 1. Segmento de Clientes
> 2. Problema
> 3. Propuesta de Valor
> 4. Solución
> 5. Canales
> 6. Flujo de Ingresos (enfocado en beneficio institucional/operativo)
> 7. Estructura de Costos
> 8. Métricas Clave
> 9. Ventaja Desleal
>
> No inventes datos comerciales irreales (recuerda que es un sistema interno de una universidad pública). Presenta la propuesta de forma clara bloque por bloque.

### Ciclo 2 — Criticar (comparación de formulaciones del problema)

**[COMPLETAR: pegar el prompt exacto usado.]**

### Ciclo 3 — Decidir (revisión de coherencia)

**[COMPLETAR: pegar el prompt exacto usado.]**

Decisiones en [`../05-lean-canvas/decisiones-canvas.md`](../05-lean-canvas/decisiones-canvas.md).
