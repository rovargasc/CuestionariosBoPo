# Comparación Detallada de Rendimiento y Resultados en Estudios de Deserción

## Aspectos Generales

| Característica | López & Macías (2018) | Rivera et al. (2021) | Fandiño (2022) | Madrid (2017) |
|----------------|---------------------|-------------------|----------------|--------------|
| Objetivo principal | Analizar tiempo hasta deserción | Clasificar y predecir deserción | Predecir deserción por programa | Clasificar estudiantes en riesgo de deserción |
| País/Región | Colombia | Colombia (U. Andes) | Colombia (Konrad Lorenz) | Colombia (UNAL Medellín) |
| Población | Estudiantes PEAMA | Estudiantes Ing. Eléctrica | 6 programas pregrado | Todos los programas pregrado |
| Periodo de estudio | 2008-I a 2018-I | 2010-I a 2021-I | 2014-I a 2020-I | 2009-I a 2016-I |

## Modelos Utilizados

| López & Macías (2018) | Rivera et al. (2021) | Fandiño (2022) | Madrid (2017) |
|---------------------|-------------------|----------------|--------------|
| - Modelo logístico de riesgo discreto | - **Random Forest** | - **Random Forest** | - Máquinas Vector Soporte (SVM) |
| - Análisis supervivencia | - MultiLayer Perceptron | - Regresión Logística | - Análisis Discriminante (AD) |
| | | - Support Vector Machines | - **K-vecinos más próximos (KNN)** |
| | |  | - Regresión Logística (RL) |

## Rendimiento por Modelo y Periodo

### Madrid (2017)
**Primer Semestre:**
- **KNN:** Mejor modelo para Facultades de Arquitectura, Ciencias y Ciencias Agrarias
  - Sensibilidad: 39-44%
  - Tasa error: 26-33%
- **AD:** Mejor para Facultad de Minas
  - Sensibilidad: 34.57%
  - Tasa error: 25.26%

**Segundo Semestre:**
- **SVM:** Mejor para Arquitectura
  - Sensibilidad: 57.14%
  - Especificidad: 99.24%
  - Tasa error: 1.86%
- **AD:** Mejor para Ciencias y Ciencias Agrarias
  - Sensibilidad: 67-70%
  - Tasa error: 15-19%

**Tercer Semestre:**
- **SVM:** Mejor para varias facultades
  - Sensibilidad: 42-66%
  - Tasa error: 0.4-8.7%
- **AD:** Destacado en algunas facultades
  - Sensibilidad: hasta 66.67%

### Fandiño (2023)
**Random Forest:**
- Accuracy: 99%
- Precision: 99%
- Recall: 99%
- F1-Score: 99%
- AUC: 99%
- Kappa: 98%

### Rivera et al. (2021)
**Random Forest:**
- Accuracy: ~0.7-0.8
- Precisión: >0.8
- Recall: 0.6-0.7
- F1-Score: ~0.7

## Variables Más Influyentes

### Madrid (2017)
- Resultados examen admisión
- PAPA (Promedio Académico)
- Nivelación en Matemáticas Básicas
- Variables socioeconómicas
- Factores individuales (edad, género, estado civil)

### Fandiño (2023)
- Promedio académico
- No renovación matrícula
- Pérdida de cuatro asignaturas
- Notas específicas por programa

### Rivera et al. (2021)
- Créditos intentados/aprobados
- Promedios por área
- Influencia de profesores
- Variables socioeconómicas

## Características Distintivas por Estudio

### Madrid (2017)
- Análisis por facultad y semestre
- Comparación exhaustiva de modelos
- Evaluación temporal (3 semestres)
- Énfasis en sensibilidad como métrica clave
- Identificación de patrones por facultad

### Fandiño (2023)
- Arquitectura en nube
- Automatización de procesos
- Alto rendimiento general
- Enfoque por programa

### Rivera et al. (2021)
- Predicción temporal
- Análisis de influencia docente
- Estabilidad en predicciones

## Conclusiones Principales sobre Rendimiento

### Madrid (2017)
- Regresión Logística mostró el peor desempeño
- Rendimiento varía significativamente por facultad
- Mejor predicción en segundo semestre
- SVM y AD mostraron mejor desempeño general
- 64% de deserción ocurre en primer semestre

### Fandiño (2023)
- Random Forest mostró rendimiento superior
- Consistencia en todas las métricas
- Efectividad en todos los programas

### Rivera et al. (2021)
- Estabilidad en predicciones temporales
- Buen balance entre métricas
- Efectividad en identificación temprana

## Innovaciones Metodológicas

### Madrid (2017)
- Análisis segmentado por facultad
- Evaluación temporal progresiva
- Comparación exhaustiva de modelos
- Enfoque en sensibilidad como métrica clave

### Fandiño (2023)
- Implementación en nube
- Procesamiento automatizado
- Escalabilidad del sistema

