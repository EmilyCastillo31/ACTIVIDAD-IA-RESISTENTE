**Salidas relevantes de la IA**  
Resumen de las propuestas de la IA que influyeron en el análisis. Se recomienda agregar también las capturas de pantalla en una carpeta 06-ia/capturas/.  
| | | | | |  
|-|-|-|-|-|  
| **Fase** | **Ciclo** | **Fecha** | **Herramienta** | **Estado** |   
| 1. Stakeholders | 1 — Generar | 15/09/2026 | Gemini | Registrado abajo |   
| 1. Stakeholders | 2 — Criticar | 15/09/2026 | Gemini | Registrado abajo |   
| 2. PESTEL | 1, 2 y 3 | **[COMPLETAR]** | **[COMPLETAR]** | A cargo de la Unidad 2 |   
| 3. Pain Points | 1, 2 y 3 | **[COMPLETAR]** | **[COMPLETAR]** | Pendiente |   
| 4. Problem/Solution Fit | 1, 2 y 3 | **[COMPLETAR]** | **[COMPLETAR]** | A cargo de la Unidad 4 |   
| 5. Lean Canvas | 1 — Generar | **[COMPLETAR]** | **[COMPLETAR]** | Resumen abajo |   
   
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANklEQVR4nO3OMQ2AABAAsSNBCkJfFEIwwIgHRiywEZJWQZeZ2ao9AAD+4lyruzq+ngAA8Nr1AOHsBegrsOrIAAAAAElFTkSuQmCC)  
**Fase 1 — Stakeholders · Ciclo 1 (Generar)**  
**Fecha:** 15/09/2026 ·  **Herramienta:** Gemini  
   
 **Propósito:** detectar stakeholders omitidos y definir quién necesita visibilidad y quién resolver.  
La IA planteó que quedarse solo con la capa operativa directa deja sin considerar áreas de soporte, control y auditoría. Propuso tres stakeholders nuevos:  
**1. Oficina de Tecnologías de la Información (TI) / Soporte de Sistemas**  
- **Tipo:** Secundario (operativo/soporte).  
- **Poder:** Alto (controla la factibilidad técnica, las integraciones, el almacenamiento y el mantenimiento).  
- **Interés:** Medio-Alto (le afecta el aumento de tickets de soporte por fallos del canal o duplicación de solicitudes).  
- **Por qué afecta o es afectado:** si el sistema no centraliza los canales, la carga de soporte recae sobre TI. Además, si el canal de entrada no respeta sus políticas de arquitectura, el proyecto puede ser bloqueado técnicamente.  
- **Visibilidad vs. resolución:**  
  - *Opción A:* solo visibilidad de logs y métricas (entregas, fallos de integración, tiempos de respuesta).  
  - *Opción B:* resolutor de segundo o tercer nivel cuando la solicitud falla por una inconsistencia de datos o un error del sistema.  
**2. Oficina de Control Interno / Auditoría y Calidad**  
- **Tipo:** Clave / Decisor (gobernanza y regulación).  
- **Poder:** Alto (puede vetar procesos y exigir cumplimiento de los acuerdos de nivel de servicio institucionales).  
- **Interés:** Medio (le importan los indicadores agregados y el cumplimiento de tiempos, no la gestión individual).  
- **Por qué afecta o es afectado:** las solicitudes duplicadas o perdidas suelen incumplir los acuerdos de nivel de servicio; si se detecta pérdida de peticiones, la institución enfrenta riesgos legales y administrativos.  
- **Visibilidad vs. resolución:**  
  - *Opción A:* visibilidad analítica agregada (tiempos de atención, cuellos de botella, tasa de duplicidad), sin resolver.  
  - *Opción B:* visto bueno institucional solo en trámites de excepción legal o reclamos que superen cierto tiempo.  
