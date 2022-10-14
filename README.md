# Calculo altura  construcciones

Obtener los ficheros MDS Y MDT originales del centro de decargas

http://centrodedescargas.cnig.es/CentroDescargas/index.jsp#


Calculo y creacion del fichero alturas.asc calculando la diferencia de los ficheros MDT - MDS.

Los ficheros MDS y MDT es un recorte de los originales del centro de descargas de CNIG y deben tene el mismo numero de filas y columnas

El recorte de ASC original se hace en QGIS 
GDAL --> Extracción raster --> Cortar ráster por capa

### Estadisticas raster a vectorial

QGIS --> Analisis Raster --> Estadisticas de zona

Calculamos las estadisticas de la capa raster de las alturas para cada parcela catastral vectorial superpuesta
