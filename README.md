# Proyecto Final - Visión por Ordenador I

Este repositorio contiene el código y materiales del **Proyecto Final de Visión por Ordenador I** (Ingeniería Matemática, Universidad Pontificia Comillas ICAI).

## 📌 Descripción

El proyecto implementa un sistema de visión por ordenador compuesto por dos bloques principales:

1. **Sistema de Seguridad**  
   - Detección de patrones geométricos mediante la cámara.  
   - Validación de una secuencia de figuras como contraseña visual.  

2. **Sistema Propuesto (Extracción de Información)**  
   - Juego interactivo tipo *"Draw a Perfect Circle"*, donde la cámara sigue el movimiento de un objeto o dedo y evalúa la circularidad del trazo.  

## 🖼️ Uso de las imágenes adjuntas

Para que el sistema funcione correctamente, es **imprescindible utilizar las imágenes adjuntadas en este repositorio**.  
Estas imágenes contienen las figuras geométricas (triángulo, cuadrado, pentágono, hexágono, etc.) que la cámara debe detectar durante la ejecución del programa.

- Coloca las imágenes impresas o en pantalla frente a la cámara.  
- Asegúrate de que estén bien iluminadas y dentro de la región de interés (ROI) definida en el código.  
- El sistema reconocerá únicamente las figuras verdes, descartando el resto.  

## ⚙️ Requisitos

- Python 3.9+  
- Librerías:  
  - `opencv-python`  
  - `numpy`  

Instalación rápida:

```bash
pip install opencv-python numpy
