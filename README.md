# Análisis de Delitos en la Ciudad de Buenos Aires - 2024

## Descripción General

Este repositorio contiene un proyecto de Business Intelligence desarrollado en Power BI que analiza los datos de delitos ocurridos en la Ciudad Autónoma de Buenos Aires durante el año 2024. El objetivo es transformar datos crudos en un informe interactivo que permita identificar patrones geográficos, temporales y de tipología delictiva.

### [Ver el Informe Interactivo en Vivo](https://app.powerbi.com/groups/decb516f-c852-463a-9e22-56f523e6ed30/reports/11f5b4d2-57b9-4117-abfc-8433739e96d0?ctid=caed286c-4396-4550-bf86-5561ed2b3254&pbi_source=linkShare)

---

## Vista Previa del Dashboard

![Dashboard de Seguridad CABA](dashboard.png)

---

## Proceso del Proyecto

1.  **ETL (Extracción, Transformación y Carga):** Se utilizó Power Query para conectar con la fuente de datos (`delitos_2024.csv`), realizar una limpieza exhaustiva (manejo de nulos, estandarización de tipos de datos) y normalizar el modelo.
2.  **Modelado de Datos:** Se implementó un **esquema de estrella** para optimizar el rendimiento y la claridad del modelo, creando tablas de dimensiones para Geografía, Tiempo, Tipo de Delito, etc., y una tabla central de Hechos.
3.  **Análisis con DAX:** Se crearon medidas personalizadas utilizando DAX (Data Analysis Expressions) para calcular KPIs clave como el total de delitos, el porcentaje de incidentes con uso de arma y el promedio diario de delitos.
4.  **Visualización de Datos:** El informe incluye una variedad de objetos visuales interactivos, como un mapa geoespacial para identificar "puntos calientes", gráficos de tendencia para el análisis temporal y segmentadores para un filtrado dinámico de la información.
5.  **Storytelling:** El dashboard está estructurado para contar una historia, guiando al usuario a través de los principales insights sobre la distribución geográfica, los patrones horarios y las modalidades delictivas más comunes.

---

## Herramientas Utilizadas

* **Power BI Desktop:** Para todo el proceso de ETL, modelado, análisis y visualización.
* **Power Query (Lenguaje M):** Para la transformación y limpieza de datos.
* **DAX (Data Analysis Expressions):** Para la creación de medidas y KPIs.
* **GitHub:** Para el control de versiones y la presentación del proyecto.

---

## Cómo Utilizar este Repositorio

1.  **Clona o descarga** el repositorio.
2.  Asegúrate de tener **Power BI Desktop** instalado.
3.  Abre el archivo `SeguridadCABA.pbix` para explorar el modelo de datos, las transformaciones en Power Query y el informe interactivo completo.
4.  El dataset original `delitos_2024.csv` está incluido para referencia.
