# 🚀 **Manual Introductorio a Ciencia de Datos**

---

## 🎯 **Objetivo de la actividad**

El objetivo principal de esta actividad es que los estudiantes pongan en práctica las técnicas de **preprocesamiento y exploración de datos** utilizando Python, Pandas y Matplotlib/Seaborn. A través de la creación de un repositorio en GitHub, se busca que desarrollen un manual o guía que les sirva como referencia para futuros proyectos. Este manual consolidará los conocimientos adquiridos en clase sobre la preparación de datos, una fase crítica en cualquier proyecto de ciencia de datos.

## 📖 **Instrucciones**

1.  **Crea un repositorio en GitHub:** Nombralo de forma descriptiva, por ejemplo, `Data_Prep_Manual` o `Manual_Ciencia_Datos` + nombre_equipo. Pueden generar tu repositorio a partir de otro para que VS incluya las extensiones necesarias.

2.  **Estructura del repositorio:**
    * **Archivo `README.md`**: Crea un archivo `README.md` en la raíz del repositorio. Este archivo debe servir como la página de inicio del manual. Debe incluir una breve descripción del proyecto, el objetivo, las herramientas utilizadas y un índice claro que enlace a los diferentes cuadernos de Jupyter. Utiliza celdas de markdown para formatear el texto.
    * **Cuadernos de Jupyter (`.ipynb`)**: Crea uno o más cuadernos de Jupyter para abordar los temas de la lista. Puedes agrupar los temas de la manera que consideres más lógica. Por ejemplo, puedes tener un cuaderno para "Limpieza y Tipos de Datos" y otro para "Análisis Exploratorio de Datos (EDA)", pero puedes generar los que consideres conveniente. Cada cuaderno debe:
        * Tener celdas de **markdown** para explicar el concepto teórico de cada paso (por ejemplo, ¿qué es un valor nulo y por qué es importante manejarlo?).
        * Tener celdas de **código** funcionales y bien comentadas que demuestren cómo aplicar las técnicas.
        * Incluir los archivos de datos (`.csv`, `.xlsx`) que uses. Puedes usar datos que ya hemos revisado en clase o encontrar otros conjuntos de datos interesantes en plataformas como Kaggle. 

3.  **Contenido del manual**: Asegúrate de que tu manual cubra al menos los siguientes temas:

    * **Lectura de archivos con Pandas**: Ejemplos de cómo leer datos de diferentes formatos (`.csv`, `.xlsx`).
    * **Exploración inicial del DataFrame**: Uso de métodos como `info()`, `describe()`, `head()`, `tail()`, `shape`, `columns`, `dtypes` para comprender la estructura de los datos.
    * **Conversión de tipos de datos**: Ejemplos prácticos de cómo convertir columnas a tipos de datos numéricos, categóricos o de fecha.
    * **Manejo de valores faltantes/nulos**: Detección (`isnull()`, `isna()`), conteo y explicación de las estrategias para manejarlos (eliminación, imputación, etc.).
    * **Limpieza de valores atípicos e inconsistencias**: Identificación y manejo de `outliers`.
    * **Manejo de renglones duplicados**: Cómo identificar y eliminar registros duplicados.
    * **Creación de nuevas columnas**: Ejemplos de cómo aplicar funciones a una o varias columnas para generar nuevas variables.
    * **Análisis Exploratorio de Datos (EDA)**:
        * **Filtros, ordenamiento, agrupamientos y agregaciones**: Ejemplos de uso de `loc`, `sort_values()`, `groupby()`, `agg()` para explorar los datos.
        * **Visualización de datos**: Incluye ejemplos de visualizaciones comunes para el EDA como histogramas, gráficas de líneas, `scatter plots`, `pair plots` y tablas de frecuencia.
    * **Cualquier otro tema que consideres relevante**: Siente la libertad de incluir otros temas que enriquezcan tu manual, como el manejo de datos de texto o el uso de *pivot tables*.

4.  **Entrega**: Una vez que el repositorio esté completo, sube el enlace a Canvas en la actividad asignada por el profesor. Asegúrate de que la última actualización del repositorio sea visible.

5.  Puedes encontrar más información sobre Markdown en https://www.markdownguide.org


## 📈 **Rúbrica de evaluación (20 puntos)**

---

| **Criterio de Evaluación** | **Puntos posibles** | **Puntuación obtenida** | **Comentarios** |
| :--- | :---: | :---: | :--- |
| **Estructura y Organización del Repositorio** | **3** | | |
| Repositorio en GitHub público y con un nombre descriptivo. | 1 | | |
| Archivo `README.md` completo, con descripción y índice claro. | 2 | | |
| **Contenido Técnico (Cuadernos de Jupyter)** | **12** | | |
| **1. Lectura de datos y exploración inicial:** | 2 | | |
| &nbsp; &nbsp; • Lectura de archivos y uso de `info()`, `describe()`, `head()`. | 2 | | |
| **2. Limpieza de datos:** | 4 | | |
| &nbsp; &nbsp; • Conversión de tipos de datos y manejo de valores faltantes. | 2 | | |
| &nbsp; &nbsp; • Limpieza de datos atípicos y manejo de renglones duplicados. | 2 | | |
| **3. Creación de nuevas variables:** | 2 | | |
| &nbsp; &nbsp; • Inclusión de al menos un ejemplo de creación de nuevas columnas. | 2 | | |
| **4. Análisis Exploratorio de Datos (EDA):** | 4 | | |
| &nbsp; &nbsp; • Uso de filtros, ordenamiento, agrupamientos y agregaciones. | 2 | | |
| &nbsp; &nbsp; • Visualización de datos (gráficas, tablas de frecuencia). | 2 | | |
| **Código y Explicaciones** | **5** | | |
| El código es funcional, legible y está bien comentado. | 3 | | |
| Las explicaciones en las celdas de markdown son claras y concisas. | 2 | | |
| **Total** | **20** | | |

---
