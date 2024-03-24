# Entornos virtuales
Utilice un entorno virtual para gestionar las dependencias de su proyecto, tanto en desarrollo como en producción.

¿Qué problema resuelve un entorno virtual? Cuantos más proyectos de Python tenga, más probable es que necesite trabajar con diferentes versiones de las bibliotecas de Python, o incluso con el mismo Python. Las versiones más nuevas de bibliotecas para un proyecto pueden romper la compatibilidad en otro proyecto.

Los entornos virtuales son grupos independientes de bibliotecas de Python, una para cada proyecto. Los paquetes instalados para un proyecto no afectarán a otros proyectos ni a los paquetes del sistema operativo.

Python viene incluido con el ***venv módulo*** para crear entornos virtuales.
## Crear un entorno
Cree una carpeta de proyecto **venv** dentro de:
 **Windows** 
```
> mkdir myproject
> cd myproject
> py -3 -m venv venv
```
Tambiém puedes usar este otro comandando, si no te funcionea el primero para crear el entorno virtual
```
python -m virtualenv venv
```
## Activar el entorno
Puede moverte hasta la ruta con: **CD Script** ya dentro, puedes es cribir el comando **dir** para ver todos los archivos que contiene adentro la carpeta **Scripts**
veras el **activate.bat** o 
para ir directo copia y pega el sigiente comando y no te olvide de dar **Enter** para ejecutar el comando, !Bueno eso creo que lo sabes jajaja¡:
```
venv\Scripts\activate.bat
```
Su indicador de shell cambiará para mostrar el nombre del entorno activado.
# Iniciando un proyecto
Ya activado el entorno virtual debes salirte de ahí, hacia **venv** con el comando **CD..** te regresa ul paso atrás.
Ahora supongamos que vas a inicial una proyecto web usando el **framework de Flask** los primero que debes hacer es instalarlo con el comando.
```
pip install Flask
```
## Instalando las dependecias del proyecto.
>Tenga en cuenta que Python se usa para una gran cantidad de propósitos diferentes, y la forma precisa en que desea administrar sus dependencias puede cambiar en 
función de cómo decida publicar su software.
Con el comando:
```
pip freeze > requirements.txt
```
Vea estas referencias te puede ayudar mucho:

[Pypi.org](https://pypi.org/project/virtualenv/)
-
[flask](https://flask.palletsprojects.com/en/2.2.x/installation).
-
[docs.python-guide.org](https://docs.python-guide.org/dev/virtualenvs).
-
