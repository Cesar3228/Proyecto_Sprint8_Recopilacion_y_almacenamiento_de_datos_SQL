# Proyecto_Sprint8_Recopilacion_y_almacenamiento_de_datos_SQL (English/Español)

# Sprint 8 – Statistical Data Analysis of Taxi Trips in Chicago  
### (TripleTen Data Science Program)

---

## 🇬🇧 Project Overview (English)

This project analyzes taxi trip data in Chicago using Python. It combines exploratory data analysis (EDA) and hypothesis testing to identify key patterns across taxi companies and neighborhoods, and to evaluate whether weather conditions affect trip duration between the Loop and O’Hare International Airport.

The analysis focuses on data cleaning, aggregation, visualization, and statistical inference to support data-driven conclusions based on real-world transportation data.

---

## Objectives
- Explore and validate taxi trip datasets
- Identify the most active taxi companies and drop-off neighborhoods
- Visualize trip distributions and interpret results
- Test a statistical hypothesis regarding trip duration under different weather conditions

---

## Datasets

### `project_sql_result_01.csv`
- **company_name**: name of the taxi company  
- **trips_amount**: number of trips per company on November 15–16, 2017  

### `project_sql_result_04.csv`
- **dropoff_location_name**: Chicago neighborhoods where trips ended  
- **average_trips**: average number of trips ending in each neighborhood during November 2017  

### `project_sql_result_07.csv`
- **start_ts**: trip start date and time  
- **weather_conditions**: weather conditions at trip start  
- **duration_seconds**: trip duration in seconds  
- Contains trips from the Loop to O’Hare International Airport  

---

## Exploratory Data Analysis
The EDA process includes:
- Importing and inspecting the datasets
- Verifying and correcting data types
- Identifying the top 10 neighborhoods by average trip drop-offs
- Aggregating data by taxi company and neighborhood
- Creating visualizations:
  - Taxi companies vs. number of trips
  - Top 10 neighborhoods by number of drop-offs

Each visualization is followed by interpretations explaining the observed patterns.

---

## Hypothesis Testing

**Null hypothesis (H₀):**  
The average duration of trips from the Loop to O’Hare International Airport does not change on rainy Saturdays.

**Alternative hypothesis (H₁):**  
The average duration of trips from the Loop to O’Hare International Airport changes on rainy Saturdays.

A significance level (α) is defined, and statistical testing is performed to determine whether the observed differences are statistically significant.

---

## Tools and Libraries
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scipy

---

## Key Insights
- A small number of taxi companies generate a large proportion of trips
- Trip drop-offs are concentrated in specific neighborhoods
- Weather conditions have a measurable impact on trip duration, supported by statistical testing

---

## Conclusion
This project demonstrates how exploratory data analysis and hypothesis testing can be used together to extract insights from transportation data and evaluate the impact of external factors such as weather on urban mobility.

---

---

## 🇪🇸 Descripción del Proyecto (Español)

Este proyecto analiza datos de viajes en taxi en la ciudad de Chicago utilizando Python. Se combinan técnicas de análisis exploratorio de datos (EDA) y pruebas de hipótesis para identificar patrones relevantes entre compañías de taxis y barrios, así como para evaluar si las condiciones climáticas influyen en la duración de los viajes entre el Loop y el Aeropuerto Internacional O’Hare.

El análisis se centra en la limpieza de datos, agregación, visualización y análisis estadístico para obtener conclusiones basadas en datos reales.

---

## Objetivos
- Explorar y validar los conjuntos de datos de viajes en taxi
- Identificar las compañías de taxi y barrios con mayor actividad
- Visualizar la distribución de los viajes y explicar los resultados
- Probar una hipótesis estadística sobre la duración de los viajes según el clima

---

## Análisis Exploratorio de Datos
El proceso de EDA incluye:
- Importación y revisión de los archivos CSV
- Verificación y corrección de tipos de datos
- Identificación de los 10 barrios principales por promedio de finalizaciones
- Agrupación de datos por compañía y barrio
- Visualización de:
  - Número de viajes por compañía de taxis
  - Los 10 barrios principales por número de finalizaciones

Cada gráfico incluye conclusiones e interpretación de los resultados.

---

## Prueba de Hipótesis

**Hipótesis nula (H₀):**  
La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O’Hare no cambia los sábados lluviosos.

**Hipótesis alternativa (H₁):**  
La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O’Hare sí cambia los sábados lluviosos.

Se define un nivel de significación (α) y se aplica un método estadístico adecuado para evaluar la hipótesis.

---

## Conclusión
Este proyecto muestra cómo el análisis exploratorio de datos y las pruebas de hipótesis permiten identificar patrones relevantes y validar supuestos en datos de transporte urbano, integrando análisis estadístico con conclusiones prácticas.

---

## Author / Autor
**César Octavio Arroyo Pérez**
