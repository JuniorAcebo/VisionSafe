# 🧠 Sistema Inteligente de Detección de Violencia en Tiempo Real

Este proyecto consiste en el desarrollo de un **sistema basado en Inteligencia Artificial** capaz de **detectar situaciones de violencia en tiempo real** a través de video, utilizando técnicas de **visión por computadora y aprendizaje profundo (Deep Learning)**.

El sistema combina dos componentes principales:

- 🔍 **Detección de personas** mediante técnicas de visión por computadora.
- ⚠️ **Clasificación de violencia** mediante un modelo entrenado con redes neuronales convolucionales (CNN).

---

## 🎯 Objetivo

Desarrollar una solución que permita:

- Detectar automáticamente la presencia de personas en un entorno.
- Analizar el comportamiento en video.
- Determinar si existe una situación de **violencia o no violencia**.
- Mostrar los resultados en tiempo real desde una cámara o video.

---

## ⚙️ ¿Cómo funciona?

El sistema sigue el siguiente flujo:

1. 📷 Captura de video (cámara o archivo).
2. 🧠 Procesamiento del frame con un modelo de clasificación de violencia.
3. 📊 Análisis de resultados:
   - Si se detectan personas.
   - Si hay violencia en la escena.
4. 🖥️ Visualización en pantalla:
   - Bounding boxes sobre las personas.
   - Indicador de "Violencia" o "No Violencia".

---

## 🧩 Tecnologías utilizadas

- 🐍 Python  
- 🎥 OpenCV  
- 🤖 TensorFlow / Keras  
- 📊 NumPy  
- 📓 Jupyter Notebook  

---

## 🧠 Modelo de IA

El modelo de detección de violencia fue entrenado con un dataset de videos clasificados en dos categorías:

- **Violence**
- **NonViolence**

### Características del entrenamiento:

- División de datos: **80% entrenamiento / 20% prueba**
- Extracción de frames desde videos
- Red neuronal basada en **CNN / MobileNetV2**
- Clasificación binaria (violencia / no violencia)

---

## 🚀 Funcionalidades principales

- ✅ Detección de violencia en tiempo real  
- ✅ Análisis desde webcam o videos  
- ✅ Detección de personas con bounding boxes  
- ✅ Sistema optimizado con buffer para mayor precisión  
- ✅ Visualización clara y en vivo  

---

## 💡 Aplicaciones

Este sistema puede ser utilizado en:

- 🏫 Seguridad en instituciones educativas  
- 🏢 Vigilancia en empresas  
- 🏙️ Sistemas de monitoreo urbano  
- 🛡️ Prevención de incidentes en espacios públicos  

---

## 🔮 Mejoras futuras

- Implementación de alertas automáticas  
- Integración con sistemas de seguridad (CCTV)  
- Uso de modelos más avanzados (Transformers, 3D CNN)  
- Detección de múltiples tipos de eventos (robos, caídas, etc.)  
