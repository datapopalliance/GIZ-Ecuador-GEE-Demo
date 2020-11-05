# GIZ-Ecuador-GEE-Demo
Demo de análisis de imágenes satelitales del satélite Sentinel-5p con ayuda de Google Earth Engine



## Instalación

Para correr esta presentacion,  se debe crear un ambiente de [Conda](https://docs.conda.io/en/latest/) con version de *Python 3.7*.  Una vez activado el nuevo ambiente de Conda, se deben instalar las paqueterías necesarias para que corra el archvio .ipynb. Estas paqueterias se encuentran en el archivo *requirements.txt* y se instalan corriendo el siguiente comando en la terminal.



```bash
pip install -r requirements.txt
```



Nota: para que el comando anterior funcione, uno debe de estar situado dentro de la terminal, en la carpeta donde se encuentra el archivo requirements.txt .



Una vez que se tiene el ambiente con las paqueterias necesarias, se puede ver el archivo dentro de jupyter corriendo el siguiente comando en la terminal:



```bash
jupyter-lab
```



Para saber mejor como funciona Jupyter Lab visite el siguiente [link](https://jupyterlab.readthedocs.io/en/latest/).



En caso de que se quiera ver el archivo .ipynb como presentacion, se deben instalar algunas extensiones de jupyter con el siguiente comando en la terminal:



```bash
pip install jupyter_contrib_nbextensions
```



Despues, se debe de correr el siguiente comando en la terminal dentro de la carpeta donde se encuentra el archivo .ipynb



```bash
jupyter nbconvert 01_imagenes_satelitales_para_el_estudio_de_contaminacion_aerea.ipynb --to slides --post serve
```



## html

En caso de que usted no maneje python, se puede clonar el repositorio y ver la presentación dándole click al archivo html que viene en el repositorio. Porfavor, no cambie el archivo html de carpeta porque, si no, no se van a poder ver algunas imágenes.