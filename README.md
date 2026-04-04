# 🛰️ Procesamiento de Imágenes SAR - Teledetección

Este repositorio contiene el desarrollo de una práctica de visión por computador aplicada a imágenes SAR (Sentinel-1), enfocada en el análisis de superficies terrestres.

## 📌 Contenido

Se trabajaron cuatro etapas principales:

1. **Preprocesamiento**
   - Reescalado de imágenes
   - Reducción de ruido speckle mediante filtrado

2. **Clasificación no supervisada**
   - Aplicación de K-Means para segmentar la imagen en clases

3. **Segmentación agua / no agua**
   - Generación de máscara binaria
   - Cálculo del porcentaje de agua

4. **Creación de dataset**
   - Registro de imágenes
   - Generación de ground truth por promedio
   - División en parches (Noisy / GT)

## 🧠 Tecnologías utilizadas

- Python
- OpenCV
- NumPy
- Matplotlib

## 📊 Objetivo

Aplicar técnicas de procesamiento de imágenes y aprendizaje automático para analizar datos SAR y construir un dataset para futuras aplicaciones de inteligencia artificial.

## 📁 Resultados

- Imágenes filtradas
- Clasificaciones por clustering
- Máscaras de agua
- Dataset estructurado (Noisy / Ground Truth)

---
