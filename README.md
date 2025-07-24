# Telecom X – Análisis de Evasión de Clientes (Churn)

Este proyecto forma parte del desafío **Telecom X** del programa ONE – Oracle Next Education y Alura LATAM. Su objetivo es aplicar técnicas de ETL y análisis exploratorio de datos (EDA) para entender las causas detrás de la **evasión de clientes** en una empresa de telecomunicaciones.

---

## 🚀 Objetivos del proyecto

- Extraer y transformar datos desde una fuente JSON estructurada.
- Limpiar y aplanar los datos usando `pandas`.
- Realizar un análisis exploratorio de datos (EDA) con `seaborn` y `matplotlib`.
- Identificar variables que influyen en la decisión de los clientes de abandonar el servicio.
- Generar visualizaciones que permitan formular hipótesis para decisiones estratégicas.
- Entregar un dataset limpio y listo para análisis predictivo.

---

## 🛠️ Herramientas y tecnologías

- Python 3.13.1
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook / VSCode
- Git & GitHub

---

## 📁 Estructura del proyecto

telecom-x-churn-analysis/
├── data/
│ └── TelecomX_Data.json
├── docs/
│ └── TelecomX_diccionario.md
├── notebooks/
│ └── TelecomX_LATAM.ipynb
├── requirements.txt
└── README.md


---

## 📊 Análisis exploratorio (EDA)

El análisis identificó varios patrones significativos:

- El **contrato mensual** tiene alta tasa de churn frente a contratos anuales.
- El método de pago con **cheque electrónico** se asocia a mayor evasión.
- Clientes con **bajo tenure** (menos tiempo en la empresa) tienden a abandonar más rápido.
- Los **cargos mensuales más altos** también muestran relación con la evasión.
- No se detectó diferencia de churn relevante por género.

Para más detalles, consulta el notebook [`TelecomX_LATAM.ipynb`](notebooks/TelecomX_LATAM.ipynb).

---

## 📦 Requisitos

Instala las dependencias con:

```bash
pip install -r requirements.txt

📌 Conclusiones y recomendaciones
Consulta la sección 📝 Informe Final en el notebook para ver las hipótesis estratégicas y propuestas de acción basadas en los hallazgos del análisis.

🤝 Autor
Yuseth Edwin Serrano Acevedo
Analista de datos en formación | ONE – Oracle Next Education
GitHub