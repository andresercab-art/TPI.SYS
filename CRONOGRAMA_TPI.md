# Cronograma de Trabajo y Planificación de Hitos (TPI)

**Asignatura:** Señales y Sistemas - Bioingeniería (Plan 2026)  
**Período de Ejecución:** Segundo Bloque (Semanas 11 a 15)  
**Tema General:** Procesamiento de Señales Electrocardiográficas (ECG)  
**Estado Actual:** Semana 11 - En Curso (Hito 1)  

---

## 1. Vista General del Cronograma (Semanas 11 a 15)

| Semana | Hito / Etapa | Actividades Principales | Entregable / Instancia | Estado |
| :---: | :--- | :--- | :--- | :---: |
| **Semana 11** | **HITO 1:** Definición y Selección del Problema | • Lluvia de ideas y Diagrama de Ishikawa.<br>• Definición de 3 propuestas de ECG.<br>• Reunión con Tutor asignado. | Documento breve (1 carilla) con 3 propuestas y selección final de 1 idea. | **[EN CURSO]** |
| **Semana 12** | **HITO 2:** Propuesta de Implementación | • Diseño del diagrama en bloques del sistema.<br>• Definición matemática de filtros/transformadas.<br>• Selección de base de datos (PhysioNet). | Documento (2 carillas) con diagrama de flujo, justificación teórica y link a datos. | [PENDIENTE] |
| **Semana 13** | **Desarrollo y Tutoría** | • Procesamiento de señales en Python.<br>• Implementación de algoritmos y filtros.<br>• Consultas de avance con el Tutor. | Código preliminar e informes de avance interno. | [PENDIENTE] |
| **Semana 14** | **HITO 3:** Prototipo Funcional (MVP) | • Demostración de código Python ejecutable.<br>• Filtrado y procesamiento de señales ECG.<br>• Visualización de entradas vs. salidas. | Jupyter Notebook / Script funcional + Gráficos de resultados preliminares. | [PENDIENTE] |
| **Semana 15** | **HITO 4:** Defensa Final y Cierre | • Presentación oral (15-20 min por grupo).<br>• Demostración en vivo y análisis crítico.<br>• Defensa conceptual e individual. | Presentación con soporte visual + Código final + Defensa individual. | [PENDIENTE] |

---

## 2. Detalle de Hitos y Entregables

### HITO 1: Definición y Selección del Problema
* **Período:** Semana 11  
* **Objetivos:** Identificar el problema biomédico, analizar causas/ruidos con Ishikawa y definir alcance.  
* **Entregable:** Documento de 1 carilla con 3 propuestas basadas en datos reales de PhysioNet.  
* **Resultado Esperado:** Selección de 1 propuesta final validada por el Tutor.  

---

### HITO 2: Propuesta de Implementación
* **Período:** Semana 12  
* **Objetivos:** Definir la arquitectura de procesamiento y el marco matemático.  
* **Entregable:** Documento de 2 carillas que incluye:  
  * Diagrama de bloques / flujo del sistema de procesamiento.  
  * Justificación teórica de filtros (FIR/IIR/Notch), transformadas (FFT/PSD) y ecuaciones.  
  * Enlace a la base de datos de PhysioNet seleccionada.  
* **Resultado Esperado:** Propuesta de implementación ajustada y aprobada por el Tutor.  

---

### HITO 3: Prototipo Funcional (MVP)
* **Período:** Semana 14  
* **Objetivos:** Validar el código ejecutable y verificar el correcto procesamiento de las señales.  
* **Entregable:**  
  * Notebook de Python (Jupyter/Colab) o script ejecutable estructurado.  
  * Visualizaciones (señal ECG original vs. filtrada, espectros de frecuencia, detección de picos R).  
* **Resultado Esperado:** Revisión técnica de código con el Tutor y corrección de errores antes de la defensa final.  

---

### HITO 4: Defensa Final y Cierre
* **Período:** Semana 15  
* **Objetivos:** Comunicar los resultados obtenidos, justificar decisiones de diseño y responder preguntas individuales.  
* **Formato:** Defensa pública de 15 a 20 minutos por grupo.  
* **Requisitos:**  
  * Presentación oral con soporte visual.  
  * Demostración en vivo o análisis estático crítico de gráficos.  
  * Defensa individual ante el tribunal/docentes sobre fundamentos de señales y sistemas.  

---

## 3. Asignación de Roles y Responsabilidades

| Rol | Responsable Sugerido | Tareas Clave |
| :--- | :--- | :--- |
| **Moderador / Coordinador** | [Nombre Apellido] | Gestión de reuniones, control de cronograma e interacción con el Tutor. |
| **Responsable Técnico (Lead Coder)** | [Nombre Apellido] | Estructuración del repositorio, calidad del código Python y librerías (SciPy, NumPy). |
| **Analista / Documentador (Scribe)** | [Nombre Apellido] | Búsqueda bibliográfica, redacción de documentos (Hitos 1 a 4) y registro de decisiones. |
| **Desarrollador / Procesamiento** | [Integrantes del equipo] | Implementación de filtros, algoritmos de detección (ej. Pan-Tompkins) y transformadas. |
| **Analista de Datos / Visualización** | [Integrantes del equipo] | Carga de registros de PhysioNet, análisis espectral y generación de gráficos. |

---

## 4. Matriz de Evaluación del TPI

| Dimensión | Ponderación | Criterios de Evaluación |
| :--- | :---: | :--- |
| **Proceso Metodológico** | **25%** | Cumplimiento de hitos en fecha (Semanas 11, 12, 14), uso de herramientas (Ishikawa, roles, Git) y participación en tutorías. |
| **Calidad Técnica (Código)** | **25%** | Código Python funcional, ordenado, comentado y uso correcto de librerías especializadas. |
| **Dominio Conceptual** | **35%** | Justificación teórica sólida, vinculación matemática con el fenómeno fisiológico y respuestas individuales en la defensa. |
| **Comunicación y Resultados** | **15%** | Claridad en la exposición oral, calidad visual de gráficos y capacidad de síntesis/conclusión. |
