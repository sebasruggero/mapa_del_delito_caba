# Delitos CABA 2016-2021 con Análisis Hexagonal (H3)

![Delitos CABA](/img/h3Delitos.png)

Este proyecto utiliza la biblioteca H3 para realizar análisis hexagonales sobre los delitos en la Ciudad Autónoma de Buenos Aires. El análisis se basa en datos recopilados de 2016 a 2021.

**[Enlace al Notebook en Colab](https://colab.research.google.com/github/sebasruggero/delitosCabaH3/blob/main/Delitos_Caba_2016_2021_H3.ipynb)**

## Descripción

Este script en Python procesa un conjunto de datos de delitos en CABA, transforma las coordenadas a índices hexagonales H3 y visualiza la densidad delictiva en un mapa interactivo.

## Contenido del Script

El script realiza las siguientes tareas:

1. Carga y procesa el conjunto de datos desde un archivo CSV.
2. Limpia y transforma los datos, eliminando valores no numéricos y guardando el conjunto de datos procesado.
3. Utiliza H3 para convertir las coordenadas de latitud y longitud en índices hexagonales.
4. Visualiza la densidad de delitos en un mapa interactivo utilizando Folium y H3.

## Requisitos

Asegúrate de tener instaladas las bibliotecas necesarias ejecutando los siguientes comandos:

```bash
!pip install h3
!pip install folium
!pip install ipyleaflet ipywidgets streamlit
```

## Cómo Usar

1. Ejecuta el script en un entorno que cumpla con los requisitos.
2. Selecciona el tipo de delito y el estilo de mapa a través de widgets interactivos.
3. Observa la visualización de la densidad delictiva en el mapa.

## Enlaces Útiles

- [Enlace al conjunto de datos original](https://drive.google.com/file/d/1YUMD_j2rUItGeg4vVrZPZ8hdZ87K5UfI/view?usp=sharing)
- [Enlace al conjunto de datos procesado](https://drive.google.com/file/d/1nxIwbjSOsaOrQN1BIDwUu9ZmToT1Hx0w/view?usp=sharing)

## Autor

[Sebastian Ruggero]

