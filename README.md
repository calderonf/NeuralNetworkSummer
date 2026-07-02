# AI Workshop: Redes Neuronales 🧠

Material del taller **AI Workshop: Neural Networks** — *AgeTech Latam Summer School 2026*
Eng. Elec. Francisco Calderón · Departamento de Electrónica · Pontificia Universidad Javeriana

Taller práctico de **90 minutos** para un público mixto (salud, ingeniería biomédica, diseño) **sin experiencia previa en programación**. El objetivo es que al salir cualquier asistente sepa **qué es una red neuronal, para qué sirve y cómo correrla y modificarla en Python** para problemas de clasificación y regresión.

---

## 📂 Contenido

| Archivo | Descripción |
|---|---|
| `ANN_Summer_2026.pptx` | Presentación de la charla (17 diapositivas). |
| `notebooks/01_Clasificacion_del_Playground_al_Codigo.ipynb` | Del TensorFlow Playground al código: clasificación (círculos → cáncer de mama). |
| `notebooks/02_Regresion_Prediccion_Numerica_en_Salud.ipynb` | Regresión: predecir la progresión de la diabetes. |

## 🚀 Cómo abrir los notebooks en Google Colab

Cada notebook tiene un botón **"Open in Colab"** en su primera celda. También puedes abrirlos directamente:

- **Notebook 1 — Clasificación:**
  https://colab.research.google.com/github/calderonf/NeuralNetworkSummer/blob/main/notebooks/01_Clasificacion_del_Playground_al_Codigo.ipynb
- **Notebook 2 — Regresión:**
  https://colab.research.google.com/github/calderonf/NeuralNetworkSummer/blob/main/notebooks/02_Regresion_Prediccion_Numerica_en_Salud.ipynb

> No hay que instalar nada: Colab ya trae Python, scikit-learn y TensorFlow. Solo ejecuta las celdas con **▶️** o `Shift + Enter`.

## 🎛️ Herramienta interactiva

Antes del código, el taller usa el **TensorFlow Playground** para construir una red *sin escribir código*:
👉 https://playground.tensorflow.org/

## 🗺️ Ruta de los 90 minutos

1. **La intuición** — qué es una red neuronal (~15 min)
2. **Playground** — construir una red sin código (~20 min)
3. **Al código** — Notebook 1, clasificación (~25 min)
4. **Regresión** — Notebook 2, caso de salud (~20 min)
5. **Tu turno** — cómo aplicarlo + límites y ética (~10 min)

## 🧰 Requisitos (solo si corres local, no en Colab)

```bash
pip install scikit-learn matplotlib numpy pandas tensorflow
```

## 🩺 Datasets usados

- `make_circles` (sintético) — puente visual con el Playground.
- *Breast Cancer Wisconsin* (`load_breast_cancer`) — clasificación benigno/maligno.
- *Diabetes* (`load_diabetes`) — regresión de la progresión de la enfermedad.

Todos vienen incluidos en scikit-learn; no requieren descargas externas.

---
*Reutiliza y adapta este material libremente para tus propias clases.*
