# Introducción a la Estadística para Data Scientist

Colección de notebooks Jupyter con los temas de estadística para ciencia de datos: regresión, combinatoria, probabilidad, variables aleatorias, muestreo, inferencia y contrastes de hipótesis.

## Visibilidad y rama
- Público.
- Rama por defecto: no verificado (no se detectó `.git` accesible).

## Stack
- Python en Jupyter Notebook (`.ipynb`).
- Librerías vistas en los imports: NumPy, Matplotlib, `math`.
- Sin `requirements.txt`, `environment.yml` ni `pyproject.toml`: las versiones no están fijadas.

## Estructura
- `01d-Regresion.ipynb` y `01d-Regresion-Ejercicio.ipynb`: regresión lineal (teoría y ejercicio).
- `02-combinatoria.ipynb`: combinatoria.
- `03-probabilidad.ipynb` y `03-probabilidad-partial.ipynb`: probabilidad (versión completa y parcial).
- `04a-variable-aleatoria-discreta.ipynb` y `04b-variable-aleatoria-continua.ipynb`: variables aleatorias.
- `05a-Muestreo.ipynb`: muestreo.
- `06-Inferencia.ipynb`: inferencia estadística.
- `07a-Contrastes de Hipotesis.ipynb`: contrastes de hipótesis (el nombre tiene espacios: escapar en la shell).
- `Tiempo de natacion.ipynb`: notebook de regresión con datos de natación.
- `rioTimes.csv`: datos de tiempos (uso exacto en los notebooks: no verificado).

## Comandos
- No hay scripts de instalación, test ni build.
- Ejecutar: `jupyter notebook` (o `jupyter lab`) en la carpeta del repo. Requiere NumPy y Matplotlib (no verificado: sin lista de versiones).

## Configuración
- Ninguna variable de entorno ni fichero de configuración.

## Convenciones para agentes
- Los notebooks guardan las salidas (incluidas imágenes PNG en base64): los diffs son muy grandes. Si se editan, conviene no regenerar todas las salidas.
- Respetar la numeración de los notebooks, que indica el orden del temario.
- Mantener el idioma (español) de textos y comentarios.

## Estado
- No hay tests.
- Los notebooks contienen salidas embebidas y no hay forma de verificar sin ejecutarlos que el código siga funcionando.
- Hay un notebook parcial (`03-probabilidad-partial.ipynb`) junto a la versión completa: no está claro cuál es la vigente.
