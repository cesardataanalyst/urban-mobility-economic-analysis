# urban-mobility-economic-analysis
# Mobility Economy Project

## 📌 Contexto y problema de negocio
La movilidad urbana está relacionada con factores económicos, sociales y operativos que pueden variar significativamente entre ciudades y países.
Este proyecto analiza información relacionada con **movilidad urbana y variables económicas**, con el propósito de identificar patrones y relaciones que puedan ayudar a comprender mejor el comportamiento del transporte y su contexto económico.
El análisis busca transformar datos públicos en información útil para apoyar la interpretación de tendencias y la toma de decisiones basada en datos.

## 🎯 Objetivo del análisis
El objetivo es explorar y analizar los datos de movilidad urbana junto con indicadores económicos para identificar patrones, tendencias y relaciones relevantes.

## Preguntas de análisis
- ¿Cómo se comportan las variables de movilidad analizadas?
- ¿Qué diferencias se observan entre las ciudades o países incluidos en los datos?
- ¿Cómo se relacionan los indicadores de movilidad con las variables económicas disponibles?
- ¿Qué tendencias o patrones relevantes pueden identificarse a partir de los datos?
- ¿Qué información puede ser útil para comprender la dinámica de la movilidad urbana?

## 📊 Origen de los datos
El proyecto utiliza **datos públicos** relacionados con movilidad urbana e indicadores económicos.
Las principales fuentes utilizadas son:
- **TomTom** — información relacionada con movilidad y tráfico urbano.
- **OECD** **(Organisation for Economic Co-operation and Development)** — indicadores económicos y urbanos.
Los datos fueron preparados y analizados para construir una visión conjunta de las variables seleccionadas.

##  Herramientas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

## 🔎 Metodología
El análisis siguió un flujo de trabajo basado en el proceso **OSEMN**:
### 1. Obtain
Obtención y revisión de los datasets provenientes de fuentes públicas.

### 2. Scrub
Limpieza y preparación de los datos, incluyendo revisión de:
- Valores ausentes
- Tipos de datos
- Registros duplicados
- Consistencia de las variables
- Calidad general de los datos

### 3. Explore
Exploración de las variables mediante:
- Estadística descriptiva
- Distribuciones
- Comparaciones entre ciudades y/o países
- Análisis de tendencias
- Identificación de relaciones entre variables

### 4. Model
Se analizaron las relaciones relevantes entre los indicadores disponibles para identificar patrones dentro de los datos.

### 5. iNterpret
Los resultados fueron interpretados desde una perspectiva de negocio, buscando convertir los hallazgos del análisis en información útil para la toma de decisiones.

## 📈 Principales resultados
El análisis permitió identificar patrones y diferencias relevantes en los indicadores de movilidad y económicos analizados.
Entre los principales hallazgos documentados en el proyecto se encuentran:
- Diferencias en los indicadores de movilidad entre las ciudades analizadas.
- Variaciones en las variables económicas consideradas.
- Relaciones entre determinadas variables de movilidad y contexto económico.
- Patrones identificados mediante el análisis exploratorio y las visualizaciones.

Nota: Los resultados específicos deben consultarse directamente en el notebook, donde se presentan los valores, gráficos y análisis que sustentan cada hallazgo.

## 📊 Visualizaciones e indicadores
El proyecto incluye visualizaciones para facilitar la interpretación de los datos, entre ellas:
- Distribución de variables.
- Comparaciones entre ciudades y países.
- Evolución de indicadores.
- Relación entre variables de movilidad y económicas.
- Gráficos comparativos para identificar patrones.

Las visualizaciones permiten complementar el análisis estadístico y comunicar los principales hallazgos de manera más clara.

## 💡 Conclusiones y posibles decisiones de negocio
Los resultados del análisis pueden servir como punto de partida para:
- Comparar el comportamiento de la movilidad entre diferentes ciudades.
- Identificar patrones que requieran mayor análisis.
- Evaluar la relación entre movilidad urbana y contexto económico.
- Apoyar análisis relacionados con planificación y gestión de movilidad.
- Utilizar indicadores de movilidad y económicos como insumos para estudios posteriores.

Las conclusiones presentadas en el notebook se basan en los datos analizados y deben interpretarse dentro del alcance y las limitaciones de las fuentes utilizadas.

Las principales variables analizadas fueron:

* **jams_delay:** retraso promedio causado por congestión.
* **traffic_index_live:** índice de tráfico en tiempo real.
* **travel_time_live_per_10kms_mins:** tiempo promedio de viaje por cada 10 km.
* **city_gdp_per_capita:** PIB per cápita de cada ciudad.

---

## ¿Qué contiene este repositorio?

Este repositorio incluye los recursos necesarios para reproducir el análisis:

* **Notebook principal (`mobility_economy_project_student.ipynb`)**

  * Limpieza y preparación de datos.
  * Integración de las bases de movilidad y economía.
  * Análisis exploratorio de datos (EDA).
  * Visualizaciones y conclusiones.

* **README.md**

  * Descripción del proyecto.
  * Objetivos.
  * Metodología.
  * Instrucciones de uso.

* **Gráficos**

  * Histogramas.
  * Boxplots.
  * Gráficos comparativos.
  * Visualizaciones utilizadas para identificar tendencias y valores atípicos.

---

## Metodología

El análisis se desarrolló siguiendo las siguientes etapas:

1. Limpieza y estandarización de los datasets.
2. Validación de formatos y nombres de columnas.
3. Selección de variables relevantes.
4. Integración de los datos mediante una **unión INNER** por ciudad y año.
5. Análisis exploratorio utilizando estadísticas descriptivas y visualizaciones.
6. Interpretación de resultados y elaboración de recomendaciones.

---

## Principales hallazgos

Los resultados muestran que las ciudades con mayor actividad económica tienden a presentar niveles elevados de congestión vehicular; sin embargo, la relación no es completamente lineal.

Entre los hallazgos más relevantes se identificó que:

* Grandes centros urbanos presentan mayores retrasos por tráfico.
* Existen ciudades con alto PIB per cápita y niveles moderados de congestión gracias a sistemas de transporte más eficientes.
* Bogotá y Lima aparecen como ciudades que podrían beneficiarse de inversiones adicionales en infraestructura de movilidad.
* Los valores atípicos observados justifican análisis estadísticos complementarios para validar las relaciones encontradas.

---

## ¿Cómo abrir el notebook en Google Colab?

* Descarga o clona este repositorio.
* Abre Google Colab.
* Selecciona Archivo → Abrir notebook.
* Ve a la pestaña GitHub o carga el archivo mobility_economy_project_student.ipynb.
* Ejecuta las celdas en orden de arriba hacia abajo.

  ---
  
## Herramientas utilizadas

* **Python**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Matplotlib**

---

## Conclusiones

Este análisis evidencia que la congestión vehicular puede estar asociada con diferencias en el desempeño económico urbano, aunque dicha relación depende de múltiples factores adicionales, como la infraestructura de transporte, la planificación urbana y el crecimiento demográfico.

Los resultados obtenidos permiten identificar ciudades donde futuras inversiones en movilidad sostenible podrían generar impactos positivos sobre la productividad y la calidad de vida.

---

## Autor

Proyecto desarrollado por **Cesar Palacio** como parte de su formación en **Data Analytics**, posteriormente reorganizado y documentado para su portafolio profesional en GitHub.
