# Clasificación Multiclase con Dataset Diamonds

Proyecto de machine learning enfocado en la predicción de la calidad del corte (cut) de diamantes utilizando modelos de clasificación multiclase.

## Objetivo

Predecir la variable `cut` (corte) de un diamante utilizando modelos de clasificación multiclase implementados con Scikit-Learn y TensorFlow/Keras.

## Dataset

El proyecto utiliza el dataset **Diamonds** disponible en la librería Seaborn, que contiene 53,940 registros con las siguientes características:

**Variables numéricas:**
- `carat`: Peso del diamante en quilates
- `depth`: Porcentaje de profundidad
- `table`: Ancho de la tabla del diamante
- `price`: Precio en dólares
- `x`, `y`, `z`: Dimensiones del diamante (largo, ancho, profundidad)

**Variables categóricas:**
- `cut`: Calidad del corte (Ideal, Premium, Very Good, Good, Fair)
- `color`: Color del diamante (D, E, F, G, H, I, J)
- `clarity`: Claridad del diamante (IF, VVS1, VVS2, VS1, VS2, SI1, SI2, I1)

## Requisitos

- Python 3.8+
- Pandas 2.2.2
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- TensorFlow 2.19.0

## Estructura del Proyecto

```
machine-learning/
├── actividad_4/
│   ├── diamonds_clasificacion_multiclase.ipynb
│   └── Actividad_4_clasificacion_multiclase_diamonds_ed.pdf
└── README.md
```

## Contenido del Notebook

El notebook `diamonds_clasificacion_multiclase.ipynb` incluye:

1. **Importación de Librerías**: Configuración inicial con todas las herramientas necesarias
2. **Carga y Estadísticas Descriptivas**: Exploración inicial del dataset
3. **Limpieza de Datos**:
   - Detección de valores nulos
   - Verificación de tipos de datos
   - Eliminación de duplicados
   - Identificación y tratamiento de outliers
4. **Análisis Exploratorio de Datos (EDA)**:
   - EDA univariante: Distribución de variables individuales
   - EDA bivariante: Relaciones entre variables
   - EDA multivariante: Análisis de correlaciones complejas
5. **Modelado**: Implementación de modelos de clasificación multiclase (en desarrollo)

## Cómo Ejecutar

1. Clonar o descargar el repositorio
2. Navegar al directorio `actividad_4/`
3. Abrir el notebook con Jupyter Notebook o JupyterLab:
   ```bash
   jupyter notebook diamonds_clasificacion_multiclase.ipynb
   ```
4. Ejecutar las celdas secuencialmente

## Resultados

El proyecto proporciona:
- Análisis completo de calidad del corte de diamantes
- Visualizaciones detalladas de distribuciones y correlaciones
- Comparación entre diferentes modelos de clasificación
- Métricas de evaluación de rendimiento
