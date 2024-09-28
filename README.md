# Cookiecutter: Plantilla para Proyectos con Python
<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/128/3344/3344372.png" alt="Texto alternativo">
</p>

__Estructura de carpeta para proyectos de automatización, ciencia de datos, web scraping y demás, con un facil control y mantenimiento.__

## Instalación de Cookiecutter 🍪
1. Agregamos el canal conda-forge para que conda pueda buscar la librería cookiecutter allí.
```bash
conda config --add  channels conda-forge
```

2. Creamos un entorno virtual para instalar la librería.
```bash
conda create --name env_cookiecutter cookiecutter=1.7.3
```


## Instalar la plantilla 📄
1. Activamos el entorno virtual
```bash
conda activate env_cookiecutter
```
2. Creamos la plantilla en la carpeta deseada
```bash
cookiecutter https://github.com/NeicerVB/Plantillas_Py.git
```