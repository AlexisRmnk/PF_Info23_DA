# Proyecto Final - Data Analytics - Especializacion Informatorio 2023
Repositorio creado para la etapa 3 - Especializacion en Data Analytics - para el Informatorio. Agosto 2023.

## Colaboradores
* [Acosta, Sergio Gustavo](https://github.com/sergioacos)
* [Fernández, Gustavo Nicolás](https://github.com/Gu57avo)
* [Nichiporuk, Fernanda](https://github.com/FernandaNichiporuk)
* [Ojcius, Gabriela](https://github.com/GabrielaOjcius/GabrielaOjcius)
* [Romaniuk, Alexis Agustin](https://github.com/AlexisRmnk)
* [Svenson, Alex](https://github.com/Alexsvn1)
* [Turbay, Julieta Lourdes](https://github.com/juliturbay)

## Instrucciones 
A continuacion se indica como realizar la instalacion de los programas necesarios junto a la creacion del entorno virtual utilizando miniconda.
1. Descargar e instalar [python 3](https://www.python.org/downloads/).
2. Descargar e instalar [miniconda](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links) con el link correspondiente a su Sistema Operativo.
3. Descargar e instalar [Visual Studio Code](https://code.visualstudio.com/download) u otro editor de codigo preferido. Extensiones de VS CODE recomendadas: Jupyter, Python.
4. Clonar/descargar este repositorio en una carpeta. Ej: C:/Proyecto.
5. Acceder a la terminal de miniconda 'Anaconda Prompt (miniconda3)'.
	* Moverse a la carpeta del proyecto creada en el paso '4'.
	* Ejecutar el comando `conda env create -f environment.yml`
	* El entorno se llama 'env01'. Una vez creado, puede activar el entorno utilizando `conda activate env01` para instalar o revisar los paquetes que contiene. 
6. Desde VS CODE, abrir la carpeta del proyecto. Luego al abrir el archivo principal 'main.ipynb' seleccionar el Kernel Python de nuestro entorno recien creado.

Ya puede ejecutar el codigo desde VS CODE. No es necesario activar/desactivar el entorno desde miniconda para su utilizacion.

### Aclaraciones
Debe tener su API key de [OpenWeatherMap](https://openweathermap.org/api) necesaria en un archivo 'credenciales.py' en una constante 'API_KEY'.

Ej:
```python
API_KEY = '000aaa111bbb222ccc'
```

## Licencia
[MIT](https://choosealicense.com/licenses/mit/)
