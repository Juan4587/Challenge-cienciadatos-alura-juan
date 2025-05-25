# Proyecto de Análisis de Datos por Tiendas

Este repositorio contiene un análisis exploratorio de datos (EDA) realizado en Python, utilizando información proveniente de cuatro tiendas diferentes. El objetivo es obtener métricas clave del negocio y visualizarlas mediante gráficos, facilitando la comprensión de los patrones de comportamiento de ventas, satisfacción del cliente y logística.

## Objetivo

Realizar un análisis integral de las ventas, satisfacción y distribución de productos en distintas tiendas utilizando Python y visualizaciones con matplotlib.

## Estructura del proyecto

- Archivos CSV: Archivos fuente con los datos de cada tienda.
- analisis.py / notebook.ipynb: Código del análisis paso a paso.
- README.md: Documento de referencia del proyecto.


## Cómo ejecutar el proyecto

1. Abre el archivo .ipynb en Jupyter o Google Colab.
2. Asegúrate de cargar los 4 archivos CSV correspondientes a las tiendas.
3. Ejecuta cada celda paso a paso para visualizar:

   - Ingresos por tienda
   - Ventas por categoría
   - Valoraciones promedio
   - Productos más y menos vendidos
   - Costos de envío promedio
   - Visualizaciones gráficas

## Resultados visuales

El proyecto genera visualizaciones de:
- Ventas totales por tienda
- Distribución de ventas por categoría
- Satisfacción del cliente (calificaciones promedio)
- Producto más y menos vendido
- Promedio de costos de envío

## Dependencias

- Python 
- pandas
- matplotlib

## Posibles problemas

- Asegúrate de que los archivos .csv tengan los mismos nombres de columnas esperados ('Producto', 'Precio', 'Calificación', 'Costo de envío', etc.)
- El separador decimal debe ser . y no , en los archivos.

## Contribuciones

Este proyecto fue desarrollado como ejercicio formativo. Las contribuciones, mejoras y sugerencias son bienvenidas.

## Autor

Juan Esteban Mazo Gaitán 
Estudiante de Ciencia de Datos – Oracle ONE
