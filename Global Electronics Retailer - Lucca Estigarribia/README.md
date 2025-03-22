# Proyecto Final - Análisis de Datos de Global Electronics Retailer

## 📅 Fecha de entrega: 23/03/25

## 🔎 Autor: Lucca Estigarribia

---

## ✏️ **Índice de Contenido**

1. [Descripción General del Proyecto](#-descripción-general-del-proyecto)
2. [Estructura de Carpetas y Archivos](#-estructura-de-carpetas-y-archivos)
3. [Objetivos del Análisis](#-objetivos-del-análisis)
4. [Datos Utilizados](#-datos-utilizados)
5. [Metodología y Pasos Realizados](#-metodología-y-pasos-realizados)
6. [Principales Hallazgos](#-principales-hallazgos)
7. [Recomendaciones Estratégicas](#-recomendaciones-estratégicas)
8. [Consideraciones Finales](#-consideraciones-finales)

---

## 📅 **Descripción General del Proyecto**

Este proyecto tiene como objetivo realizar un análisis exploratorio y estadístico de los datos de ventas de la empresa "Global Electronics Retailer". El fin es extraer insights clave sobre los productos, las ventas en distintas ubicaciones y la estacionalidad, para ayudar a la empresa a tomar mejores decisiones comerciales.

---

## 🗂 **Estructura de Carpetas y Archivos**

```
.
├── data
│   ├── raw
│   │   ├── Customers.csv         # Información de los clientes
│   │   ├── Products.csv          # Detalles de los productos
│   │   ├── Sales.csv             # Histórico de ventas
│   │   ├── Stores.csv            # Detalles de las tiendas
│   │   ├── Exchange_Rates.csv    # Tipos de cambio
│   │   ├── Data_Dictionary.csv   # Diccionario de datos
├── notebook
│   ├── Global_Retail_Analysis.ipynb  # Notebook con todo el análisis, visualizaciones y conclusiones
├── README.md                     # Este archivo
```

---

## 🎯 **Objetivos del Análisis**

1. Identificar tendencias y patrones estacionales en las ventas.
2. Detectar los productos más vendidos y más rentables.
3. Analizar la ubicación geográfica de las ventas y el canal online.
4. Aplicar técnicas estadísticas (prueba t, correlaciones).
5. Extraer recomendaciones estratégicas para la empresa.

---

## 📊 **Datos Utilizados**

Se utilizaron los siguientes archivos:

- **Customers.csv:** Datos demográficos y ubicación de los clientes.
- **Products.csv:** Información detallada de cada producto (precio, costo, categoría).
- **Sales.csv:** Registro de las ventas (fecha, cantidad, producto, tienda).
- **Stores.csv:** Datos de cada tienda y su ubicación.
- **Exchange_Rates.csv:** Tipos de cambio.
- **Data_Dictionary.csv:** Guía explicativa de los campos.

---

## 🧰 **Metodología y Pasos Realizados**

1. **Carga y limpieza de datos**
    - Corrección de formatos.
    - Manejo de valores nulos.
2. **Análisis exploratorio (EDA)**
    - Análisis temporal y estacionalidad.
    - Análisis de productos por ventas, ingresos y rentabilidad.
    - Análisis geográfico.
3. **Aplicación de estadísticas**
    - Prueba t-Student (ventas online vs físicas).
    - Análisis de correlación (precio, tamaño de tienda, ventas).
4. **Visualizaciones gráficas**
    - Gráficos de líneas, barras, heatmaps.
5. **Extracción de conclusiones y recomendaciones**

---

## 🔍 **Principales Hallazgos**

- La mayoría de las ventas se concentran en noviembre y diciembre.
- Estados Unidos es el mercado más fuerte, seguido del canal online.
- Las computadoras lideran las ventas por volumen.
- Los productos premium como televisores generan ingresos altos pese a pocas ventas.
- No se encontraron correlaciones significativas entre precio, tamaño de tienda y cantidad vendida.

---

## 💡 **Recomendaciones Estratégicas**

- Preparar el inventario y la logística para los picos de demanda (noviembre - diciembre).
- Desarrollar campañas de marketing en los meses de baja demanda (marzo-mayo).
- Potenciar productos premium y de alto margen.
- Fortalecer la presencia en Estados Unidos y seguir expandiendo el canal online.

---

## 📅 **Consideraciones Finales**

Este análisis permite comprender mejor el comportamiento de las ventas y sentar bases sólidas para la toma de decisiones estratégicas. La empresa puede utilizar estos hallazgos para optimizar su inventario, potenciar productos y mejorar sus resultados comerciales.

---

> 📃 **Nota:** Para ver el análisis detallado, gráficos y código, acceder al notebook `Global_Retail_Analysis.ipynb`

📅 Lucca Estigarribia - [23/03/25]
