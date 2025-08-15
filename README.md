# Analisis-Mercado-Inmobiliario-Colombia

# Descripción del Proyecto
Este proyecto es un análisis exploratorio de datos (EDA) del mercado de propiedades en venta en Medellín, Colombia. El objetivo principal es identificar las tendencias de precios, los factores que influyen en el valor de las propiedades y las zonas de mayor interés para compradores e inversionistas.

Los datos fueron obtenidos en la pagina web Kaggle("Propiedades en venta en Colombia (FincaRaiz)" por Diego Medina F.) y fueron limpiados, procesados y visualizados utilizando herramientas de análisis de datos.

# Objetivos del Análisis
El análisis se centró en cumplir los siguientes 5 objetivos:

1. Evaluación de la Calidad de los Datos y Limpieza: Identificar y manejar valores nulos y atípicos, y asegurar la correcta tipificación de los datos para un análisis confiable.
2. Análisis Descriptivo del Mercado: Calcular métricas clave (promedio, mediana, distribución de precios) para obtener una visión general del mercado de propiedades.
3. Identificación de Sectores Estratégicos: Determinar los barrios más caros y más económicos, así como las zonas con la mayor oferta de propiedades.
4. Análisis del Impacto de las Características en el Precio: Cuantificar cómo variables como el área, el número de habitaciones y los baños influyen en el precio final de las propiedades.
5. Creación de un Dashboard Interactivo: Desarrollar un dashboard que permita la exploración visual de todos los hallazgos para una toma de decisiones más informada.

# Metodología
1. Limpieza de Datos: El dataset inicial fue analizado con Python (Pandas) para tratar valores nulos, corregir tipos de datos y manejar outliers en columnas clave como el precio y el área.
2. Análisis Exploratorio: Se utilizaron visualizaciones en Python (Matplotlib y Seaborn) para descubrir patrones y correlaciones entre las variables.
3. Visualización Interactiva: El dataset limpio fue cargado en Power BI para crear un dashboard interactivo que resume los principales hallazgos del análisis.

# Conclusiones clave
1. Se encontro que las casas tienen el precio promedio de venta mas elevado que los apartamentos, pero los apartamentos tienen el precio de M2 promedio mas elevado que el de las casas.
2. Antioquia es el estado con mayor precio promedio de venta de todo el conjunto de datos con un valor de $519'000.000 COP, superando a Bogota D.C. por un 7.4%
3. El precio de venta esta fuertemente correlacionado con el Area Construida (0.51) y la cantidad de Baños (0.59)
4. La presencia de un Garage puede elevar el precio de venta en mas de $100'000.000 COP
5. Existe una clara diferencia en el precio de venta entre los diferentes estratos, con las propiedades de estrato 6 costando, en promedio, un 75% más que las de estrato 4.


# Herramientas y Tecnologías
Python: Para la limpieza y el análisis de datos (pandas, matplotlib, seaborn).
Power BI: Para la visualización interactiva y la creación del dashboard.
GitHub: Para  el alojamiento del proyecto.
   
