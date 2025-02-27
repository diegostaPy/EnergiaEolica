# Curso de Uso de Winrose para Análisis de Datos de Viento

Bienvenidos al curso de Uso de Winrose para el Análisis de Datos de Viento. Este curso está diseñado para introducir a los participantes en el uso de la herramienta Winrose, una librería de Python especializada en la visualización y análisis de datos de viento. A lo largo de este curso, aprenderemos a:

    Generar y trabajar con datos sintéticos de viento.

    Obtener y procesar datos reales de viento desde el portal NASA POWER.

    Analizar la tendencia y estacionalidad de los datos de viento.

    Extrapolar el viento a niveles más altos y comparar distribuciones de Weibull.

## Estructura del Repositorio

- `notebooks/`: Contiene el notebook de Google Colab con el código y ejemplos utilizados en el curso.

- `README.md`: Este archivo, que proporciona una descripción general del repositorio.

## Requisitos
- Python 3.x
- Jupyter Notebook o Google Colab
- Bibliotecas de Python:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scipy`
  - `windrose`
  - `requests`
  - `scikit-learn`
Instalar las dependencias:


pip install -r requirements.txt

## Uso

Los notebooks proporcionados en la carpeta notebooks/ están diseñados para ser ejecutados secuencialmente. Cada notebook aborda una parte específica del análisis:

    Obtención de Datos:
        Descarga de datos de velocidad y dirección del viento desde el portal NASA POWER para Asunción, Paraguay.

    Análisis Exploratorio:
        Visualización de series temporales de velocidad del viento.
        Cálculo de estadísticas descriptivas.

    Análisis Estacional:
        Evaluación de patrones estacionales y mensuales del viento.
        Generación de rosas de los vientos para diferentes estaciones del año.

    Modelado y Tendencias:
        Ajuste de distribuciones de Weibull para modelar la velocidad del viento.
        Extrapolación de velocidades a diferentes alturas utilizando la ley de potencia.
        Análisis de tendencias a lo largo del tiempo mediante regresión lineal.

    Evaluación del Potencial Eólico:
        Cálculo de la densidad de potencia del viento.
        Discusión sobre la viabilidad de la instalación de plantas eólicas basándose en los resultados obtenidos.

Para ejecutar un notebook específico:

    Si utilizas Google Colab:
        Sube el notebook a tu cuenta de Google Drive y ábrelo con Colab.
        Asegúrate de montar tu Google Drive si el notebook requiere acceso a archivos almacenados allí.

    Si utilizas Jupyter Notebook localmente:
        Navega hasta la carpeta notebooks/ y abre el archivo deseado con Jupyter.