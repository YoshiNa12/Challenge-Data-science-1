# Análisis de Ventas

## Propósito del Análisis

Este proyecto tiene como objetivo analizar las ventas de 4 tiendas para evaluar cuál tiene el menor rendimiento. Se analizaron diversas métricas clave, como el total de ventas, el promedio de clasificación, el producto más vendido, el costo de envío promedio y el conteo de artículos vendidos por categoría. Este análisis proporciona una base para identificar áreas de mejora en cada tienda.

### Organización del Análisis

El notebook está organizado en las siguientes secciones:

1. **Importación de Datos**  
   En esta sección, se cargan y preparan los datos para el análisis.

2. **Análisis de Facturación**  
   Aquí se analizan las métricas de facturación para cada tienda, como el total de ventas y el rendimiento general.

3. **Ventas por Categoría**  
   Se examina el total de ventas por cada categoría de productos en las tiendas.

4. **Clasificación Promedio de las Tiendas**  
   En esta parte, se calcula el promedio de la clasificación de los productos en cada tienda.

5. **Productos Más y Menos Vendidos**  
   Se identifican los productos más vendidos y los que tienen menos ventas en cada tienda.

6. **Envío Promedio por Tienda**  
   Finalmente, se calcula el costo de envío promedio por tienda para evaluar cómo este impacto en los costos generales.

## Ejemplos de Insights Obtenidos

Durante el análisis, se identificaron los siguientes insights clave:

- **La tienda con menor rendimiento** se destaca por tener un bajo total de ventas y un bajo promedio de clasificación.
- **El costo de envío promedio** varía entre las tiendas, lo que podría influir en la rentabilidad de cada una.
- **La categoría de productos más vendidos** muestra diferencias en los productos que tienen más éxito en cada tienda.

Estos insights ayudan a visualizar cómo las diferentes métricas afectan el rendimiento general de cada tienda.

## Instrucciones para Ejecutar el Notebook en Google Colab

Para ejecutar este notebook en Google Colab, sigue los pasos a continuación:

1. **Clonar el repositorio**:
   Si aún no lo has hecho, clona el repositorio a tu cuenta local o directamente en Google Colab:
   - Abre Google Colab en [https://colab.research.google.com/](https://colab.research.google.com/).
   - Haz clic en **Archivo > Abrir cuaderno** y selecciona la pestaña **GitHub**.
   - Introduce la URL del repositorio de GitHub o clona el repositorio directamente desde Colab utilizando el siguiente comando en una celda:
     ```python
     !git clone https://github.com/YoshiNa12/Challenge-Data-science-1
     ```

2. **Ejecutar el Notebook**:
   Una vez que hayas cargado los datos, abre el archivo `Challenge_DS1.ipynb` y ejecuta todas las celdas del notebook para reproducir el análisis.

   Si necesitas instalar algunas librerías adicionales en Colab, puedes hacerlo ejecutando el siguiente comando en una celda:
   ```python
   !pip install -r requirements.txt



