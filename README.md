# Proyecto de Detección de Lavado de Dinero
---

## Descripción
Este proyecto utiliza modelos de Machine Learning para detectar transacciones sospechosas asociadas a lavado de dinero.

---

## Cómo ejecutar

1. Clonar el repositorio:
git clone https://github.com/tsezaro/tp-final-ml-lavado-dinero.git

---

## Requisitos

- Python 3.12.7
  
## Dataset
Se utilizó el dataset **IBM AMLSim (Anti Money Laundering)**, que simula un sistema bancario real con millones de transacciones.

Archivos principales:
- `HI-Small_Trans.csv` → transacciones
- `HI-Small_accounts.csv` → información de cuentas

## Descargar Datasets (IMPORTANTE)
Dado el tamano de los datasets se dificulta el poder cargarlos directamente acá. 
Comparto el enlace para descargarlos: https://drive.google.com/drive/folders/1oZFYwdHx7s4-fS4s1zxl_v_KvLWYKw12?usp=sharing
Presetar atención a como estructurar la carpeta para ejecutar el archivo Jupyter.

---

## Metodología
El proyecto sigue la metodología CRISP-DM:

1. Comprensión del problema
2. Análisis exploratorio (EDA)
3. Preparación de datos
4. Feature engineering
5. Modelado
6. Evaluación

---

## Modelos utilizados
- Regresión Logística (baseline)
- Random Forest
- LightGBM (modelo final)

---

## Resultados
- ROC-AUC: > 0.98
- Recall: > 85%

El modelo demuestra una alta capacidad de detección de transacciones sospechosas.

---

## Librerías utilizadas
- pandas
- numpy
- scikit-learn
- lightgbm
- matplotlib
- seaborn

