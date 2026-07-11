# Indicadores demográficos de los países del mundo
Dashboard que informa acerca de la población, promedio de esperanza de vida y mortalidad por cada mil niños de todos los páises del mundo. (actualizados a Noviembre del 2024)- Realizado en función de la BD brindada por el Tío Tech en el módulo 3 del curso de Power BI

Procedimiento:
1. Carga de archivos
   - Se importaron las 4 tablas de Excel para la realización del trabajo: Países, Población, Esperanza de Vida, Mortalidad Infantil

2. Modelado de datos:
   - En este caso, Países guardaba relación 1 a 1 con Población, Esperanza de Vida y Mortalidad Infantil mediante la llave país. Por lo cual se puede acceder a la información del resto de tablas.
  
3. Visualización:
   - Fueron utilizados los siguientes gráficos:
     - Matriz: Contiene información acerca de cada país, su población total, esperanza de vida y mortalidad infantil. Los valores en la fila se dividieron jerárquicamente en: Continentes --> Países.
     - TreeMap: Utilizado para comparar las proporciones entre las poblaciones de todos los países. Además, indica sobre el promedio de esperanza de vida en cada país.
     - Mapa: Localiza a todos los países del mundo y su mortalidad infantil por cada 1000 habitantes.
     - Filtros de segmentación: Permite filtrar los datos de las visualizaciones según el continente, tipo de esperanza de vida o cantidad poblacional 
