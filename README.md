# Tarea: Introdución a la Optimización - Analítica Social e Inteligencia Estratégica

**Estudiante:** Nicolás Silva Andujar  
**Código:** 20200832  
**Carrera:** Ciencia Política y Gobierno  

En esta tarea, aplicamos métodos de **Optimización, Análisis de Jerarquía Analítica (AHP) y Benchmarking** para la toma de decisiones estratégicas en situaciones complejas. La tarea se distribuye así en tres partes.

**Enlace a la tarea**: https://nicosil02.github.io/Optimization_Intro/Intro_To_Optimization.html
----------------------------

## Parte 1: Optimización

En este apartado resolvemos dos ejercicios de maximización y minimiación para casos hipotéticos.

* [Ejercicio 1 Indicaciones](https://docs.google.com/presentation/d/e/2PACX-1vTSq9X74urGAB_5n_MIJ9ZGIboKSvBdokVTBXVLh_qqZnmLRTJioOF431Rzys3Qi9UaFwWXjeq6Wmd5/embed?start=false&loop=false&delayms=3000)


* [Ejercicio 2: Indicaciones](https://docs.google.com/presentation/d/e/2PACX-1vQtBRpIr6Hx1_T0zJ3_DRqsE82YUjx7ZkeEKLdA64fbjtjkmc6Ibf6ebzp6CY69D482IGpG2h9GcsC5/embed?start=false&loop=false&delayms=3000)


--------------------
## Parte 2: Multicriteria Decision Making.

En este apartado resolvemos un problema para seleccionar el país más viable para realizar estudios de maestria

Los países a analizar son:

* Brasil
* Canadá
* EE.UU.
* Reino Unido

**Criterios para la elección**

| Criterio                  | Descripción                                                                                             |
|---------------------------|---------------------------------------------------------------------------------------------------------|
| **Costo de Vida**         | Evalúa el costo aproximado para mantener un nivel de vida cómodo en el país de estudio, incluyendo gastos de vivienda, alimentación, transporte y otros. Un costo de vida alto puede requerir recursos adicionales o becas para cubrir los gastos. La información proviene de [Expatistan](https://www.expatistan.com/es/costo-de-vida/pais/ranking) |
| **Dificultad del Idioma** | Mide la facilidad o dificultad de aprendizaje y uso del idioma del país, en el contexto de estudios y vida cotidiana. Este criterio incluye la capacidad para entender el material académico y comunicarse de manera eficaz en el entorno local. |
| **Posibilidad de Estudios Post-Maestría** | Examina la disponibilidad y accesibilidad de programas de doctorado o estudios avanzados en el país de estudio, así como la existencia de oportunidades de investigación o financiamiento. Un país con buenas posibilidades permite una continuidad académica sin necesidad de emigrar nuevamente. La información proviene de [Synergie](https://www.synergie.es/trabajar-en-extranjero/) |



------------------------------
## Parte 3: Benchmarking

En este apartado, se han seleccionado municipalidades con características comunes en términos de **Población, ingresos totales, sectores en los que los serenazgos realizan seguimiento, Gastos totales, porcentaje de victimización e infraestructura para seguridad ciudadana**. En base a estas características se han seleccionado **8** municipalidades.


**Variables**
| **Categoría** | **Variable**                 | **Descripción**                                                        |
|---------------|------------------------------|------------------------------------------------------------------------|
| **Inputs**    | Ingresos                     | Recursos financieros del distrito.                                     |
|   **Inputs**             | Sectores_t                   | Número de sectores o áreas en los que se realiza seguimiento operativo.|
| **Outputs**   | Gastos                       | Monto total de gasto ejecutado en el distrito.                         |
|   **Outputs**            | Porcentaje de Victimización   | Proporción de personas que han sido víctimas de delitos en el distrito.|
|     **Outputs**          | Infra                         | Disponibilidad de infraestructura relevante (ej. puestos de serenazgo o comisarías). |


Con estas características se ha medido la eficiencia entre las municipalidades homogéneas.


**Municipalidades y características**
| Distrito              | Ingresos           | Sectores_t | Infra | Gastos           | Porcentaje Victimización | Población |
|-----------------------|--------------------|------------|-------|------------------|--------------------------|-----------|
| CHORRILLOS            | 158,955,561.68    | 4.00       | 31.00 | 136,398,031.24  | 15.62                     | 373.55    |
| SULLANA               | 160,136,371.26    | 6.00       | 1.00  | 147,215,512.70  | 31.25                     | 195.02    |
| TORATA                | 150,530,385.41    | 45.00      | 0.00  | 113,920,401.53  | 12.50                     | 7.89      |
| HUANCAYO              | 149,930,722.83    | 4.00       | 10.00 | 119,763,095.16  | 12.50                     | 125.65    |
| CAYMA                 | 149,830,383.08    | 11.00      | 2.00  | 85,561,574.87   | 15.62                     | 110.22    |
| SAN MARTIN DE PORRES  | 145,409,912.79    | 18.00      | 7.00  | 156,226,225.89  | 20.83                     | 794.84    |
| SAN SEBASTIAN         | 140,761,077.44    | 7.00       | 5.00  | 83,604,252.36   | 25.00                     | 142.03    |
| IQUITOS               | 129,733,420.60    | 4.00       | 12.00 | 130,819,688.05  | 12.50                     | 155.68    |






