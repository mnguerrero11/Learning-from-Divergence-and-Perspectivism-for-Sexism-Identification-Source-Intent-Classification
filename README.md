---

# Detección y Categorización de Mensajes Sexistas con Deep Learning y Aprendizaje con Desacuerdo
Manuel Guerrero García - Trabajo de Fin de Grado - Grado en Ingeniería Informática

<p align="center">
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/huggingface-FFD14E?style=for-the-badge&logo=huggingface&logoColor=white" alt="HuggingFace">
  <img src="https://img.shields.io/badge/pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/google%20colab-F9AB00?style=for-the-badge&logo=google%20colab&logoColor=white" alt="Google Colab">
  <img src="https://img.shields.io/badge/optuna-6843A1?style=for-the-badge&logo=optuna&logoColor=white" alt="Optuna">
  <img src="https://img.shields.io/badge/GPU-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="GPU">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/latex-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX">
</p>

<p align="center">
  <img src="https://www.uhu.es/presentacion/uploads/img/UHU_Logo.png" alt="Universidad de Huelva" width="200">
  <img src="https://www.uhu.es/etsi/images/logo-etsi.png" alt="ETSI UHU" width="200">
</p>

Este repositorio contiene todo el trabajo realizado para el Trabajo Fin de Grado **"Detección y Categorización, según su Intención, de Mensajes de Contenido Sexista Mediante Técnicas de Deep Learning y Aprendizaje con Desacuerdo"** por Manuel Guerrero García, presentado en la Universidad de Huelva en 2024.

## Contenido del Repositorio

### Estructura de Directorios

- **data/**: Contiene los conjuntos de datos utilizados para el entrenamiento y la evaluación de los modelos.
- **notebooks/**: Incluye todos los Jupyter notebooks utilizados durante el desarrollo del proyecto.
- **results/**: Resultados obtenidos tras la evaluación de los modelos.
- **scripts/**: Scripts de utilidad para preprocesamiento de datos y entrenamiento de modelos.
- **docs/**: Documentación adicional del proyecto.

### Jupyter Notebooks de Modelos Utilizados

1. **v1.1**: Modelo clasificador binario inicial.
2. **v1.2**: Modelo mejorado con aprendizaje por transferencia utilizando DeBERTa y RoBERTa.
3. **v2.1**: Modelo multiidioma con técnicas avanzadas de preprocesamiento y regularización.
4. **v2.2**: Ensamble de seis modelos diferentes.
5. **v2.3**: Ensamble de tres modelos optimizados.

### Resultados

Los resultados de la competición se encuentran en la carpeta `results/`, incluyendo los archivos de predicción y los informes de evaluación.

## Tecnologías Utilizadas

- **Python**: Utilizado como el lenguaje de programación principal debido a su versatilidad y su amplio ecosistema de bibliotecas especializadas en aprendizaje automático y procesamiento de lenguaje natural.
- **Jupyter**: Herramienta empleada para crear y compartir documentos que contienen código en tiempo real, ecuaciones, visualizaciones y texto narrativo. Facilitó la experimentación y visualización de resultados y se empleó para ejecutar los cuadernos que entrenaban los modelos en el equipo del laboratorio I2C.
- **HuggingFace Transformers**: Biblioteca esencial para la implementación de modelos basados en Transformers, como BERT y RoBERTa, que se utilizaron para el procesamiento de lenguaje natural y la categorización de intenciones en tweets.
- **PyTorch**: Framework de aprendizaje profundo utilizado para la creación y entrenamiento de modelos de redes neuronales. Su flexibilidad y eficiencia fueron cruciales para ajustar y optimizar los modelos.
- **Google Colab**: Plataforma en la nube que proporciona acceso a unidades de procesamiento gráfico (GPU), específicamente la GPU NVIDIA T4. Esta GPU, con 16 GB de VRAM y soporte para Tensor Cores, aceleró significativamente las tareas de entrenamiento de modelos.
- **Optuna**: Utilizado para la optimización de hiperparámetros, permitiendo encontrar las configuraciones más eficientes para los modelos implementados, mejorando su rendimiento.
- **GPU del laboratorio "I2C"**: Adicionalmente, empleé la GPU GeForce RTX 4070, que se encuentra instalada en un equipo del laboratorio del grupo de investigación “I2C” de la Universidad de Huelva, para tareas de entrenamiento que requerían recursos computacionales intensivos.
- **GitHub**: Plataforma utilizada para el control de versiones y la organización de los cuadernos de Jupyter, código fuente y documentación del proyecto. Facilitó la colaboración y la gestión eficiente del desarrollo del proyecto.
- **LaTeX**: Sistema de composición de textos que permite crear documentos de alta calidad tipográfica, especialmente utilizados en la producción de documentos científicos y académicos.
