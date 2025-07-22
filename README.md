# Evaluación de la Contaminación Ambiental por  Material particulado PM 2.5 en Soacha
  

Diego Molina y Camila Canchon   

En Colombia, la normativa que regula los límites máximos permisibles de material particulado menor a 2,5 micras (PM2.5) en el aire ambiente, es la Resolución 2254 de 2017 del Ministerio de Ambiente y Desarrollo Sostenible. Esta Resolución establece los estándares de calidad del aire para proteger la salud humana y el ambiente.
Según esta norma, los límites para este contaminante (PM2.5) son:   
•	Anual: 25 µg/m³    
•	24 horas (diario): 37 µg/m³

**Objetivo General**: Evaluar la contaminación ambiental por  material particulado PM 2.5 en la población de Soacha   
**Objetivos especificos**:   
* Analizar la información y sus indicadores espaciales
* Identificar las zonas de riesgo por contaminación atmosférica

**Insumos**:    
•	Concentraciones de PM2.5 en las estaciones de bajo costo instaladas en el municipio de Soacha, lo anterior para el mes de marzo. Fuente de datos: Servidor API de Aire Ciudadano      
•	Ubicación de las estaciones de bajo costo instaladas en el municipio de Soacha. Fuente de datos: Servidor API de Aire Ciudadano    
•	Mapa de uso de suelo del municipio de Soacha. Fuente de datos: POT del municipio     
•	Ubicación de centros medicos del municipio. Fuente de datos: Colombia en mapas   
•	Resolución 2254 de 2017

**Procedimientos**:   
•	Análisis estadistico y de las concentraciones de PM2.5   
•	Elaboración de raster de concentración de PM2.5 en el municipio, con ayuda de la herramienta Kriging   
•	Clasificación de exposición de la contaminación de PM2.5, teniendo como insumo el mapa de uso del suelo    
•	Clasificación de vulnerabilidad por la contaminación de PM2.5, teniendo como insumo el mapa de uso del suelo   
•	Clasificación de vulnerabilidad por la contaminación de PM2.5, teniendo como insumo la ubicación de los centros medicos del municipio      
•	Cálculo y análisis de riesgo por contaminación de PM2.5   

**Estructura**
- Docs   
- Notebooks:   
•	Analisis_Amenaza: Se realiza el análisis de la amenaza por contaminación atmosferica, teniendo como insumo los valores de concentración de PM2.5    
•	Analisis_Concentracion: Se realiza el análisis de la concentración de las diferentes estaciones y su comparación con la normativa    
•	Analisis_Datos: Se realiza el análisis estadistico a los datos   
•	Analisis_Exposicion: Se realiza el análisis y clasificación de la exposición de la contaminación de PM2.5, teniendo como insumo el mapa de uso del suelo    
•	Analisis_Riesgo: Se realiza el cálculo y análisis de riesgo por contaminación de PM2.5    
•	Analisis_Vulnerabilidad: Se realiza el análisis y clasificación de la vulnerabilidad por contaminación de PM2.5, teniendo como insumo el mapa de uso del suelo y la ubicación de los centros medicos del municipio          
- Presentación   
- Resultados   
- src


