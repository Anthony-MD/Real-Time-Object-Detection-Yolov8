# Object-Detection-Yolov8
Este proyecto implementa un sistema de detección de objetos utilizando la arquitectura YOLOv8 (You Only Look Once). El modelo ha sido entrenado y validado para identificar y localizar múltiples clases de objetos con alta precisión y velocidad de inferencia, ideal para aplicaciones en tiempo real.

# Object Detection using YOLOv8

## Descripción
Este proyecto implementa un sistema de detección de objetos utilizando la arquitectura **YOLOv8 (You Only Look Once)**. El modelo ha sido entrenado y validado para identificar y localizar múltiples clases de objetos con alta precisión y velocidad de inferencia, ideal para aplicaciones en tiempo real.

## Stack Tecnológico
* **Modelo:** Ultralytics YOLOv8.
* **Framework:** PyTorch.
* **Herramientas:** OpenCV (para procesamiento de video/imagen), YAML (configuración de dataset), Google Colab (GPU T4).

## Capacidades Técnicas
* **Detección de Objetos:** Localización precisa mediante Bounding Boxes.
* **Entrenamiento Personalizado:** Configuración del pipeline de entrenamiento, incluyendo la gestión de archivos `.yaml` para la definición de clases y rutas de datos.
* **Métricas de Rendimiento:** Evaluación basada en **mAP (mean Average Precision)**, asegurando un equilibrio óptimo entre precisión y velocidad de procesamiento (FPS).

## Visualización de Resultados
El modelo es capaz de procesar imágenes y video, generando etiquetas y scores de confianza.

<img width="1207" height="624" alt="image" src="https://github.com/user-attachments/assets/d69d3431-a856-4992-9d7d-eb844eb485c3" />

<img width="1045" height="728" alt="image" src="https://github.com/user-attachments/assets/51781bd3-64d1-4128-a8b5-3539193fcb87" />

<img width="639" height="613" alt="image" src="https://github.com/user-attachments/assets/95512b4e-4a5e-409c-a232-0c9605716836" />

<img width="644" height="629" alt="image" src="https://github.com/user-attachments/assets/0eb24f4e-dd9c-4fd8-baa4-82f55cf3e48d" />



##  Cómo empezar
1. Instalar dependencias: `pip install ultralytics`
2. Clonar el repositorio.
3. Ejecutar el notebook `Practica_Unidad2_CV.ipynb` para ver el pipeline completo desde la carga de datos hasta la inferencia.
