# Ascenso y Caida de los Grandes Imperios de la Historia

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-green)
![Kaggle](https://img.shields.io/badge/Datos-Kaggle-20BEFF)
![Historia](https://img.shields.io/badge/Tema-Historia-brown)
![Estado](https://img.shields.io/badge/Estado-Completo-brightgreen)

---

## Descripcion

Este proyecto analiza **168 imperios historicos** a lo largo de
**4500 anos de historia**, desde el Imperio Elam (-2500) hasta
los ultimos imperios coloniales del siglo XX. A traves de series
de tiempo, visualizaciones historicas y Machine Learning,
se identifican patrones en el surgimiento, expansion y colapso
de las grandes civilizaciones de la humanidad.

> *"Los imperios que priorizaron el comercio duraron mas
> que los que priorizaron la expansion territorial"*

---

## Objetivos

- Analizar la duracion y extension de los grandes imperios
- Identificar patrones temporales en surgimientos y caidas
- Modelar la tendencia historica con regresion polinomial
- Clasificar imperios por perfil de poder usando K-Means
- Comunicar 4500 anos de historia con visualizaciones

---

## Preguntas que responde este analisis

1. Cuales fueron los imperios mas longevos y extensos?
2. En que siglos surgieron y cayeron mas imperios?
3. Que factores determinaron la duracion de un imperio?
4. Que perfiles naturales existen entre los grandes imperios?
5. Puede un modelo capturar la tendencia historica imperial?

---

## Visualizaciones principales

| Grafico | Descripcion |
|---------|-------------|
| ![longevos](images/top15_longevos.png) | Top 15 imperios mas longevos |
| ![extensos](images/top15_extensos.png) | Top 15 imperios mas extensos |
| ![region](images/imperios_por_region.png) | Imperios por region geografica |
| ![era](images/imperios_por_era.png) | Imperios por era historica |
| ![timeline](images/linea_tiempo.png) | Linea de tiempo de los 20 grandes imperios |
| ![serie](images/serie_tiempo_imperios.png) | Serie de tiempo 4500 anos |
| ![ciclo](images/surgimiento_vs_caida.png) | Surgimiento vs caida por siglo |
| ![regresion](images/regresion_polinomial.png) | Regresion polinomial historica |
| ![poder](images/perfiles_poder.png) | Clasificacion por perfil de poder |

---

## Machine Learning

### Series de Tiempo — Regresion Polinomial

| Metrica | Valor |
|---------|-------|
| Grado del polinomio | 4 |
| R² | 0.8944 |
| Variacion explicada | 89.4% |
| Rango temporal | -2500 a 2000 |

### Clustering — Perfiles de Poder

| Perfil | Duracion | Territorios | Comercio |
|--------|----------|-------------|---------|
| Imperio Regional | 272 años | 6 | 13% |
| Gran Imperio Territorial | 406 años | 27 | 4% |
| Imperio Comercial | 448 años | 8 | 67% |

### Hallazgo clave
Los imperios con mayor actividad comercial (Cluster 2)
fueron los mas longevos — superando incluso a los grandes
imperios territoriales en anos de duracion.

---

## Estructura del proyecto
```
imperios-historicos/
│
├── images/
│   └── (todas las visualizaciones)
│
├── Analisis_Imperios_Historicos.ipynb
├── README.md
└── requirements.txt
```

---

## Tecnologias utilizadas

- **Python 3.12**
- **Pandas** — manipulacion y series de tiempo
- **Matplotlib / Seaborn** — visualizacion historica
- **Scikit-learn** — Regresion Polinomial, K-Means, PCA
- **Google Colab** — entorno de desarrollo
- **GitHub** — control de versiones

---

## Como ejecutar el proyecto

1. Clona el repositorio:
```bash
git clone https://github.com/George1902/imperios-historicos.git
```

2. Instala las dependencias:
```bash
pip install -r requirements.txt
```

3. Descarga el dataset desde Kaggle:
   [World Empires Dataset](https://www.kaggle.com/datasets/stealthtechnologies/world-empires-dataset)
   y guardalo como `imperios.csv`

4. Abre el cuaderno en Google Colab o Jupyter

---

## requirements.txt
```
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

## Fuente de datos

**World Empires Dataset**
Kaggle — Stealth Technologies
Dataset: https://www.kaggle.com/datasets/stealthtechnologies/world-empires-dataset

---

## Autor

**Jorge Ojeda**
Estudiante — Oracle Next Education (ONE) — Alura LATAM
Especializacion: Ciencia de Datos
2026

---

## Licencia

Proyecto de uso educativo y libre distribucion.
Los datos estan disponibles publicamente en Kaggle.
