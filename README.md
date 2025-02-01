# Análisis del Sector y Desarrollo de Algoritmos

## Introducción
Para definir el entendimiento de la situación actual, trabajamos sobre el enunciado, el cual nos dice que la empresa está requiriendo un análisis del sector en base a información que nos brinda de 2 fuentes. Debemos poder analizar estas fuentes para generar un algoritmo que le permita obtener las recomendaciones que está solicitando.

## Objetivos
1. **Análisis de Sentimiento**: Identificar los establecimientos que van a estar en una mejor posición respecto al sentimiento de los usuarios.
2. **Predicción de la Demanda**: Determinar cómo se va a estar moviendo la demanda a corto plazo.
3. **Desarrollo de Algoritmos**: Crear un algoritmo capaz de realizar recomendaciones y predecir los centros de mayor demanda.
4. **Redes Neuronales**: Identificar el sentimiento de los usuarios respecto a los establecimientos visitados, utilizando sus reseñas en lenguaje natural.

## Alcance del Proyecto
El alcance del proyecto se va a limitar a utilizar los data sets brindados y cruzar la información con data sets que vamos a extraer desde páginas web utilizando web scraping. Para ello, utilizaremos Python como herramienta principal de programación y complementaremos los análisis utilizando MySQL Workbench y Microsoft Power BI.

### Metodología
1. **Análisis Exploratorio de Datos (EDA)**: Realizaremos un análisis exploratorio de datos para entender la conformación de los datos disponibles.
2. **Transformaciones de Datos**: Procederemos a realizar transformaciones necesarias para alimentar los algoritmos.
3. **Data Warehouse**: Crearemos un data warehouse en MySQL Workbench o en la nube, si es posible, para guardar la información de forma estructurada.
4. **Carga de Datos**: Cargaremos la información en el data warehouse y comprobamos su funcionalidad.
5. **Conexión Power BI y MySQL**: Haremos la conexión entre Power BI y MySQL para alimentar el dashboard.

## KPI Propuestos
1. Proporción de hoteles con reseñas positivas.
2. Cantidad de hoteles en la zona.
3. Cantidad de reseñas en hoteles.

## División del Trabajo
Nuestra metodología incluye la división del trabajo en 3 segmentos:
1. Documentación e investigación.
2. Data analytics.
3. Machine Learning e ingeniería de datos.

### Cronograma
- **Semana 1**: Documentación e investigación.
- **Semana 2**: Inicio de data analytics.
- **Semana 1 a Semana 4**: Desarrollo de Machine Learning e ingeniería de datos, con el algoritmo en producción en la última semana.

## Flujo de Trabajo
El flujo de trabajo implicará:
1. División de trabajo.
2. Puesta en común de la metodología de trabajo.
3. Definición de roles y fechas de entrega.
4. Definición de KPI.
5. Creación del diagrama de flujo de Gantt.
6. Realización del EDA.
7. Creación del data warehouse en MySQL Workbench.
8. Realización del ETL en Python.
9. Conexión de Python con el data warehouse.
10. Creación de la conexión web scraping desde Python.
11. Desarrollo del algoritmo de análisis de sentimiento.
12. Establecimiento de la demanda futura prevista.
13. Creación del algoritmo de recomendaciones.
14. Realización de la conexión y carga de datos en Power BI.
15. Desarrollo del tablero de mando.

## Cronograma Estimado
- **1 semana**: Documentación y inicio del proyecto.
- **3 semanas**: Completar EDA, ETL y carga de datos en Python.
- **Entre semana 2 y 4**: Creación de la base de datos.
- **Antes de semana 4**: Conectar Power BI con la base de datos.
- **Semana 4**: Presentar el algoritmo en producción.

## Stack Tecnológico
- **Lenguajes y Herramientas**:
  - Python
  - MySQL Workbench
  - Power BI

## Herramientas de Machine Learning
- **Redes Neuronales**: Utilizaremos redes neuronales tipo Transformers para el análisis de sentimientos, ya que están preentrenadas y utilizan lenguaje natural.
- **Mapas de Calor**: Para conocer dónde se está concentrando la demanda.
- **Desarrollo de Algoritmos de Recomendaciones**: Utilizaremos redes neuronales Transformers o SciPy, considerando la cantidad de lenguaje natural presente en las reseñas.
