📊 Análisis de Licencias de Software – Entidad Pública (Colombia)
🧠 Descripción del proyecto

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre el inventario de licencias de software de una entidad pública en Colombia, utilizando datos abiertos del portal datos.gov.co.

El objetivo es limpiar, normalizar y analizar la información para facilitar la toma de decisiones relacionadas con:

Gestión de licencias

Control de activos de software

Optimización de costos

Visualización de la distribución tecnológica

📁 Fuente de datos

Plataforma: Datos Abiertos Colombia

Dataset: Licencias de software

Registros: 119

Periodo: 2024 – 2026

Formato original: CSV / Excel

🎯 Objetivos del análisis

Identificar la distribución de licencias por tipo de herramienta

Normalizar categorías inconsistentes

Analizar el volumen real de licencias por categoría

Evaluar el estado de las licencias (activas vs perpetuas)

Identificar los softwares con mayor número de licencias

🛠️ Tecnologías utilizadas

Python

Pandas

Matplotlib

Google Colab

Excel (pre-limpieza inicial)

🧹 Proceso de limpieza de datos

Durante la limpieza se realizaron las siguientes acciones:

Normalización de texto en la columna Tipo de herramienta

Corrección de inconsistencias ortográficas y categóricas

Creación de una nueva variable: Categoría de herramienta

Tratamiento de valores nulos en la columna Cantidad

Validación de coherencia de estados de licencia

Categorías finales creadas:

DISEÑO

DESARROLLO

SEGURIDAD

OFIMÁTICA

ANÁLISIS DE DATOS

BASES DE DATOS

SOPORTE / UTILIDADES

OTROS

📊 Análisis exploratorio (EDA)
🔹 Distribución de licencias por categoría

Se identificó una alta concentración de licencias en categorías como:

DISEÑO

OFIMÁTICA

SEGURIDAD

Esto sugiere un enfoque operativo fuerte en áreas creativas, administrativas y de protección de sistemas.

🔹 Volumen total de licencias

El análisis por cantidad permitió identificar:

Categorías con mayor impacto en volumen

Oportunidades para auditoría y optimización de licencias

🔹 Estado de las licencias

Se observó la coexistencia de:

Licencias Perpetuas (activos a largo plazo)

Licencias Activas (requieren seguimiento y renovación)

Esto resalta la importancia de una gestión diferenciada por tipo de licencia.

🔹 Softwares con mayor número de licencias

Un número reducido de softwares concentra la mayor cantidad de licencias, lo cual:

Facilita la priorización de controles

Permite optimizar negociaciones con proveedores

📌 Principales insights

La normalización de categorías mejora significativamente la calidad del análisis

Existe concentración de licencias en pocas categorías clave

El control del estado de las licencias es crítico para la gestión IT

Los datos abiertos permiten generar valor real mediante análisis estructurado

📂 Estructura del proyecto
├── data/
│   ├── licencias_software_original.csv
│   └── licencias_software_limpio.xlsx
├── notebooks/
│   └── analisis_licencias_software.ipynb
├── README.md

🚀 Próximos pasos

Análisis de costos por proveedor

Migración del análisis a SQL:
## 🗄️ Análisis en SQL

El dataset limpio fue exportado desde Python y cargado en una base de datos SQLite.
Se realizaron consultas SQL para replicar y validar los resultados obtenidos en el análisis exploratorio.

Consultas realizadas:
- Conteo total de registros
- Distribución por categoría de herramienta
- Total de licencias por categoría
- Estado de licencias
- Top softwares con mayor número de licencias

Creación de dashboard en Power BI / Tableau

Automatización del proceso de limpieza

👤 Autor

Álvaro Enrique Plata Moscote
📍 Colombia
📊 Aspirante a Data Analyst / BI Junior
🔗 LinkedIn: (agregar enlace)

🏁 Nota final

Este proyecto forma parte de mi portafolio profesional, enfocado en demostrar habilidades prácticas en análisis de datos, limpieza, visualización y generación de insights a partir de datos reales.
