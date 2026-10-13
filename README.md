# TPI.SYS

# Guía Metodológica del Trabajo Práctico Integrador (TPI)

Asignatura: Señales y Sistemas - Bioingeniería (Plan 2026)  
Período de ejecución: Segundo Bloque (Semanas 11 a 15)

---

## 1. Fundamentación y enfoque pedagógico

El Trabajo Práctico Integrador (TPI) se estructura bajo la modalidad de Aprendizaje Basado en Proyectos (ABP). El objetivo no es solo la aplicación técnica de herramientas de procesamiento de señales, sino el desarrollo de competencias transversales de ingeniería: identificación de problemas reales, trabajo colaborativo, gestión del tiempo y comunicación efectiva.

Se busca simular un entorno de I+D (Investigación y Desarrollo) biomédico, donde los estudiantes deben transitar desde una necesidad o problema clínico/biológico hacia una solución tecnológica validada mediante procesamiento digital.

---

## 2. Conformación de grupos y dinámica de roles

Considerando la complejidad del análisis y la necesidad de discusión teórica profunda:

- Integrantes: los grupos estarán conformados por 7 a 8 estudiantes (excepcionalmente 10, sujeto a aprobación de la cátedra).
- Asignación de roles: para optimizar las discusiones y evitar el trabajo desarticulado, se sugiere la asignación y rotación de roles internos sugeridos por la metodología de cátedra:

1. Moderador/Coordinador: organiza las reuniones, asegura que todos participen en la lluvia de ideas y mantiene el foco en los objetivos semanales.
2. Responsable Técnico (Lead Coder): centraliza la estructura del código en Python y asegura buenas prácticas (uso de repositorios, librerías estándar).
3. Analista/Documentador (Scribe): registra las decisiones tomadas, gestiona la búsqueda de bibliografía y la redacción de informes de avance.

> Nota: aunque existan roles, todos los integrantes deben dominar los conceptos teóricos y la implementación del código. La defensa es individual dentro del grupo.

---

## 3. Herramientas de gestión y discusión

Se exigirá el uso de herramientas metodológicas para la definición del problema (discutidas en la Clase de Aplicaciones de la Semana 10):

- Lluvia de ideas (Brainstorming): divergencia inicial para proponer múltiples enfoques.
- Diagrama de Ishikawa (Espina de Pescado): para analizar causa-efecto al definir el problema biomédico (por ejemplo: ¿por qué la señal tiene ruido? ¿Es fisiológico, de instrumentación o de entorno?).
- Gestión de versiones: uso obligatorio de entorno Python y recomendación de Git/GitHub para el trabajo colaborativo.

---

## 4. Cronograma de hitos y entregables

El TPI se desarrolla en 4 etapas obligatorias con entregables definidos. El incumplimiento de un hito impide avanzar al siguiente.

### HITO 1: Definición y selección del problema

- Fecha: Semana 11 (durante la clase de práctica post-teoría de aplicaciones)
- Actividad:
  - Basado en la clase teórica de aplicaciones (ECG, EEG, Voz, etc.), el grupo debe generar 3 ideas/problemas potenciales.
  - Discusión con el tutor asignado sobre la viabilidad, alcance y disponibilidad de datos (bases de datos como PhysioNet o adquisiciones propias).
- Entregable: documento breve (1 carilla) describiendo las 3 ideas.
- Resultado: selección de 1 idea final validada por el tutor.

### HITO 2: Propuesta de implementación

- Fecha: Semana 12
- Actividad:
  - Diseño del diagrama en bloques del sistema propuesto.
  - Definición matemática de las herramientas a usar (tipos de filtros, transformadas, operaciones de convolución, etc.).
- Entregable digital:
  - Documento breve (2 carillas) conteniendo:
    - diagrama de flujo/bloques de la solución propuesta
    - justificación teórica de los métodos elegidos y referencias bibliográficas
    - link a la base de datos o descripción del protocolo de adquisición
- Resultado: propuesta ajustada final validada por el tutor.

