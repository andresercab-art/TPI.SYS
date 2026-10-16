# Hito 1: Definición y Selección del Problema

**Asignatura:** Señales y Sistemas - Bioingeniería  
**Trabajo Práctico Integrador (TPI)** | **Semana 11**  
**Tema General:** Procesamiento de Señales Electrocardiográficas (ECG)  

---

## 1. Datos del Grupo y Asignación de Roles

* **Grupo N°:** [Insertar Número de Grupo]

* **Integrantes y Roles:**
  * **[Fátima Luna Latorre]** - *Moderador/Coordinador* (Gestión de reuniones y cronograma)
  * **[Nombre Apellido]** - *Responsable Técnico / Lead Coder* (Estructura de código en Python)
  * **[Kiara Catalina Furlán]** - *Analista / Documentador (Scribe)* (Registro de decisiones e informe)
  * **[Nombre Apellido]** - *Analista / Documentador (Scribe)* (Registro de decisiones e informe)
  * **[Nombre Apellido]** - *Desarrollador / Procesamiento de Señales*
  * **[Nombre Apellido]** - *Desarrollador / Análisis de Datos*
  * **[Nombre Apellido]** - *Desarrollador / Análisis de Datos*

---

## 2. Propuestas de Problemas Potenciales (ECG)

### Propuesta 1: Filtrado Digital y Supresión de Artefactos Fisiológicos y de Instrumentación

* **Problema biomédico:**  
  Las señales de ECG suelen verse contaminadas por interferencias de la red eléctrica (50/60 Hz), deriva de la línea base por respiración y ruido electromiográfico (EMG) por movimiento del paciente.

* **Enfoque técnico (Señales y Sistemas):**  
  Diseñar e implementar filtros digitales en Python (Notch/muesca para red eléctrica, pasa-banda FIR/IIR para deriva e interferencias) y analizar la respuesta en frecuencia/fase sin distorsionar la morfología del complejo QRS.

* **Base de datos:**  
  PhysioNet (*MIT-BIH Noise Stress Test Database* / *MIT-BIH Arrhythmia Database*).

---

### Propuesta 2: Detección Automática del Complejo QRS y Análisis de Variabilidad de la Frecuencia Cardíaca (HRV)

* **Problema biomédico:**  
  La identificación precisa del intervalo R-R es fundamental para la detección de arritmias y la evaluación del sistema nervioso autónomo.

* **Enfoque técnico (Señales y Sistemas):**  
  Implementar un algoritmo de detección de picos R (basado en derivación, filtrado y umbralización adaptativa tipo Pan-Tompkins). Posterior análisis espectral de la serie R-R mediante Transformada Rápida de Fourier (FFT) y Densidad Espectral de Potencia (PSD).

* **Base de datos:**  
  PhysioNet (*MIT-BIH Arrhythmia Database*).

---

### Propuesta 3: Caracterización y Clasificación Morfométrica de Contracciones Ventriculares Prematuras (PVC)

* **Problema biomédico:**  
  Las extrasístoles ventriculares presentan una morfología del complejo QRS alterada y ensanchada respecto a los latidos sinusales normales, requiriendo caracterización objetiva.

* **Enfoque técnico (Señales y Sistemas):**  
  Segmentación temporal de latidos, extracción de características en el dominio del tiempo (duración del QRS, amplitud) y de la frecuencia (energía en bandas / FFT / Wavelet) para diferenciar latidos normales de patológicos.

* **Base de datos:**  
  PhysioNet (*MIT-BIH Arrhythmia Database*).

---

## 3. Metodología de Discusión Interna

* **Herramientas empleadas:**  
  Lluvia de ideas (*Brainstorming*) y análisis causa-efecto (*Diagrama de Ishikawa*) para definir el origen de las interferencias y evaluar la factibilidad matemática de cada propuesta.

* **Control de versiones:**  
  Repositorio en GitHub y entorno ejecutable en Python.

---

## 4. Registro de Validación con el Tutor Asignado

* **Idea elegida para el proyecto:** [ A completar en la reunión de la Semana 11 ]

* **Observaciones y alcance acordado:** [ A completar con el Tutor ]

* **Fecha de aprobación:** ____ / ____ / 2026
