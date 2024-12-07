# Diabetic retinopathy clasification in fundus images using convolutional neuronal networks

![banner_RD](https://github.com/user-attachments/assets/440c0c9a-7396-41cc-ad59-c68040d84255)

**Autor:** Oscar Mauricio Campos Sepulveda

**Objetivo:** Construir un modelo basado en redes neuronales convolucionales para la clasificación de cada una de las fases de la retinopatía diabética presentes en imágenes del fondo del ojo.

**Dataset:** https://www.kaggle.com/competitions/aptos2019-blindness-detection/data 

- *Descripción:* Se dispone de un extenso conjunto de datos compuesto por imágenes de retina de alta resolución, tomadas bajo diversas condiciones de imagen. Cada sujeto tiene asignados campos para el ojo izquierdo y derecho, identificados con el número de paciente seguido de “izquierda” o "derecha"(por ejemplo, 1_izquierda.jpeg es el ojo izquierdo del paciente con identificación 1). Cada imagen fue evaluada por un clínico para determinar la presencia de retinopatía diabética, utilizando una escala de 0 a 4 que indica la gravedad de la condición. Esta escala incluye los siguientes niveles: 0 (sin retinopatía diabética), 1 (leve), 2 (moderada), 3 (severa) y 4 (retinopatía diabética proliferativa).

- *Instrucciones:* Debido al tamaño extremadamente grande de este conjunto de datos, los archivos vienen separados en varias partes. Se recomienda utilizar 7zip o keka para extraerlos.  
  - train.zip - el conjunto de entrenamiento (5 archivos en total)
  - test.zip - el conjunto de pruebas (7 archivos en total)
  - trainLabels.csv - contiene las etiquetas del conjunto de entrenamiento

**Modelos:** Convolutional Neuronal Networks (CNN), Transfer Learning, EfficientNetB7, Preprocessing, Data Augmentation, Multiclass classification, Keras, Tensorflow.

**Enlaces de interés:**
- Código: https://www.kaggle.com/code/oscarmauriciocampos/entrega-final
- Video: 
- Repositorio:  https://github.com/oskarwest/diabetic_retinopathy
- Diapositivas: https://docs.google.com/presentation/d/e/2PACX-1vQGzs8Oa0NDjGd9PcrRvQUNsRbzmqZfUriWh2RKQkjGK01yYPHdHTUwmEvVVZrsHg/pub?start=false&loop=false&delayms=3000
