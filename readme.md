# UD03 - Proyecto Integrador: Análisis del Mercado Airbnb en Valencia

**Autor:** Igor Ostyak  
**Fecha:** 22 de Diciembre 2025  
**Curso:** IA y Big Data  
**Nivel de dificultad:** Intermedio 
**Nota máxima:** 90 puntos

## 📋 Descripción del Proyecto

Este proyecto consiste en un analisis de datos completo sobre el mercado de alojamientos de Airbnb en la ciudad de Valencia. He trabajado con un dataset real para entender como funcionan los precios, que zonas son las mas caras y que tipo de alojamientos prefieren los usuarios.

A lo largo del trabajo, he realizado una limpieza profunda de los datos para eliminar errores y precios atipicos, y he creado visualizaciones avanzadas como un Dashboard general y un mapa interactivo para localizar las mejores zonas segen el precio y las reseñas.

## 📊 Dataset Utilizado

- **Listings:** `listings.csv.gz` - Datos detallados de cada alojamiento (ubicación, tipo, precio, capacidad).
- **Reviews:** `reviews.csv.gz` - Datos de las reseñas dejadas por los huespedes, utilizado para medir la popularidad.
- **Fuente:** Inside Airbnb
- **Tema:** Analisis del Sector Turistico

## 🎯 Objetivos del Análisis

1. Limpiar y preparar los datos eliminando nulos y "outliers" de precios
2. Identificar la distribución de precios por barrios y distritos en Valencia
3. Analizar la estacionalidad del mercado y la influencia del tipo de habitación en el precio

## 🔑 Principales Hallazgos

1. **Predominio del Piso Completo:** Los "Entire home/apt" representan la mayoria de la oferta y tienen los precios mas altos
2. **Zonas Premium:** El centro historico y la playa concentran la oferta mas cara, mientras que el interior tiene precios mas bajos con alta demanda
3. **Efecto de las Reseñas:** Los precios moderados acumulan mas volumen de comentarios, lo que indica que el mercado busca equilibrio entre calidad y coste

## 🛠️ Tecnologías Utilizadas

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly

## 📦 Instalación

```bash
rm -r -force .git
# Instalar dependencias
pip install -r requirements.txt

```

## 🚀 Ejecución

1. Descargar el dataset y colocarlo en `data/listings.csv`
2. Abrir Jupyter Notebook:
```bash
jupyter notebook notebooks/UD03_Analisis_Airbnb_Valencia.ipynb

```


3. Ejecutar todas las celdas en orden (Kernel → Restart & Run All)

## 📁 Estructura del Proyecto

```text
Proyecto_Airbnb_Valencia/
├── datos/
│   └── listings.csv.gz
│   └── reviews.csv.gz
├── informes/
│   └── Informe_Final.pdf
├── notebooks/
│   └── UD03_Analisis_Airbnb_Valencia.ipynb
├── visualizaciones/
│   └──dashboard.png
│   └──newplot.png
├── README.md
└── requirements.txt

```

## 📧 Contacto

**Email:** igorostyak11@gmail.com

**LinkedIn:** [Igor Ostyak](https://www.linkedin.com/in/igor-ostyak-584b38287/)

## 📜 Licencia

Este proyecto es parte del curso de Especialización en IA y Big Data.
