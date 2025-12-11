# 📘 Proyecto Final – Introducción a Deep Learning
### Autor: [Tu nombre]
### Curso: DS405 – Introducción a Deep Learning

---

## 📌 Descripción General

Este proyecto reúne tres modelos diferentes de Deep Learning aplicados a distintos tipos de datos:  
1. **MLP** para datos tabulares  
2. **CNN** para imágenes  
3. **LSTM** para datos secuenciales  

Cada modelo fue desarrollado y entrenado en un notebook independiente, incluyendo métricas, visualizaciones y análisis de predicciones.

---

## 🧠 Modelos Implementados

### **1. MLP – Clasificación de tumores (Breast Cancer Dataset)**  
- **Tipo de datos:** Tabular  
- **Dataset:** Breast Cancer Wisconsin (scikit-learn)  
- **Tarea:** Clasificar tumores como benignos o malignos.  
- **Arquitectura:** Capas densas con ReLU, Dropout y salida sigmoidal.  

**Resultados principales:**  
- **Accuracy en test: 94.19%**  

---

### **2. CNN – Clasificación de imágenes (Fashion-MNIST)**  
- **Tipo de datos:** Imágenes 28×28  
- **Dataset:** Fashion-MNIST (Keras)  
- **Tarea:** Clasificar prendas de ropa en 10 categorías.  
- **Arquitectura:** Dos capas convolucionales con MaxPooling y una capa densa final softmax.  

**Resultados principales:**  
- **Accuracy en test: 89.45%**  

---

### **3. RNN/LSTM – Análisis de sentimientos (IMDB Reviews)**  
- **Tipo de datos:** Texto secuencial  
- **Dataset:** IMDB Reviews (Keras)  
- **Tarea:** Clasificar reseñas como positivas o negativas.  
- **Arquitectura:** Embedding, LSTM de 64 unidades y salida sigmoidal.  

**Resultados principales:**  
- **Accuracy en test: 85.85%**  

---

## 📊 Visualizaciones Incluidas

Los notebooks incluyen:

- Curvas de entrenamiento (loss y accuracy)  
- Matriz de confusión  
- Reporte de clasificación  
- Ejemplos de predicciones correctas e incorrectas  
- Muestras visuales de los datos (cuando aplica)

---

## 📁 Estructura del Repositorio

```
deep-learning-project/
│── 01_MLP.ipynb
│── 02_CNN.ipynb
│── 03_RNN.ipynb
│── README.md
```

---

## ▶️ Cómo Ejecutar

1. Abrir los notebooks en Google Colab.  
2. Ejecutar las celdas en orden.  
3. No se necesita descargar datasets manualmente:  
   - Breast Cancer → scikit-learn  
   - Fashion-MNIST → Keras  
   - IMDB Reviews → Keras  

---

## 📝 Conclusiones Generales

- Cada arquitectura funciona mejor con un tipo distinto de datos.  
- Los modelos alcanzaron resultados adecuados aun siendo arquitecturas simples.  
- El proyecto permite comparar cómo cambian el preprocesamiento, la estructura del input y el rendimiento según la red utilizada.

---

## 🔧 Mejoras Futuras

- Ajuste de hiperparámetros  
- Modelos más profundos o con regularización adicional  
- Data augmentation para CNN  
- Uso de embeddings preentrenados en LSTM  
