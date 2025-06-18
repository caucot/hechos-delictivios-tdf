# Predeccion de hechos delictivos

## Objetivo General
Desarrollar un modelo de Aprendizaje Automático que permita predecir el nivel delictivo mensual (bajo, medio o alto) en la provincia de Tierra del Fuego, a partir de variables demográficas y socioculturales registradas.

### Objetivos Específicos:
- Identificar las variables más influyentes en la ocurrencia de hechos
delictivos.
- Clasificar cada mes según su nivel delictivo utilizando técnicas de
clasificación supervisada.


## Contexto de la Problematica
Tierra del Fuego es una de las provincias más australes y con menor densidad poblacional de Argentina. A menudo es percibida como una zona segura, con bajos niveles de criminalidad. Sin embargo, esta percepción puede verse afectada por factores como el crecimiento poblacional, variaciones estacionales (turismo, migraciones internas) y cambios sociales y económicos. La predicción del nivel resultaría útil para entidades de seguridad para aumentar la seguridad en ciertas temporadas.

## Problema de clasificación
El modelo de clasificación busca categorizar un mes determinado dentro de una de tres clases posibles: Nivel Bajo de criminalidad, Nivel Medio de criminalidad y Nivel alto de criminalidad.

Modelos de clasificación que se podrían emplear: Árbol de decisión, K-Nearest Neighbors, SVM.
## Estructura del proyecto

```text
hechos-delictivios-tdf/
│── data/
│   ├── raw/                # Datos sin procesar, en su estado original
│   ├── processed/          # Datos limpios y transformados para análisis
│   ├── interim/            # Datos intermedios o en proceso de transformación
│   ├── external/           # Datos externos de referencia
│── docs/                   # Documentación del proyecto 
│── models/                 # Modelos del proyecto
│── notebooks/              # Jupyter notebooks de limpieza, analisis y modelos
├── references/             # Artículos, papers, papers técnicos o benchmarks
│── reports/
│   ├── figures/            # Imágenes y gráficos generados
│── src/                    # Código fuente del proyecto
│── .gitattributes          # Atributos de git
│── .gitignore              # Archivos y carpetas a ignorar en Git
│── LICENSE                 # Licencia del proyecto
│── README.md               # Descripción general del repositorio
```
