# 🧩 Proyecto de Data Analytics

## 📘 Descripción General

Este proyecto forma parte del trabajo práctico de **Análisis de Datos**, cuyo objetivo es aplicar las etapas iniciales del proceso de *Data Analytics*:  
- Recopilación, exploración y evaluación de la calidad de los datos.  
- Limpieza, transformación, agregación e integración para generar información útil.

Los análisis se desarrollaron en **Google Colab**, utilizando las librerías `pandas` y `numpy`, a partir de tres fuentes de datos:  
- `clientes.csv`  
- `ventas.csv`  
- `marketing.csv`

---

## 🧱 Etapa 1: Recopilación y Preparación de Datos

**Objetivos:**
1. Cargar los tres datasets como DataFrames.  
2. Realizar un análisis exploratorio inicial con Pandas.  
3. Evaluar la calidad de los datos (valores nulos y duplicados).

**Resultados:**
- Los datos se cargaron correctamente desde Google Drive.  
- Se verificó que el dataset de ventas contenía 35 registros duplicados y 4 valores nulos.  
- Se generó una tabla `estado_datos` documentando el estado inicial de cada dataset.  

---

## 🧹 Etapa 2: Preprocesamiento y Limpieza de Datos

**Objetivos:**
1. Eliminar duplicados y limpiar valores inconsistentes.  
2. Transformar los datos para calcular métricas de rendimiento.  
3. Agregar la información por categorías de producto.  
4. Integrar las tablas para obtener una visión completa de clientes, ventas y marketing.

**Resultados:**
- Se creó una nueva columna `total_venta` que mide el rendimiento de cada producto.  
- Se filtraron los productos de **alto rendimiento** (superiores al promedio de ventas).  
- Se resumieron los ingresos por categoría (`Decoración`, `Electrodomésticos`, `Electrónica`).  
- Los datasets fueron integrados exitosamente por la clave `producto`.

---

## 📊 Conclusión

El proyecto permitió aplicar las etapas iniciales del proceso de análisis de datos:
- Comprensión y limpieza de los datasets.  
- Transformación de variables para obtener indicadores de rendimiento.  
- Integración de diferentes fuentes para generar una vista unificada del negocio.

El notebook resultante está completamente funcional y cumple con la consigna pedida en clase.

