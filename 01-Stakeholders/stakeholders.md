# Identificación de Stakeholders (Unidad 1)

Stakeholders identificados para el sistema de gestión de solicitudes estudiantiles, clasificados según su tipo, nivel de poder/interés y la restricción del caso (necesidad de visibilidad o resolución).

### 1. Estudiante
* **Tipo:** Primario
* **Poder:** Bajo | **Interés:** Alto
* **Impacto:** Es el usuario que origina la solicitud y el principal afectado si esta se pierde o duplica. 
* **Regla del sistema:** Necesita Visibilidad (saber en qué estado va su trámite).

### 2. Secretaría de Coordinación
* **Tipo:** Secundario
* **Poder:** Bajo | **Interés:** Alto
* **Impacto:** Recibe la carga operativa de las quejas por solicitudes perdidas.
* **Regla del sistema:** Necesita Visibilidad (para informar al estudiante y organizar el flujo).

### 3. Coordinador del Proyecto Curricular
* **Tipo:** Clave / Decisor
* **Poder:** Alto | **Interés:** Alto
* **Impacto:** Es el responsable de evaluar y aprobar/rechazar las solicitudes académicas.
* **Regla del sistema:** Necesita Resolver (toma la decisión sobre el trámite).

### 4. Docente
* **Tipo:** Secundario
* **Poder:** Bajo | **Interés:** Bajo
* **Impacto:** Solo le interesa el resultado final del trámite: si el estudiante aparece en su lista.
* **Regla del sistema:** Necesita Visibilidad (solo del resultado que le afecte).

### 5. Decano
* **Tipo:** Externo / Directivo
* **Poder:** Alto | **Interés:** Bajo
* **Impacto:** No opera el sistema a diario, pero interviene si hay problemas graves o escalamientos.
* **Regla del sistema:** Necesita Visibilidad 

### 6. Oficina de Admisiones y Registro
* **Tipo:** Clave / Decisor
* **Poder:** Alto | **Interés:** Alto
* **Impacto:** Ejecuta a nivel central y legal las decisiones aprobadas por la coordinación.
* **Regla del sistema:** Necesita Resolver (procesa certificaciones y matrículas oficiales).

### 7. Oficina de TI / Soporte (Aportado por  la IA)
* **Tipo:** Secundario
* **Poder:** Bajo | **Interés:** Bajo
* **Impacto:** Asume la carga técnica si el sistema falla o duplica registros.
* **Regla del sistema:** Necesita Visibilidad (monitoreo de logs y errores).

### 8. Bienestar Estudiantil (Aportado por la IA)
* **Tipo:** Secundario
* **Poder:** Bajo | **Interés:** Alto
* **Impacto:** Emite conceptos psicosociales para trámites excepcionales: (ej. aplazamientos por salud).
* **Regla del sistema:** Necesita Visibilidad (emite concepto, pero no resuelve el trámite final).
