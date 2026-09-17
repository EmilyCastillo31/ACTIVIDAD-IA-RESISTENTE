# Problem/Solution Fit

## 1. Problema validado

Los pacientes adultos mayores (60+) de la IPS no logran completar el agendamiento
de citas médicas por la app debido a una interfaz poco accesible para su nivel de
familiaridad tecnológica, lo que los obliga a saturar la línea telefónica,
generando demoras en la atención para todos los pacientes.

## 2. Afectados (stakeholders relacionados)

- **Pacientes adultos mayores** (primario): no logran agendar por su cuenta.
- **Personal administrativo/recepción** (primario): recibe la sobrecarga de
  llamadas y reclamos.
- **Médicos** (secundario): ven agendas mal distribuidas por citas mal gestionadas.
- **Coordinación de EPS** (clave/decisor): responde por indicadores de servicio
  y quejas ante el ente regulador.

## 3. Cómo el sistema debería cambiar/mejorar

Se plantea rediseñar el flujo de agendamiento para incluir un modo simplificado
(menos pasos, texto más grande, opción de asistencia guiada o agendamiento
asistido por un tercero autorizado), sin eliminar el canal telefónico, pero
reduciendo su saturación al resolver la causa raíz del problema en la app.

## 4. Formulaciones alternativas generadas por IA (Ciclo 1 — Generar)

| # | Formulación | Estado |
|---|---|---|
| A | Los pacientes adultos mayores no pueden agendar citas médicas por la app | ✅ Adoptada (con ajuste) |
| B | El proceso de agendamiento no está diseñado para usuarios con baja alfabetización digital | ⚠️ Parcialmente incorporada |
| C | La IPS no tiene un canal de agendamiento accesible para todos los segmentos de pacientes | ❌ Rechazada |

## 5. Intervención humana (Ciclo 2–3 — Criticar y Decidir)

- **Qué verificamos:** registros de quejas de recepción, confirmando que ~80%
  de los reclamos por "no pude agendar" provienen de pacientes mayores de 60 años.
- **Qué rechazamos:** la formulación C, por ser institucional y no accionable
  (no orienta ningún rediseño concreto).
- **Qué modificamos:** se tomó la especificidad de A y se incorporó parcialmente
  el enfoque de "accesibilidad" de B, pero acotado al segmento con evidencia real.
- **Decisión final:** formulación combinada (ver sección 1), justificada por ser
  específica, verificable con datos existentes y con relación causal clara al
  problema de saturación telefónica.
- **Reflexión:** la IA tendía a generalizar el problema (formulación B y C) para
  sonar más "escalable", pero eso diluía la evidencia real que teníamos. El
  equipo aportó el contraste con los datos de quejas, algo que la IA no podía
  verificar por sí sola.

## 6. Comparación de formulaciones (evidencia GitHub requerida)

| Criterio              | A                        | B                                             | C                                        |
|-----------------------|--------------------------|-----------------------------------------------|------------------------------------------|
| Evidencia disponible  | Alta (quejas por edad)  | Media (sin dato de "alfabetización digital") | Baja (comparación difusa entre canales) |
| Accionabilidad        | Alta                     | Media                                          | Baja                                     |
| Alcance               | Acotado y realista       | Amplio pero no sustentado                     | Institucional, no operativo             |
| Elegida               | ✅                       | Parcial                                        | ❌                                        |
