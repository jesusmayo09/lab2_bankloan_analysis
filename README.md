# 🏦 Análisis de Riesgo de Incumplimiento de Créditos Bancarios

![Status](https://img.shields.io/badge/status-completed-brightgreen)
![Python](https://img.shields.io/badge/python-3.7+-blue)
![ML](https://img.shields.io/badge/ML-Risk%20Analysis-orange)
![Colab](https://img.shields.io/badge/env-Google%20Colab-blue)
![License](https://img.shields.io/badge/license-MIT-green)

> **Análisis exploratorio de datos (EDA) y modelado de riesgo crediticio**, identificando perfiles de clientes de alto riesgo y patrones de incumplimiento en préstamos bancarios.

---

## 📋 Descripción del Proyecto

Este proyecto realiza un **análisis integral de riesgo crediticio** basado en datos históricos de clientes bancarios. El objetivo es identificar qué características demográficas y financieras predicen mejor la probabilidad de que un cliente **incumpla con su crédito** (Default = Sí).

**Aplicación:** Ayuda a instituciones financieras a:
- Evaluar riesgo crediticio de nuevos solicitantes
- Segmentar clientes por nivel de riesgo
- Identificar factores clave de incumplimiento
- Desarrollar modelos de machine learning más robustos

---

## 🎯 Preguntas de Investigación

El análisis busca responder tres preguntas críticas:

### 1️⃣ **¿Qué perfil demográfico es más propenso a incumplir?**
- Análisis de edad, educación y características demográficas
- Segmentación por grupos de riesgo
- Visualización de patrones de incumplimiento

**Hallazgo:** Los clientes **jóvenes (20-30 años)** presentan mayor propensión al incumplimiento.

---

### 2️⃣ **¿Existen valores atípicos (outliers) que requieran tratamiento?**
- Detección de anomalías en variables numéricas
- Evaluación de su impacto en modelos posteriores
- Decisiones sobre tratamiento/eliminación

**Hallazgo:** Se detectaron **outliers en Income y Age** que requieren atención antes de entrenar modelos de ML.

---

### 3️⃣ **¿Cuáles variables son más importantes para predecir riesgo?**
- Análisis de correlación
- Comparación de distribuciones entre grupos
- Ranking de importancia de características

**Hallazgo:** La **edad** emerge como variable más predictiva del riesgo crediticio.

---

## 🧰 Tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Hallazgos Principales

### 🔴 Perfiles de Alto Riesgo Identificados

1. **Edad Joven (20-30 años)**
   - Incumplimiento: 35% (vs 25% promedio)
   - Posibles razones: Falta de experiencia, inestabilidad laboral
   - Recomendación: Requisitos más estrictos, garantías adicionales

2. **Ingresos Bajos (<$30k)**
   - Incumplimiento: 30% (vs 25% promedio)
   - Posibles razones: Capacidad de pago limitada
   - Recomendación: Montos más bajos, plazos más cortos

3. **Ratio Deuda/Ingreso Alto (>20%)**
   - Incumplimiento: 35% (vs 25% promedio)
   - Posibles razones: Sobreendeudamiento
   - Recomendación: Rechazar si ratio excede umbral

---

### 🟢 Perfiles de Bajo Riesgo Identificados

1. **Edad Mayor (50+ años)**
   - Incumplimiento: 20% (vs 25% promedio)
   - Posibles razones: Estabilidad laboral, historial comprobado
   - Recomendación: Términos favorables

2. **Ingresos Altos (>$70k)**
   - Incumplimiento: 20% (vs 25% promedio)
   - Posibles razones: Capacidad de pago verificada
   - Recomendación: Mayor flexibilidad en montos

3. **Antigüedad en vivienda (>10 años)**
   - Incumplimiento: 18% (vs 25% promedio)
   - Posibles razones: Estabilidad domiciliaria
   - Recomendación: Factor positivo en evaluación

---

## 📄 Proposito

Proyecto educativo y académico.
