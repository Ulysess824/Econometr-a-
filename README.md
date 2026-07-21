# Econometría

Repositorio de estudio y práctica de econometría: notebooks de Python y scripts de Stata que cubren desde fundamentos estadísticos hasta evaluación de impacto de políticas.

## Contenido

| Notebook | Descripción |
|---|---|
| [`Supuestos de una regresion lineal.ipynb`](notebooks/Supuestos%20de%20una%20regresion%20lineal.ipynb) | Análisis exploratorio de datos y verificación de los supuestos clásicos de la regresión lineal simple (linealidad, homocedasticidad, normalidad de residuos, etc.). |
| [`Proximidades.ipynb`](notebooks/Proximidades.ipynb) | Medidas de proximidad, similaridad y disimilaridad entre observaciones, con sus propiedades matemáticas. |
| [`Practica de master - Evaluacion de Impacto.ipynb`](notebooks/Practica%20de%20master%20-%20Evaluacion%20de%20Impacto.ipynb) | Práctica de máster sobre evaluación de impacto, replicando en Python un análisis originalmente desarrollado en Stata. |

## Estructura del repositorio

```
Econometr-a-/
├── notebooks/   # Jupyter notebooks (Python) con el desarrollo teórico y práctico
├── python/      # Scripts y utilidades en Python
├── stata/       # Do-files de Stata
└── README.md
```

## Requisitos

Para ejecutar los notebooks se recomienda tener instalado:

- Python 3.9+
- Jupyter Notebook o JupyterLab
- Librerías habituales de análisis de datos: `numpy`, `pandas`, `matplotlib`, `scipy`, `statsmodels`, `scikit-learn`

Instalación rápida:

```bash
pip install numpy pandas matplotlib scipy statsmodels scikit-learn jupyter
jupyter notebook
```

## Uso

Clona el repositorio y abre los notebooks desde la carpeta `notebooks/`:

```bash
git clone https://github.com/ulysess824/econometr-a-.git
cd econometr-a-/notebooks
jupyter notebook
```

## Autor

Repositorio mantenido por [ulysess824](https://github.com/ulysess824).
