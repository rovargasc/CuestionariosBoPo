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
