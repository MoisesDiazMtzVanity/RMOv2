# project

Proyecto para leer, procesar y reportar datos.

## Instalación

1. Abre una terminal en la carpeta raíz del repositorio.
2. Activa el entorno virtual (si no está activo):
	```pwsh
	.\venv\Scripts\Activate.ps1
	```
3. Instala las dependencias:
	```pwsh
	pip install -r project\requirements.txt
	```

## Estructura
- `main.py`: Script principal
- `requirements.txt`: Dependencias
- `data/input`: Datos de entrada
- `data/output`: Resultados generados
- `src/reader.py`: Lectura de datos
- `src/processor.py`: Procesamiento
- `src/reporter.py`: Generación de reportes

## Uso

Ejecuta el archivo principal:
```pwsh
python project\main.py
```

