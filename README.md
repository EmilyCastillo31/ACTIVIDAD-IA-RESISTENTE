# Sistema de Atención de Solicitudes Estudiantiles

**Actividad IA Resistente — Nivel 3 · Análisis de Sistemas**
Tecnología en Sistematización de Datos · Universidad Distrital Francisco José de Caldas

**Equipo:** Scrum Squad (Squad 2)
**Integrantes:**
* Paula Camila Hurtado Ramírez
* Samuel Julián Castillo Muñoz
* Emily Sofia Castillo Preciado
* Santiago Abella Bello
* Juan Miguel Tapiero Gutiérrez

## Problema analizado

Los estudiantes enfrentan incertidumbre por la falta de visibilidad sobre el estado de sus solicitudes académicas. Esto genera una sobrecarga operativa de consultas para la Secretaría de Coordinación, por lo que se requiere un sistema que centralice y transparente el seguimiento del trámite para el usuario final.

## Síntesis de la decisión final

* **Problema principal:** la dificultad de los estudiantes para conocer el estado y avance de sus solicitudes académicas.
* **Tipo de problema:** es principalmente un problema de **información** (falta de visibilidad del estado), con una causa probable de **proceso** (solicitudes que llegan por canales dispersos, sin trazabilidad entre áreas; por validar). No lo tratamos como un problema principalmente tecnológico: el caso no reporta fallas de infraestructura y la tecnología es el medio para resolverlo, no su origen. La comunicación (notificar al estudiante) es una consecuencia que la solución atiende.
* **Visibilidad vs. resolución:** necesitan visibilidad el Estudiante, la Secretaría de Coordinación, el Docente, el Decano, TI y Bienestar Estudiantil. Necesitan resolver el Coordinador del Proyecto Curricular y la Oficina de Admisiones y Registro.
* **Urgencia y responsable:** no todas las solicitudes tienen la misma urgencia ni el mismo responsable; por eso cada solicitud debe registrar su tipo (ver `03-pain-points/pain-points.md`, sección 5).
* **Canales:** algunos estudiantes prefieren canales tradicionales y pueden resistirse al cambio, por lo que se mantiene un canal presencial o telefónico de respaldo.
* **Propuesta:** un sistema web con registro único de solicitudes, número de radicado, seguimiento por estados, historial, notificaciones automáticas y una bandeja de gestión para las áreas.
* **Supuestos aún por validar:** frecuencia de las consultas repetidas, frecuencia de solicitudes perdidas o duplicadas, nivel de adopción del sistema y necesidades específicas de cada área.
* **Uso de la IA:** la IA propuso alternativas y críticas (stakeholders, formulaciones del problema y Lean Canvas); el equipo verificó, aceptó, rechazó o modificó cada propuesta. Todo el registro está en `06-ia/`.

## Enlaces a las evidencias

* [Unidad 1: Stakeholders](./01-stakeholders/)
* [Unidad 2: Análisis PESTEL](./02-pestel/)
* [Unidad 3: Pain Points](./03-pain-points/)
* [Unidad 4: Problem / Solution Fit](./04-problem-solution-fit/)
* [Unidad 5: Lean Canvas](./05-lean-canvas/)
* [Unidad 6: Uso de IA Resistente (prompts, salidas y decisiones)](./06-ia/)
* [Unidad 7: Defensa](./07-defensa/)
