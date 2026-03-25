# 📞 Análisis de Retención de Clientes (Churn) - Sector Telecomunicaciones

## 📌 Descripción del Proyecto
Este proyecto se enfoca en identificar los factores clave que influyen en la deserción de clientes en una compañía de telecomunicaciones. Utilizando un dataset de **Kaggle**, se desarrolló un proceso de análisis integral que abarca desde la limpieza de datos hasta la creación de un dashboard estratégico en Power BI.

El objetivo principal es proporcionar insights accionables para reducir el **Churn Rate** (Tasa de Abandono) y mejorar las estrategias de fidelización.

## 🛠️ Tecnologías Utilizadas
* **Power BI:** Visualización de datos y diseño de dashboard.
* **Power Query (M):** Transformación de datos, normalización de tipos lógicos y creación de columnas condicionales.
* **DAX:** Creación de medidas dinámicas y KPI de negocio.

## 🔄 Proceso de Análisis (ETL & Modelado)
1. **Limpieza de Datos:** Transformación de variables booleanas (TRUE/FALSE) a numéricas (1/0) para habilitar cálculos matemáticos.
2. **Segmentación:** Creación de una columna condicional de "Rango de Antigüedad" para clasificar a los clientes en:
   * **Nuevo:** < 60 días.
   * **Maduro:** 60 - 120 días.
   * **Fiel:** > 120 días.
3. **Modelado DAX:** * `Total Clientes`: Conteo de registros únicos.
   * `Total Bajas`: Suma de registros con churn positivo.
   * `Churn Rate %`: Medida dinámica comparativa.

## 💡 Hallazgos Principales (Insights)
* **Impacto del Plan Internacional:** Los clientes con plan internacional contratado presentan una tasa de abandono significativamente mayor que el promedio global (14.85%).
* **Lealtad en Riesgo:** Se identificó que la tasa de Churn aumenta levemente en los segmentos "Maduro" y "Fiel", sugiriendo que la empresa necesita reforzar sus planes de fidelización a largo plazo.

## 📊 Visualización del Proyecto
<img width="908" height="507" alt="image" src="https://github.com/user-attachments/assets/5a617d29-eca1-4dca-8705-d3b2115df90e" />


---
📩 **Contacto:** andrea.moreno.lamberti@gmail.com | www.linkedin.com/in/andreaelenamorenolamberti
