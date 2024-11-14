Skin Cancer Classification Model
Este proyecto tiene como objetivo la clasificación de imágenes de cáncer de piel utilizando un modelo de aprendizaje automático basado en Redes Neuronales Convolucionales (CNN). Utiliza transfer learning con el modelo preentrenado EfficientNetB0 para mejorar el rendimiento en la clasificación de imágenes de diferentes tipos de cáncer de piel.

Tecnologías Utilizadas
Python: Lenguaje de programación principal.
TensorFlow: Framework de deep learning para entrenar y desplegar el modelo.
Keras: API de alto nivel para construir y entrenar modelos de deep learning.
Flask: Framework web para crear la interfaz de usuario (UI).
OpenCV: Biblioteca para procesamiento de imágenes (opcional dependiendo de tus necesidades).
Scikit-learn: Usado para calcular pesos de clase para balancear las clases durante el entrenamiento.
NumPy: Para la manipulación de matrices y arrays.
Descripción
Este proyecto utiliza un modelo de Redes Neuronales Convolucionales (CNN) para predecir la probabilidad de diferentes tipos de cáncer de piel a partir de imágenes. El modelo se entrena utilizando imágenes de un conjunto de datos con 9 clases de cáncer de piel:

Actinic Keratosis
Basal Cell Carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented Benign Keratosis
Seborrheic Keratosis
Squamous Cell Carcinoma
Vascular Lesion
Se utiliza Transfer Learning con el modelo EfficientNetB0 preentrenado en ImageNet para mejorar la capacidad del modelo de generalizar patrones visuales.
