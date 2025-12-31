# megaline-prepaid-plan-analysis
# Análisis de Tarifas Prepago – Megaline

## Descripción del Proyecto
Megaline es un operador de telecomunicaciones que ofrece dos planes prepago: **Surf** y **Ultimate**.  
El área comercial necesita identificar cuál de estos planes genera mayores ingresos para optimizar la inversión en publicidad y las estrategias de marketing.

En este proyecto se realiza un **análisis exploratorio y estadístico de datos**, con el fin de comprender el comportamiento de los clientes y apoyar la toma de decisiones basada en datos.

## Conjunto de Datos
El análisis se basa en información de **500 clientes de Megaline durante el año 2018**, que incluye:
- Datos demográficos de los clientes  
- Tipo de plan contratado  
- Duración de llamadas  
- Mensajes de texto enviados  
- Consumo de datos móviles  
- Ingresos mensuales por cliente  

## Objetivos
- Analizar el comportamiento de uso de los clientes según el plan contratado  
- Comparar los ingresos generados por los planes Surf y Ultimate  
- Identificar diferencias significativas en los ingresos promedio  
- Generar recomendaciones de negocio basadas en los resultados  

## Análisis Realizado
- Revisión y limpieza de datos (valores faltantes y tipos de datos)  
- Análisis exploratorio de datos (EDA)  
- Estudio de distribuciones y tendencias mensuales  
- Comparación del uso de servicios y de los ingresos por plan  
- Pruebas de hipótesis estadísticas por plan y por región  

## Principales Hallazgos
- El plan **Ultimate** presenta un ingreso promedio mensual más alto y estable que el plan Surf  
- La mayoría de los ingresos de Ultimate proviene de la tarifa base del plan  
- En el plan Surf, los usuarios suelen exceder los límites del plan, generando cargos adicionales  
- Las distribuciones de uso muestran sesgo a la derecha, indicando que la mayoría de los usuarios tiene un consumo moderado  
- Se identificaron diferencias estadísticamente significativas en los ingresos promedio entre regiones (NY–NJ vs otras)  

## Recomendaciones de Negocio
- Priorizar la inversión publicitaria en el plan Ultimate por su estabilidad y rentabilidad  
- Implementar estrategias para migrar usuarios del plan Surf al Ultimate cuando su consumo exceda la tarifa base  
- Ajustar las estrategias de marketing según la región geográfica  

## Herramientas y Habilidades
Python · Pandas · NumPy · Matplotlib · Seaborn · Análisis Exploratorio de Datos · Pruebas de Hipótesis · Análisis Estadístico
