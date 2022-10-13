# Ejemplo práctico de la guía metodológica para identificar zonas libres de conflicto ambiental
## Equipo
Guía elaborada por el Equipo QGIS-Warriors ganador del [Datajam 2022](https://participa.datalat.org/conferences/datajam2022?locale=es), [Categoría 1](https://docs.google.com/spreadsheets/d/1nzGWhM-CD_C9RntCxUfvotcMMtHusdEdj4DyOXPV7AI/edit?usp=sharing) Dateando por el agua
- [Danny Vasco](https://github.com/Danny-Vasco) - [Click para revelar email](mailto:marcelovasco4@gmail.com)
- [Karen Parra](https://github.com/KarenParraA/) - [Click para revelar email](mailto:kren.parra9@gmail.com)
- [José Jácome](https://github.com/josejacomeb/)

## Con el apoyo de

<a href="https://datalat.org/" target="_blank"><img src="https://datalat.org/wp-content/uploads/2021/08/cropped-Logo300ppi.jpg" style="max-height: 100px; max-width: 100px;"></a>
<a href="https://hubuio.ec/" target="_blank"><img src="https://hubuio.ec/wp-content/uploads/2021/09/04-25pr-e1632715032810.png" style="max-height: 100px; max-width: 100px;"></a>
<a href="https://www.gobiernoabierto.ec/" target="_blank"><img src="https://www.gobiernoabierto.ec/wp-content/uploads/2018/10/logo-GAE-500-01.jpg?x58984" style="max-height: 100px; max-width: 100px;"></a>
<a href="https://www.ambiente.gob.ec/" target="_blank"><img src="https://www.ambiente.gob.ec/wp-content/uploads/2012/09/LOGO6.jpg" style="max-height: 100px; max-width: 100px;"></a>


## Descripción
Programa modelo para limpiar, explorar y visualizar bases de datos de recursos hídricos a base de librerías de software libre. Además del análisis de proyección cartográfica en Sistemas de Información Geográfica (SIG), para a yudar evaluación del otorgamiento de una autorización hídrica para una industria que no presente conflicto ambiental. 

## Software utilizado
- QGIS v3.26 [Link de descarga](https://qgis.org/es/site/forusers/download.html)
- Python >= 3.8 [Link Descarga Python](https://www.python.org/downloads/release/python-3106/)
- Numpy v1.23.2 - Librería de análisis científico de Python [Página Oficial](https://numpy.org/)
- Pandas v1.4.3 - Librería de análisis y manipulación de datos para Python [Página Oficial](https://pandas.pydata.org/)
- Jupyterlab v3.4.5 - Interfaz amigable basada en Web para Python [Página Oficial](https://jupyter.org/)
- Openpyxl v3.0.10 - Librería de Python para leer/escribir archivos de excel [Página Oficial](https://openpyxl.readthedocs.io/en/stable/)
- Excel: Filtrado, visualizzación de datos gráficamente y uso de tablas dinámicas

## Ejecución de los archivos
### ¿Cómo ejecutar los Notebooks de Python?
- Instalar Python >= 3.8 desde la página oficial, por ejemplo seleccionar Windows installer (64-bit) para Windows 
- Instalar la aplicación Git para Windows o Linux [Link descarga](https://git-scm.com/downloads)
- Descargar este repositorio en una carpeta seleccionada en su computador a través del comando `git clone https://github.com/KarenParraA/DataJam.git`
- Entrar via terminal `CMD` en Windows o `Bash` en Linux y entrar a la carpeta `DataJam`
- Instalar las dependencias del proyecto via el comando `pip install -r requirements.txt`
- Escribir el siguiente comando para abrir los notebooks de la `jupyter lab`
- Abrir el Notebook [Limpieza_Datos.ipynb](https://github.com/KarenParraA/DataJam/blob/main/Limpieza_Datos.ipynb) para verificar el proceso de limpieza de datos
- Abrir el Notebook [Visualizacion_Datos_filtrados.ipynb](https://github.com/KarenParraA/DataJam/blob/main/Visualizacion_Datos_filtrados.ipynb) para verificar el proceso de Visualización de Datos
### ¿Cómo abrir los datos de Información Geográfica?
- Instalar la versión de QGIS indicada en el software utilizado
- Abrir el archivo que se encuentra en la carpeta `QGIS_DATAJAM-RETO1/DATAJAM DATEANDO POR EL AGUA.qgz` a través del programa QGIS en el Menú  *Proyecto > Abrir > Seleccionar el archivo*
- El punto rojo significa el Punto donde se quiere instalar la fábrica textil y los puntos amarillos representan las Localizaciones de las Autorizaciones Hídricas

### ¿Cómo abrir el archivo de Análisis?

## Resultados
![Resultados QGIS](https://github.com/KarenParraA/DataJam/blob/main/INDUSTRIA%20TEXTIL.png?raw=true)

## Licencia
[GNU GLP v3](https://github.com/KarenParraA/DataJam/blob/main/LICENSE.md)