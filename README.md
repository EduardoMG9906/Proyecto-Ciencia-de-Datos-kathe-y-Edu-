# Proyecto-Ciencia-de-Datos-kathe-y-Edu

# Proyecto 1 — Visualizaciones exploratorias (EDA)  
**Dataset:** Breast Cancer Wisconsin (Diagnostic) — UCI Machine Learning Repository

## 1) Descripción general del proyecto
Este proyecto realiza un **análisis exploratorio** del conjunto de datos *Breast Cancer Wisconsin (Diagnostic)* con el fin de responder la pregunta:

**¿Cuál es la relación entre las características de los tumores y su malignidad en el conjunto de datos de cáncer de mama?**

A partir de variables morfológicas calculadas sobre imágenes de biopsias (FNA), se comparan los casos **Benignos (B)** y **Malignos (M)** mediante visualizaciones básicas:
- **Gráficos de barras** (distribución de la clase/diagnóstico).
- **Histogramas** (distribución de variables numéricas por clase).
- **Gráficos de dispersión** (relaciones entre variables y separación visual B vs M).
- **Boxplots** (comparación directa de variables entre clases).

**Notebook del proyecto:**  
`sp_1_Eduardo_Montoya_Katherine_Narvaez.ipynb`

**Fuente de datos:**  
Wolberg, W., Mangasarian, O., Street, N., & Street, W. (1993). *Breast Cancer Wisconsin (Diagnostic)* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B

## 2) Instrucciones para ejecutar los notebooks

### Opción A — Ejecutar con JupyterLab / Jupyter Notebook
1. Descarga o clona el proyecto.
2. Abre JupyterLab o Notebook.
4. Abre el archivo `sp_1_Eduardo_Montoya_Katherine_Narvaez.ipynb`.
5. Ejecuta las celdas **en orden** (de arriba hacia abajo).

comandos sugeridos: `pip install -r requirements.txt` y luego `jupyter lab` (o en VS Code abrir el .ipynb y ejecutar celda por celda). Si el dataset está en CSV separado por punto y coma, se debe cargar con `df = pd.read_csv("ruta/al/archivo.csv", sep=";")` y verificar que la ruta coincida con la ubicación del archivo en el equipo.

## 3) Nombres y correos institucionales de los estudiantes.

Estudiantes: **EDUARDO MONTOYA GUEVARA** (eduardo.montoyag@udea.edu.co) y **KATHERINE NARVAEZ GOEZ** (katherine.narvaez@udea.edu.co). 

## 4) Dependencias o librerías requeridas

Dependencias requeridas: **pandas**, **numpy**, **matplotlib**, **seaborn**; instalación rápida: `pip install pandas numpy matplotlib seaborn`; contenido opcional de `requirements.txt`: `pandas`, `numpy`, `matplotlib`, `seaborn`.

```bash
pip install -r requirements.txt
jupyter lab
