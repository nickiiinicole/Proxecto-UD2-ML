# 🏦 Predicción de Campaña de Marketing Bancario

![Status](https://img.shields.io/badge/Status-Finalizado-ff69b4)
![Python](https://img.shields.io/badge/Python-3.9-ff99ac)
![Library](https://img.shields.io/badge/Library-Scikit__Learn-d63384)

> **Proyecto Final - Aprendizaje Supervisado** > 

---

## Introducción

Este proyecto tiene como objetivo analizar y predecir el comportamiento de los clientes de un banco ante una campaña de marketing telefónico. La meta principal es identificar **qué clientes tienen mayor probabilidad de contratar un depósito a plazo fijo** (variable `y`).

El problema se aborda como una tarea de **Clasificación Binaria**, utilizando datos demográficos y económicos.

## Dataset y Variables

El dataset contiene información sobre llamadas telefónicas y perfiles de clientes. Algunas de las variables más relevantes analizadas son:

* **`duration`**: Duración de la última llamada (variable clave).
* **`euribor3m`**: Tasa euribor a 3 meses.
* **`job`**: Tipo de trabajo del cliente.
* **`housing` / `loan`**: Si el cliente tiene hipoteca o préstamos personales.

---

## Modelos Implementados

Para resolver el problema, he implementado y comparado tres algoritmos de aprendizaje supervisado:

### 1. K-Nearest Neighbors (KNN) 
Algoritmo basado en distancias. Busca a los clientes más "parecidos" (vecinos) para inferir si contratarán el servicio.
* *Preprocesamiento:* Escalado de datos (StandardScaler).

### 2. Árbol de Decisión (Decision Tree) 
Modelo "White Box" que permite visualizar las reglas de decisión explícitas.
* *Ventaja:* Alta interpretabilidad para explicar al negocio por qué se toma una decisión.

### 3. Regresión Logística 
El estándar estadístico para clasificación binaria.
* *Ventaja:* Proporciona la **probabilidad matemática** (0-100%) de éxito, no solo la clasificación.

---


## Herramientas Utilizadas

* **Lenguaje:** Python 
* **Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Seaborn (Estilo `husl`), Matplotlib
* **Machine Learning:** Scikit-Learn

---

##  Autora

**NickiNicole** *Estudiante de Machine Learning & Data Science*

---
