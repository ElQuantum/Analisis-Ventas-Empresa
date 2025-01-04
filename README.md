# __Análisis de Ventas de una Empresa__
Este repositorio contiene el proyecto de análisis de ventas, para identificar tendencias, patrones y oportunidades de mejora. Incluye un dashboard interactivo de Power Bi y el código de Python utilizado para la limpieza de datos, creación de base de datos para usar sentencias de SQL y visualizaciones para el análisis de datos.

## __Contenido del Repositorio__

* 📁 __Codigo__: Contiene el código de Python utilizado para todo el proceso de análisis.
  * `Analisis_ventas_empresa.ipynb`: Script para la limpieza de datos, creación de la base de datos, sentencias de SQL y generación de visualizaciones.
  * `requiremente.txt`: Versión de bibliotecas necesarias para compilar el archivo de Python.

* 📁 __Dashboard__: Archivo `.pbix` del dashboard de Power Bi.
  * `analisis_ventas.pbix`: Dsahboard interactivo con análisis visual de varias relaciones clave.

* 📁 __Datos__: Contiene los datos utilizados en el proyecto.
  * 📁 __Base de datos__: Contiene la base de datos que se creó en SQLite, para poder usar sentencias de SQL en el código de Python.
    * `superstore.db`: Base de datos procesada después de la limpieza de datos.
  * 📁 __Datos limpios__: Contiene el archivo `.csv` después de realizar la limpieza de datos en Python.
    * `ventas_superstore.csv`: Datos procesados después de la limpieza.
  * `Sample-Superstore.csv`: Datos crudos descargados de __Kaggle__.

* 📁 __Visualizaciones__: Capturas de los gráficos realizados en Python

* 📄 `Análisis_de_Ventas_de_una_Empresa.pdf`: Contiene un reporte del proyecto con todo el análisis que se realizó tanto en Power Bi, como en Python.


## __Dashboard Interactivo__
El archivo de Power Bi incluye:

* __Análisis de Ventas por Categoría__: Cantidad de ventas y productos más vendidos.
* __Clientes que generan mayores ventas__: Clientes más fercuentes y con mayor cantidad de compras.
* __Ventas y Ganancias por ciudad__: Distribución de las ventas por cada ciudad y región.
* __Indicadores clave__: Ganancias totales, desceuntos por categoría, entre otros.

## __Cómo usar este Proyecto__

1. __Explorar el Dashboard__:
  * Descarga el archivo `analisis_ventas.pbix` y ábrelo en Power Bi Desktop.
2.  __Reproducir el análisis con Python__:
  * Usa el archivo de Python `Analisis_ventas_empresa.ipynb` para procesar los datos paso a paso y generar visualizaciones clave. Es necesario descargar también `Sample-Superstore.csv` para poder usar en el script de Python.
3. __Leer el reporte__:
  * Descargar el archivo `Análisis_de_Ventas_de_una_Empresa.pdf`, que contiene una síntesis de todo el análisis realizado, juntando resultados de Power Bi y Python.


## __Contribuciones__
Cualquier contribución es bienvenida. Si tienes sugerencias, mejoras o encuentras algún error, por favor envía un _pull request_.