### Rivera et al. (2021)
- Análisis de influencia docente
- Predicción temporal adaptativa
- Enfoque en variables académicas







#_________________________________________________________________________
# Análisis Comparativo Actualizado de Estudios sobre Deserción Estudiantil

## Aspectos Generales

| Característica | Mduma (2023) | López & Macías (2018) | Rivera et al. (2021) |
|----------------|--------------|---------------------|-------------------|
| Objetivo principal | Mejorar predicción usando técnicas de balanceo | Analizar tiempo hasta deserción con modelos de supervivencia | Clasificar y predecir deserción usando ML |
| País/Región | Tanzania e India | Colombia | Colombia (U. Andes) |
| Población | Estudiantes general | Estudiantes PEAMA | Estudiantes Ing. Eléctrica/Electrónica |
| Periodo de estudio | Datos 2015-2016 | 2008-I a 2018-I | 2010-I a 2021-I |

## Metodología

### Modelos Utilizados

| Mduma (2023) | López & Macías (2018) | Rivera et al. (2021) |
|--------------|---------------------|-------------------|
| - Regresión Logística | - Modelo logístico de riesgo discreto | - Random Forest |
| - Random Forest | - Análisis de supervivencia en tiempo discreto | - MultiLayer Perceptron |
| - Multi-Layer Perceptron | | - Logistic Regression |

### Técnicas de Balanceo de Datos

| Mduma (2023) | López & Macías (2018) | Rivera et al. (2021) |
|--------------|---------------------|-------------------|
| - Random Over Sampling (ROS) | No aplica técnicas de balanceo | - Stratified K Fold |
| - Random Under Sampling (RUS) | | |
| - SMOTE | | |
| - SMOTE con ENN | | |
| - SMOTE con Tomek links | | |

## Métricas de Evaluación

| Mduma (2023) | López & Macías (2018) | Rivera et al. (2021) |
|--------------|---------------------|-------------------|
| - Geometric Mean (Gm) | - Función de riesgo discreta | - Accuracy |
| - F-measure (Fm) | - Criterio de información AIC | - Precision |
| - Adjusted Geometric Mean (AGm) | - Residuales deviance | - Recall |
| - Matriz de confusión | | - F1-Score |
| | | - Matriz de confusión |

## Variables Consideradas

### Mduma (2023)
- Variables socioeconómicas
- Variables académicas
- Ratios institucionales

### López & Macías (2018)
- Género
- Estrato socioeconómico
- Sede de origen
- Cambio de sede
- Tiempo (semestres)

### Rivera et al. (2021)
- Variables académicas (créditos intentados/aprobados, promedios por áreas)
- Variables socioeconómicas (ingreso hogar, estrato)
- Variables individuales (ciudad origen, nivel educativo padres)
- Información sobre profesores
- Variables temporales

## Principales Hallazgos

### Mduma (2023)
- SMOTE-ENN logró el mejor desempeño en clasificación
- La Regresión Logística clasificó correctamente el mayor número de desertores
- El balanceo de datos mejoró significativamente la predicción de la clase minoritaria

### López & Macías (2018)
- El riesgo de deserción disminuye con el tiempo pero aumenta en semestres finales
- Los hombres presentan mayor riesgo de deserción
- El cambio de sede tiene efectos variables según sede de origen
- El estrato socioeconómico bajo actúa como factor protector en algunas sedes

### Rivera et al. (2021)
- Random Forest mostró el mejor desempeño entre los modelos evaluados
- Los descriptores académicos son altamente relevantes para la clasificación
- La deserción es más alta en primeros 4 semestres y semestres 9-10
- Los profesores tienen influencia significativa en primeros semestres
- El modelo mantiene buen accuracy (>0.7) incluso prediciendo hasta 7 semestres antes

## Enfoques Innovadores por Estudio

### Mduma (2023)
- Uso extensivo de técnicas de balanceo de datos
- Comparación sistemática de métodos de balanceo
- Enfoque en mejorar predicción de clase minoritaria

### López & Macías (2018)
- Análisis longitudinal del tiempo hasta deserción
- Consideración de cambios de sede
- Uso de modelos de supervivencia

### Rivera et al. (2021)
- Predicción temporal (k-t semestres hacia atrás)
- Análisis detallado de influencia de profesores
- Uso de Stratified K-Fold para mantener proporciones
- Feature importance analysis por periodo

## Similitudes Clave entre Estudios
1. Uso de Regresión Logística y Random Forest como modelos base
2. Consideración de factores académicos y socioeconómicos
3. Énfasis en primeros semestres como críticos para deserción
4. Uso de matrices de confusión para evaluación

## Diferencias Principales
1. Tratamiento del desbalance de datos
2. Temporalidad del análisis
3. Especificidad de la población estudiada
4. Métricas de evaluación empleadas