**3. Bienestar Estudiantil / Asistencia Social o Académica**  
- **Tipo:** Primario / Secundario (según el trámite).  
- **Poder:** Bajo a Medio (emite conceptos o recomendaciones, no siempre vinculantes).  
- **Interés:** Alto (cambios de grupo, cancelaciones extemporáneas o aplazamientos suelen estar motivados por factores de salud, económicos o personales).  
- **Por qué afecta o es afectado:** si el sistema limita la solicitud al canal administrativo, se pierde el contexto psicosocial del estudiante. Un concepto de Bienestar suele ser insumo para que se tome una decisión justificada.  
- **Visibilidad vs. resolución:**  
  - *Opción A:* visibilidad del estado y del historial para acompañar, sin resolver el trámite.  
  - *Opción B:* resolutor parcial que emite un concepto de aprobado o rechazado antes de que pase a Secretaría o Coordinación.  
**Qué influyó en el análisis:** las propuestas 1 y 3 llevaron a incluir TI y Bienestar (de 6 a 8 stakeholders). La propuesta 2 se rechazó.  
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANElEQVR4nO3OMQ0AIAwAwZIgBKnVgjN8dGDBABMhuZt+/JaZIyJmAADwi9VP1NMNAABu1AaU3AUhiyfJeAAAAABJRU5ErkJggg==)  
**Fase 1 — Stakeholders · Ciclo 2 (Criticar)**  
**Fecha:** 15/09/2026 ·  **Herramienta:** Gemini  
   
 **Propósito:** Cuestionar la clasificación de Poder/Interés y las reglas de visibilidad/resolución del mapa final de 8 stakeholders.  
**Resumen de la salida:**  
   
 La IA detectó inconsistencias en la jerarquía inicial. Advirtió que la Oficina de TI, al ser un área de soporte técnico, no tiene autoridad para aprobar o rechazar trámites académicos, por lo que sugerir un "Poder Alto" era un error de contexto institucional. Tambien señaló que Bienestar Estudiantil emite conceptos psicosociales que sirven como insumo (Visibilidad), pero según la estructura universitaria, no tienen la potestad de actuar como resolutores finales del trámite.  
**Qué influyó en el análisis:** Esta crítica fue clave para confirmar la decisión del equipo de ajustar a la Oficina de TI a "Poder Bajo / Interés Bajo" y de asegurar que Bienestar Estudiantil quedara configurado únicamente con la regla de "Visibilidad", delegando la resolución final al Coordinador del Proyecto Curricular.  
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANUlEQVR4nO3OQQmAABRAsSd49m4tA8nPaQJjWMGbCFuCLTOzV2cAAPzFvVZbdXw9AQDgtesBorcEPwOKyvQAAAAASUVORK5CYII=)  
**Fase 5 — Lean Canvas · Ciclo 1 (Generar)**  
**Fecha:**  **[COMPLETAR]** ·  **Herramienta:**  **[COMPLETAR]**  
   
 **Propósito:** generar una primera propuesta de los 9 bloques del Lean Canvas.  
La IA propuso una estructura basada en:  
- Estudiantes como usuarios principales.  
- Secretaría de Coordinación y otras áreas institucionales como usuarios internos.  
- Dificultad para conocer el estado de las solicitudes como problema.  
- Registro único y seguimiento mediante estados.  
- Notificaciones automáticas.  
- Aplicación web como canal principal.  
- Reducción de carga operativa como beneficio.  
- Costos de desarrollo, infraestructura, capacitación y soporte.  
- Métricas de tiempos de respuesta, seguimiento y adopción.  
**Qué influyó en el análisis:** sirvió como base de los 9 bloques, pero el equipo corrigió el bloque de ingresos y evitó presentar hipótesis como hechos.  
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAnEAAAACCAYAAAA3pIp+AAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAANUlEQVR4nO3OMQ2AABAAsSNBCUpfD6ZYGZDAgAU2QtIq6DIzW7UHAMBfHGt1V+fXEwAAXrseHCoGAe/SKtAAAAAASUVORK5CYII=)  
**Fase 5 — Lean Canvas · Ciclos 2 y 3**  
**[COMPLETAR: resumen de las salidas de la IA en la comparación de formulaciones (ciclo 2) y en la revisión de coherencia (ciclo 3).]**  
