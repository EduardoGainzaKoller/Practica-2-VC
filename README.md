# README

Este repositorio contiene un cuaderno de Jupyter con prácticas de **Procesamiento Digital de Imágenes** utilizando **OpenCV** y **Python**.  
A continuación, se describen las tareas implementadas:

## 📌 Tarea 1: Detección de bordes con Canny
- Se carga la imagen `mandril.jpg`.
- Se convierte a escala de grises.
- Se aplica el detector de bordes **Canny**.
- Se cuenta el número de píxeles blancos por fila.
- Se destacan las filas cuyo número de bordes supera el 90% del máximo detectado.
- Se grafican los resultados.

## 📌 Tarea 2: Filtros Sobel y Umbralización
- Se suaviza la imagen con un filtro **Gaussiano**.
- Se aplican los filtros **Sobel** en los ejes X e Y.
- Se convierte el resultado a 8 bits (`convertScaleAbs`).
- Se realiza una **umbralización** para resaltar bordes fuertes.
- Se cuentan píxeles blancos por filas y columnas.
- Se identifican filas/columnas con ≥90% del máximo.
- Se dibujan líneas en la imagen original (`mandril.jpg`) indicando las regiones detectadas.

## 📌 Tarea 3: Demostrador en vivo con cámara
- Se captura video en tiempo real.
- Se implementan distintos modos de visualización:
  1. **Original**  
  2. **Sustracción de fondo**  
  3. **Escala de grises**  
  4. **Canny (bordes)**  
- Se permite alternar entre modos con la tecla `m`.
- Se cierra con la tecla `ESC`.

## 📌 Tarea 4: Pelota interactiva con detección de bordes
- Se genera una pelota que se mueve con velocidad inicial.
- Rebota contra los bordes de la ventana.
- Utiliza **Canny** para detectar bordes dentro del entorno.
- Si la pelota toca un borde detectado, cambia aleatoriamente su trayectoria.
- Se muestran dos ventanas:  
  - La cámara con la pelota en movimiento.  
  - Los bordes detectados por Canny.  

---
