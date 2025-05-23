# Challenge_DataScience_Alura

# Análisis Comparativo de Tiendas en Línea

## Descripción General

Este proyecto de ciencia de datos analiza y compara el desempeño de **cuatro tiendas en línea** utilizando datos reales de ventas, productos, calificaciones de clientes, costos de envío y ubicación geográfica. El objetivo es identificar cuál de las tiendas es la mejor opción para vender productos, considerando factores clave como facturación, categorías más vendidas, satisfacción del cliente, productos destacados, costos de envío y distribución geográfica de las ventas.

---

## Estructura del Proyecto

- **Importación de Datos:** Descarga y carga de los datasets de cada tienda desde fuentes públicas.
- **Análisis de Facturación:** Comparación de ingresos totales por tienda.
- **Ventas por Categoría:** Identificación de las categorías de productos más y menos vendidas.
- **Calificación Promedio:** Evaluación de la satisfacción del cliente por tienda.
- **Productos Más y Menos Vendidos:** Ranking de productos según su volumen de ventas.
- **Costo de Envío Promedio:** Comparación de los costos de envío entre tiendas.
- **Análisis Geográfico:** Visualización de la distribución de ventas y calificaciones por ubicación.
- **Informe Final:** Resumen de hallazgos y recomendación basada en los análisis.

---

## Variables Principales

- **tienda, tienda2, tienda3, tienda4:** DataFrames con los datos de cada tienda.
- **df_tiendas:** DataFrame combinado de todas las tiendas.
- **facturacion_por_tienda:** Diccionario con la facturación total por tienda.
- **ventas_categoria:** Serie con ventas totales por categoría de producto.
- **calif_promedio:** Lista con la calificación promedio de cada tienda.
- **productos_mas_vendidos / productos_menos_vendidos:** Series con los productos más y menos vendidos.
- **envio_promedio:** Lista con el costo de envío promedio por tienda.
- **tiendas:** Lista con los nombres de las tiendas.
- **tiendas_datos:** Lista con los DataFrames de cada tienda.

---

## Visualizaciones Incluidas

- **Gráficos de barras** para comparar facturación, calificaciones y costos de envío.
- **Gráficos de dispersión y mapas de calor** para analizar la distribución geográfica de ventas y calificaciones.
- **Gráficos de pastel** para mostrar los productos más y menos vendidos.

---

## Cómo Usar el Proyecto

1. **Requisitos**
    - Python 3.7+
    - Jupyter Notebook
    - Bibliotecas: `pandas`, `matplotlib`, `numpy`

    Instala las dependencias ejecutando:
    ```bash
    pip install pandas matplotlib numpy
    ```

2. **Ejecución**
    - Abre el archivo `.ipynb` en Jupyter Notebook.
    - Ejecuta las celdas en orden para reproducir el análisis y las visualizaciones.
    - Explora los resultados y el informe final para comprender las conclusiones y recomendaciones.

---

## Resultados y Recomendación

El análisis integral considera ingresos, satisfacción del cliente, costos logísticos y tendencias de ventas. Tras comparar todos los factores, **la Tienda 3** se recomienda como la opción más equilibrada para vender productos, ya que combina altos ingresos, excelente satisfacción del cliente y costos de envío competitivos.

---

## Créditos

Proyecto desarrollado como parte de un reto de ciencia de datos de Alura Latam.  
Datos y recursos disponibles en:  
https://github.com/alura-es-cursos/challenge1-data-science-latam
