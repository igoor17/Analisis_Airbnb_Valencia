# UD03 - Proyecto Integrador: Análisis del Mercado Airbnb en Valencia

**Autor:** Igor Ostyak  
**Fecha:** 22 de Diciembre 2025  
**Curso:** IA y Big Data  
**Nivel de dificultad:** Intermedio 
**Nota máxima:** 90 puntos

## 📋 Descripción del Proyecto

En este trabajo he analizado datos reales del mercado de Airbnb en Valencia para entender como funciona el sector turistico en la ciudad. He utilizado datos de Inside Airbnb para ver que zonas son las mas caras, donde hay mas demanda y que caracteristicas hacen que un alojamiento tenga exito.

El objetivo era coger datos brutos, limpiarlos y sacar conclusiones utiles que sirvan para tomar decisiones, como por ejemplo: ¿donde es mejor invertir? o ¿que tipo de piso busca realmente la gente?

## 📊 Datasets Utilizados

He trabajado con dos archivos principales que se encuentran en la carpeta `datos/`:

- **`listings.csv.gz`**: Es el archivo principal. Tiene toda la información detallada de los alojamientos (barrio, precio, número de habitaciones, etc.).
- **`reviews.csv.gz`**: Contiene las opiniones de los usuarios. Lo he utilizado para medir la "demanda real" (analizando cuales tienen mas comentarios recientes).

**Nota:** Todo el analisis se centra en el **Sector Turistico**.

## 🎯 Objetivos

1. **Limpieza de Datos:** Eliminar valores nulos y filtrar precios irreales (outliers superiores a 300€) que distorsionaban las medias.
2. **Análisis de Precios:** Identificar cuanto cuesta una noche media segun el barrio y el distrito.
3. **Análisis de Demanda:** Cruzar los datos de precios con las reseñas para ver que tipo de alojamientos tienen mayor rotación.

## 🔑 Mis Conclusiones

1. **Piso completo vs Habitación:** La gran mayoria de la oferta en Valencia son apartamentos enteros. Alquilar habitaciones sueltas tiene mucha menos presencia y margen.
2. **Las zonas clave:** Ciutat Vella y los Poblats Maritims (Playa) son las zonas mas caras. Sin embargo, he detectado barrios de la periferia norte con precios mas bajos pero con una demanda muy estable, ideales para empezar con menor riesgo.
3. **El factor capacidad:** Los datos muestran que los pisos que aceptan mas huespedes consiguen mejores precios y ocupación que los estudios pequeños para dos personas.

## 🛠️ Tecnologías

He desarrollado el proyecto en Python 3 usando estas librerías:
- **Pandas & NumPy:** Para toda la carga y limpieza de datos.
- **Matplotlib & Seaborn:** Para las gráficas de precios y barras.
- **Plotly:** Para crear el mapa interactivo de las zonas de Valencia.
- **Nbformat:** Necesario para visualizar correctamente los mapas en el notebook.

## 📦 Instalación

```bash
#Clonar el repositorio:
git clone https://github.com/igoor17/Analisis_Airbnb_Valencia
# Instalar dependencias
pip install -r requirements.txt

```

## 🚀 Ejecución

1. Descargar el dataset (`listings.csv.gz` y `reviews.csv.gz`) y colocarlos en `datos/`
2. Abrir Jupyter Notebook:
```bash
jupyter notebook notebooks/UD03_Analisis_Airbnb_Valencia.ipynb

```
## 📊 Visualización del Proyecto (Presentación)

Este proyecto incluye una presentación interactiva generada directamente desde el Notebook, ocultando el código para centrarse en los gráficos y conclusiones.

Tienes dos formas de verla:

### Opción 1: Archivo Directo (Rápido y Fácil)
Si no quieres ejecutar codigo, simplemente descarga y abre el archivo HTML que ya esta generado en la carpeta `notebooks`:

* 📂 **Archivo:** `UD03_Analisis_Airbnb_Valencia.slides.html`
* 🖥️ **Instrucciones:** Haz doble clic sobre el para abrirlo en tu navegador favorito.
* ⚠️ **Nota:** Asegúrate de tener conexión a internet para que los mapas interactivos (Plotly) carguen correctamente.

---

### Opción 2: Generar
Si tienes el entorno instalado y quieres ver la presentación con un servidor local (recomendado para máxima compatibilidad), ejecuta este comando en tu terminal desde la raíz del proyecto:

```bash
jupyter nbconvert notebooks/UD03_Analisis_Airbnb_Valencia.ipynb --to slides --no-input --post serve
```
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
