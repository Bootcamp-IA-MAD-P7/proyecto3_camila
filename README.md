# Spotify EDA Project 🎵

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre un conjunto de datos de Spotify para descubrir patrones, tendencias y características de las canciones.

---

## 📂 Estructura del Proyecto

A continuación se detalla la organización de los archivos y carpetas dentro de este repositorio:

| Carpeta / Archivo | Descripción |
| :--- | :--- |
| 📁 **`data/`** | Contiene los datasets en formato CSV utilizados para el análisis de Spotify. |
| 📁 **`imagenes/`** | Almacena las gráficas, mapas de calor y capturas exportadas del EDA. |
| 📁 **`notebooks/`** | Contiene los Jupyter Notebooks (`.ipynb`) con el código y desarrollo paso a paso. |
| 📄 **`.gitignore`** | Configuración para evitar subir archivos temporales o basura a GitHub. |
| 📄 **`requirements.txt`** | Lista con las librerías de Python y versiones necesarias para correr el proyecto. |
| 📄 **`README.md`** | Portada y documentación principal del proyecto (este archivo). |

---

## 📊 Estructura y Fases del EDA

El análisis se desarrolló de manera estructurada en el notebook siguiendo el siguiente flujo de trabajo:

| Fase del Análisis | Objetivos y Tareas Realizadas |
| :--- | :--- |
| 🔍 **1. Carga y Exploración Inicial** | Importación del dataset, revisión de dimensiones (`shape`), tipos de datos (`info`) y primer vistazo a los registros (`head`). |
| 🛠️ **2. Limpieza de Datos** | Identificación y manejo de valores nulos o duplicados. Ajuste de formatos y filtrado de datos atípicos si aplica. |
| 📈 **3. Análisis Estadístico Descriptivo** | Cálculo de medias, medianas, desviaciones estándar (`describe`) para entender la distribución de variables como popularidad, duración o *tempo*. |
| 🎨 **4. Visualización de Datos (Gráficos)** | Creación de histogramas, diagramas de caja (*boxplots*) y gráficos de dispersión para ver el comportamiento de las canciones. |
| 🔗 **5. Análisis de Correlación** | Construcción de una matriz y mapa de calor (*heatmap*) para descubrir la relación entre variables (ej. si la energía influye en la bailabilidad). |
| 💡 **6. Conclusiones** | Resumen con los hallazgos más importantes sobre qué hace que una canción sea exitosa en Spotify. |

---

## 🛠️ Tecnologías y Librerías Utilizadas

Para este análisis exploratorio se utilizaron las siguientes herramientas del ecosistema de Python:
* **Pandas**: Para la carga, manipulación y limpieza de los datos musicales.
* **NumPy**: Para el soporte de operaciones matemáticas y manejo de matrices/vectores.
* **Matplotlib**: Para la creación de gráficos estadísticos y visualizaciones básicas.
* **Seaborn**: Para la generación de gráficos avanzados, mapas de calor y visualizaciones estilizadas.
* **Jupyter Notebook**: Como entorno de desarrollo interactivo.

---

## 🚀 Cómo Inicializar el Proyecto

Para replicar este análisis en tu computadora local, sigue estos pasos detallados:

### Paso 1: Clonar el repositorio
Abre tu terminal (Git Bash, CMD o la terminal de VS Code) y descarga una copia exacta de este proyecto a tu computadora usando el comando:
```bash
git clone URL_DE_TU_REPOSITORIO_DE_GITHUB