### HITO 3: Prototipo funcional (MVP)

- Fecha: Semana 14
- Actividad:
  - Demostración de código en Python funcionando.
  - El sistema debe ser capaz de cargar la o las señales, procesarlas (filtros/transformadas) y mostrar resultados preliminares.
- Entregable:
  - Notebook de Python (Jupyter/Colab) o script ejecutable.
  - Visualización de resultados preliminares (gráficos de entrada vs. salida, espectros, etc.).
- Instancia de control: revisión de código con el tutor para corregir errores conceptuales antes de la defensa final.

### HITO 4: Defensa final y cierre

- Fecha: Semana 15
- Formato: defensa pública (15-20 minutos por grupo)
- Requisitos:
  - presentación oral con soporte visual
  - demostración en vivo del procesamiento (si aplica) o resultados estáticos analizados críticamente
  - defensa individual: cada integrante responderá preguntas conceptuales sobre las decisiones tomadas (por ejemplo: “¿Por qué usaste un filtro IIR y no FIR?”, “¿Qué representa la fase en tu señal biológica?”)

---

## 5. Rúbrica de evaluación del TPI

La nota del TPI se compone de la siguiente matriz ponderada (total 100%):

| Dimensión | Peso | Criterios de evaluación |
| --- | ---: | --- |
| Proceso metodológico | 25% | Cumplimiento de hitos en fecha (Semanas 11, 12, 13). Uso de herramientas de gestión (Ishikawa, roles). Participación activa en consultas con el tutor. |
| Calidad técnica (código) | 25% | Código Python funcional, ordenado y comentado. Uso correcto de librerías (SciPy, NumPy). Correcta implementación de algoritmos vistos en la materia. |
| Dominio conceptual | 35% | Justificación teórica sólida. Capacidad de vincular el resultado matemático con el fenómeno fisiológico/biológico. Respuestas individuales en la defensa. |
| Comunicación y resultados | 15% | Claridad en la exposición oral. Calidad de los gráficos y visualizaciones. Capacidad de síntesis y conclusiones críticas. |

---

## 6. Consideraciones para alumnos

1. Autonomía: los docentes actúan como facilitadores/tutores. Se espera que los grupos investiguen bibliografía complementaria para problemas específicos.
2. Datos reales: se valorará positivamente el uso de señales reales (propias o de bases de datos) por sobre señales sintéticas simuladas exclusivamente.
3. Tutorías: cada grupo tendrá asignado un docente tutor. Es responsabilidad del grupo aprovechar las horas de práctica de las semanas 10 a 13 para validar avances.
4. Trabajo colaborativo: la evaluación no se limita al resultado final, sino también a la forma en que el grupo organiza, documenta y avanza en conjunto.
5. Defensa individual: la comprensión profunda del proyecto es un criterio central. Cada integrante debe poder explicar claramente el fundamento técnico y matemático de la solución.

---

## 7. Objetivo general del TPI

El TPI busca que el estudiante logre:

- identificar un problema real en bioingeniería
- definir una estrategia de análisis basada en señales
- aplicar herramientas de procesamiento digital adecuadas
- interpretar resultados en contexto clínico o biológico
- comunicar de manera clara y técnica la propuesta y sus conclusiones

---

## 8. Recomendación para comenzar

Se recomienda iniciar por:

1. definir 3 ideas de proyecto posibles
2. evaluar viabilidad, disponibilidad de datos y complejidad
3. seleccionar una propuesta con alcance realista
4. documentar la idea con un esquema de bloques y una justificación técnica
5. preparar la base de datos y el entorno de Python para la implementación del MVP

---

## 9. Cierre

El trabajo práctico integrador no se reduce a “hacer un filtro” o “graficar una señal”. Su valor pedagógico radica en la capacidad de transformar un problema biomédico en una estrategia de análisis y validación basada en señales, con rigor matemático, criterio técnico y una mirada crítica sobre los resultados.

Este documento funciona como guía metodológica para orientar la planificación, el desarrollo y la defensa del proyecto durante el segundo bloque académico.
