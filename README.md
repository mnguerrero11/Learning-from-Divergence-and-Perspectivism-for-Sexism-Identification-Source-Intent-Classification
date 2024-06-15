# Detección y Categorización de Mensajes Sexistas con Deep Learning y Aprendizaje con Desacuerdo
Manuel Guerrero García - Trabajo de Fin de Grado - Ingeniería Informática


Este repositorio contiene todo el trabajo realizado para el Trabajo Fin de Grado  **"Detección y Categorización, según su Intención, de Mensajes de Contenido Sexista Mediante Técnicas de Deep Learning y Aprendizaje con Desacuerdo"** por Manuel Guerrero García, presentado en la Universidad de Huelva en 2024.

## Contenido del Repositorio

### Estructura de Directorios

- **data/**: Contiene los conjuntos de datos utilizados para el entrenamiento y la evaluación de los modelos.
- **notebooks/**: Incluye todos los Jupyter notebooks utilizados durante el desarrollo del proyecto.
- **results/**: Resultados obtenidos tras la evaluación de los modelos.
- **scripts/**: Scripts de utilidad para preprocesamiento de datos y entrenamiento de modelos.
- **docs/**: Documentación adicional del proyecto.

### Descripción de los Jupyter Notebooks

1. **01_Data_Preprocessing.ipynb**: Notebook que contiene el preprocesamiento de los datos iniciales.
2. **02_Exploratory_Data_Analysis.ipynb**: Análisis exploratorio de los datos.
3. **03_Model_Training_v1.ipynb**: Entrenamiento del primer modelo utilizando una arquitectura básica.
4. **04_Model_Training_v2.ipynb**: Entrenamiento del segundo modelo utilizando una arquitectura mejorada con técnicas de aprendizaje por transferencia.
5. **05_Model_Evaluation.ipynb**: Evaluación de los modelos entrenados y análisis de resultados.
6. **06_Ensemble_Methods.ipynb**: Implementación y evaluación de métodos de ensamble.

### Conjuntos de Datos

- **Original Training Set**: Conjunto de datos original utilizado para el entrenamiento.
- **Original Dev Set**: Conjunto de datos de desarrollo para validación.
- **Translated Data**: Conjunto de datos traducidos del inglés al español y viceversa.
- **Augmented Data**: Conjunto de datos aumentado mediante técnicas de backtranslation y eliminación de filas clasificadas como NO.
- **Test Sets**: Conjuntos de datos de prueba utilizados para la evaluación final.

### Modelos Utilizados

1. **v1.1**: Modelo clasificador binario inicial.
2. **v1.2**: Modelo mejorado con aprendizaje por transferencia utilizando DeBERTa y RoBERTa.
3. **v2.1**: Modelo multiidioma con técnicas avanzadas de preprocesamiento y regularización.
4. **v2.2**: Ensamble de seis modelos diferentes.
5. **v2.3**: Ensamble de tres modelos optimizados.

### Resultados

Los resultados de la competición se encuentran en la carpeta `results/`, incluyendo los archivos de predicción y los informes de evaluación.
