# Trabajo Práctico Especial - Fundamentos de la Ciencia de Datos

Este repositorio contiene el trabajo práctico especial del Grupo 01, realizado en el marco de la materia **Fundamentos de la Ciencia de Datos** (2025).

## Integrantes

* Rojas, Tomas Alejandro
* Campo Zambotti, Agustin

## Contenido del repositorio

- `TPE.ipynb`: Notebook de Jupyter con todo el análisis de datos y las hipótesis planteadas.
- `Informe_TPE.pdf`: Informe escrito con hallazgos, discusión y conclusiones.
- `requirements.txt`: Archivo con las librerías necesarias para ejecutar la notebook.
- `README.md`: Este archivo, con instrucciones de uso y ejecución.
- `siniestros-2022.csv`: Conjunto de datos utilizado para el análisis.

## Dataset

El dataset principal (`siniestros-2022.csv`) recopila información sobre siniestros registrados en distintas **autopistas porteñas**. Incluye variables clave como:

* Hora del siniestro
* Tipo de vehículo involucrado y cuantos
* Severidad (lesionados y fallecidos)
* Características del trazado (bandas y ramales)

## Requisitos previos

- Python 3.10 o superior
- Jupyter Notebook, JupyterLab o Visual Studio Code (con la extensión de Jupyter).

## Pasos de instalación

Sigue estos pasos para configurar el entorno local y ejecutar el proyecto:

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/tomito9669/TPEspecial-FCD-Siniestros-BSAS.git
    ```

2.  **Moverse a la carpeta del proyecto:**
    ```bash
    cd TPEspecial-FCD-Siniestros-BSAS
    ```

3.  **Crear un entorno virtual:**
    ```bash
    python -m venv env
    ```

4.  **Activar el entorno virtual:**

    * En Windows (PowerShell/CMD):
        ```bash
        .\env\Scripts\activate
        ```
    * En macOS/Linux:
        ```bash
        source env/bin/activate
        ```

5.  **Instalar las dependencias:**
    ```bash
    pip install -r requirements.txt
    ```