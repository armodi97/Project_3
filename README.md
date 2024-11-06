
# Proyecto de Análisis de Pedidos de Instacart

Este proyecto realiza un análisis de datos sobre los pedidos de comestibles en la plataforma Instacart. El objetivo es estudiar el comportamiento de los clientes, el uso de los pasillos y departamentos en la tienda y explorar patrones en los pedidos.

## Descripción del Proyecto

Instacart es una plataforma de entrega de comestibles en la que los clientes pueden hacer pedidos y recibirlos a domicilio. En este proyecto, se analiza un conjunto de datos modificado que contiene información sobre los pedidos, productos, pasillos y departamentos. El conjunto de datos ha sido preprocesado para facilitar el análisis, incluyendo valores faltantes y duplicados.

## Estructura del Análisis

1. **Introducción y Preparación de los Datos**
   - Se cargan los datos de cinco archivos (`instacart_orders.csv`, `products.csv`, `aisles.csv`, `departments.csv`, y `order_products.csv`) en diferentes DataFrames.
   - Cada archivo representa una entidad en el sistema de Instacart, como pedidos, productos, pasillos y departamentos.
   - Se realiza una verificación de la estructura de los datos para identificar columnas, tipos de datos y valores faltantes.

2. **Análisis Exploratorio de Datos**
   - Se exploran las características principales de los datos, incluyendo la distribución de pedidos en distintos días de la semana y horas del día.
   - Se analiza el comportamiento de los clientes en cuanto a la frecuencia de pedidos y los productos más populares.
   - Visualizaciones interactivas se crean usando `plotly` para representar la distribución de productos por pasillos y departamentos.

3. **Identificación de Patrones en los Pedidos**
   - Se identifican patrones de recompra y se exploran tendencias en los productos que los clientes tienden a pedir de manera recurrente.
   - Se analiza la relación entre los departamentos y la frecuencia de pedidos para entender qué secciones de la tienda reciben más demanda.

4. **Conclusiones**
   - Se resume el análisis identificando patrones clave en el comportamiento del cliente y su preferencia por determinados productos y secciones de la tienda.

## Requisitos

- **Python 3.7+**
- Librerías: `pandas`, `plotly`

## Cómo Ejecutar el Proyecto

1. Clona el repositorio.
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta el notebook `Project_3.ipynb` para reproducir el análisis y las visualizaciones.
