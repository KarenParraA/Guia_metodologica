# DataJam - QGis Warriors
## Integrantes
- [Danny Vasco](https://github.com/Danny-Vasco) - [Click para revelar email](mailto:marcelovasco4@gmail.com)
- [Karen Parra](https://github.com/KarenParraA/) - [Click para revelar email](mailto:kren.parra9@gmail.com)
- [José Jácome](https://github.com/josejacomeb/)


## Descripción
Manejar y limpiar bases de datos de recursos hídricos a base de librerías de software libre, proyección cartográfica en Sistema SIG, evaluación de una zona adecuada de una industria y evaluación del número de autorizaciones hídricas. 

## Software utilizado
- QGIS v3.22 [Link de descarga](https://qgis.org/es/site/forusers/download.html)
- Python >= 3.8 [Link Descarga Python](https://www.python.org/downloads/release/python-3106/)
- Numpy v1.23.2 - Librería de análisis científico de Python [Página Oficial](https://numpy.org/)
- Pandas v1.4.3 - Librería de análisis y manipulación de datos para Python [Página Oficial](https://pandas.pydata.org/)
- Jupyterlab v3.4.5 - Interfaz amigable basada en Web para Python [Página Oficial](https://jupyter.org/)
- Openpyxl v3.0.10 - Librería de Python para leer/escribir archivos de excel [Página Oficial](https://openpyxl.readthedocs.io/en/stable/)

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
![Resultados QGIS](INDUSTRIA TEXTIL.png)

## Licencia
GNU GLP v3