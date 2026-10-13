#  Cronograma del Proyecto

## Diagrama de Gantt

```mermaid
gantt
    title Cronograma del Proyecto - Procesamiento de Señales
    dateFormat  YYYY-MM-DD
    excludes    weekends

    section Hito 1 - Definición
    Generación de 3 ideas / problemas      :t11, 2026-04-01, 3d
    Discusión con Tutor (Viabilidad/Datos) :t12, after t11, 2d
    Hito 1 - Entregable: Documento 1 carilla :milestone, h1, after t12, 0d

    section Hito 2 - Propuesta
    Diagrama de bloques y justificación    :t21, after h1, 4d
    Definición matemática y base de datos  :t22, after t21, 3d
    Hito 2 - Entregable: Documento 2 carillas :milestone, h2, after t22, 0d

    section Hito 3 - MVP
    Desarrollo en Python (Filtros/Transformadas) :t31, after h2, 7d
    Visualización de resultados preliminares     :t32, after t31, 3d
    Hito 3 - Entregable: Notebook / Script       :milestone, h3, after t32, 0d

    section Hito 4 - Defensa
    Preparación de presentación y gráficos :t41, after h3, 4d
    Hito 4 - Defensa Final y Cierre (Semana 15) :milestone, h4, after t41, 0d
    Planificación                           :g1, 2026-04-01, 5d
    Seguimiento y Control                   :g2, after g1, 45d
    Cierre del Proyecto                     :g3, after t32, 3d
