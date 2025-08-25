# project

Proyecto para leer, procesar y reportar datos.

## Instalación

1. Clona o descarga este repositorio.
2. Abre una terminal en la carpeta raíz del proyecto.
3. Crea un entorno virtual:
	```pwsh
	py -3 -m venv venv
	```
4. Activa el entorno virtual:
	- En Windows PowerShell:
	  ```pwsh
	  .\venv\Scripts\Activate.ps1
	  ```
	- En CMD:
	  ```cmd
	  venv\Scripts\activate.bat
	  ```
5. Instala las dependencias:
	```pwsh
	pip install -r project\requirements.txt
	```

## Estructura
- `project/main.py`: Script principal
- `project/requirements.txt`: Dependencias
- `project/data/input`: Datos de entrada
- `project/data/output`: Resultados generados
- `project/src/reader.py`: Lectura de datos
- `project/src/processor.py`: Procesamiento
- `project/src/reporter.py`: Generación de reportes

## Uso

Ejecuta el archivo principal:
```pwsh
python project\main.py
```

# RMOv2

Repositorio principal para el proyecto de reporte de datos.

## Instalación general

1. Clona o descarga este repositorio.
2. Abre una terminal en la carpeta raíz (`RMOv2`).
3. Crea un entorno virtual:
	 ```pwsh
	 py -3 -m venv venv
	 ```
4. Activa el entorno virtual:
	 - En Windows PowerShell:
		 ```pwsh
		 .\venv\Scripts\Activate.ps1
		 ```
	 - En CMD:
		 ```cmd
		 venv\Scripts\activate.bat
		 ```
5. Instala las dependencias del proyecto principal:
	 ```pwsh
	 pip install -r project\requirements.txt
	 ```

## Estructura
- `project/`: Carpeta principal del proyecto de reporte
	- `main.py`: Script principal
	- `requirements.txt`: Dependencias
	- `data/input`: Datos de entrada
	- `data/output`: Resultados generados
	- `src/reader.py`: Lectura de datos
	- `src/processor.py`: Procesamiento
	- `src/reporter.py`: Generación de reportes

## Uso

Para instrucciones específicas del proyecto, consulta el archivo `README.md` dentro de la carpeta `project`.

