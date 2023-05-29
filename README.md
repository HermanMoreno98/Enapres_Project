# Indicadores de saneamiento ENAPRES

Script para extraer datos desde la web del INEI y calcular indicadores de cobertura de agua y alcantarillado en el Perú durante los años 2013-2022 📈

## Metodología para extracción de datos desde la pagína web y preprocesamiento

A través de la herramienta de inspección de desarrollador del navegador se ubicó el enlace de cada módulo SPSS, Stata o CSV, en función a ENAPRES.
Luego, se desarrolló un proceso iterativo desde python, mediante el menejo del directorio, para descargar y guardar los archivos .sav de interés.
Finalmente, se realiza el preprocesamiento de los módulos 100 y 200 para obtener indicadores tanto a nivel de hogares y población.

## Visualización

Se realizan gráficas utilizando las librerías de seaborn, plotly y geopandas.
Para la elaboración del mapa de cobertura a nivel nacional, se realizó un procedimiento de extracción del shapefile de los departamentos del Perú desde la web.


## Enlaces
<li><a href="https://proyectos.inei.gob.pe/microdatos/Consulta_por_Encuesta.asp?CU=19558/" target="_blank">Enlace a INEI</a></li>
<li><a href="https://www.geogpsperu.com/2018/02/limite-departamental-politico-shapefile.html" target="_blank">Enlace a ShapeFile</a></li>
