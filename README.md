# Análisis de E-commerce Olist - Power BI 🚀

Este proyecto presenta un ecosistema de dashboards para la toma de decisiones estratégicas en Olist (Brasil),
me enfoqué en la limpieza de datos y la creación de métricas accionables.

### 📊 Páginas del Dashboard:
1. **Operaciones y Logística**: Control de tiempos de entrega y gestión de retrasos.
2. **Producto y Cliente**: Análisis de categorías líderes y comportamiento de compra.
3. **Resumen Ejecutivo**: Ventas por categoría y géstion logístico.

## 🐍 Procesamiento de Datos (ETL)
Para este proyecto no solo se utilizó Power BI, sino que se aplicó un flujo de datos previo:
1. **Extracción:** Carga de datasets desde archivos CSV (+100k registros).
2. **Transformación (Python/Pandas):** Limpieza de nulos, normalización de nombres de categorías y exportación de datos limpios. (Ver carpeta `/notebook`).
3. **Carga:** Importación al modelo relacional de Power BI.

## 📂 Cómo utilizar este repositorio
1. Descarga los datos de la carpeta `/data` (recuerda unir los archivos ZIP si están divididos).
2. Abre el archivo `.pbix` en **Power BI Desktop**.
3. Si los enlaces de datos se rompen, actualiza la ruta de origen hacia la carpeta donde extrajiste los CSV.
