# Mi Proyecto de Geometría

Este proyecto contiene clases para representar figuras geométricas en Python.

## Estructura del Proyecto

- `src/`: Código fuente del proyecto.
- `README.md`: Descripción del proyecto.
- `requirements.txt`: Dependencias necesarias.


## ver si esta instalado
 
 git --version

## Cómo Ejecutar

Para ejecutar el programa, navega a la carpeta `src` y ejecuta:

- MacOS

```bash
python3 src/main.py
```
- Windows
```
python src/main.py
```
# para hacer correr  el proyecto de python
 

## Paso 1: Instalar `virtualenv` (opcional)

Si no tienes `virtualenv` instalado, puedes hacerlo con pip. Aunque desde Python  en adelante, puedes usar el módulo `venv` que viene incluido.

### Usando `virtualenv`

bash
```
pip install virtualenv 
```

## Paso 2: Crear un Entorno Virtual

### Usando `venv`

Para crear un entorno virtual con `venv`, ejecuta el siguiente comando:

bash

Copiar código

`python -m venv nombre_del_entorno` 

o, si usas Python 3:

bash

Copiar código

`python3 -m venv nombre_del_entorno` 

### Usando `virtualenv`

Si decidiste usar `virtualenv`, el comando es similar:

bash

Copiar código

`virtualenv nombre_del_entorno` 

## Paso 3: Activar el Entorno Virtual

Para empezar a usar el entorno virtual, necesitas activarlo.

### En Windows

bash

Copiar código

`nombre_del_entorno\Scripts\activate` 

### En macOS y Linux

bash

Copiar código

`source nombre_del_entorno/bin/activate` 

Después de activar el entorno, deberías ver el nombre del entorno al inicio de la línea de tu terminal.

## Paso 4: Instalar Dependencias

Con el entorno virtual activado, puedes instalar las bibliotecas que necesites usando pip. Por ejemplo:

bash

Copiar código
```
pip install nombre_del_paquete 
```
## Paso 5: Desactivar el Entorno Virtual

Cuando hayas terminado de trabajar, puedes desactivar el entorno virtual con el siguiente comando:

bash

Copiar código

`deactivate` 