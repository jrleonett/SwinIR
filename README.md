# SwinIR
Restauración de imágenes usando SwinIR: Swin Transformer.

La restauración de imágenes es un problema de visión de bajo nivel de larga data que tiene como objetivo restaurar imágenes de alta calidad a partir de imágenes de baja calidad (por ejemplo, imágenes reducidas, ruidosas y comprimidas). Si bien los métodos de restauración de imágenes de última generación se basan en redes neuronales convolucionales, se han realizado pocos intentos con transformadores que muestren un rendimiento impresionante en tareas de visión de alto nivel. En este documento, proponemos un sólido modelo de referencia SwinIR para la restauración de imágenes basado en Swin Transformer. SwinIR consta de tres partes: extracción de características superficiales, extracción de características profundas y reconstrucción de imágenes de alta calidad. En particular, el módulo de extracción de características profundas se compone de varios bloques de transformadores Swin residuales (RSTB), cada uno de los cuales tiene varias capas de transformadores Swin junto con una conexión residual. Realizamos experimentos en tres tareas representativas: superresolución de imagen (incluida la superresolución de imagen clásica, liviana y del mundo real), eliminación de ruido de imagen (incluida la eliminación de ruido de imagen en escala de grises y en color) y reducción de artefactos de compresión JPEG. Los resultados experimentales demuestran que SwinIR supera a los métodos más avanzados en diferentes tareas hasta en 0,14~0,45 dB, mientras que el número total de parámetros se puede reducir hasta en un 67%.

![image](https://user-images.githubusercontent.com/41134438/198924164-0e06700e-9cda-4287-a50c-ee986784bc62.png)

# Licencia y Reconocimiento
Este proyecto se publica bajo la licencia Apache 2.0. Los códigos se basan en gran medida en Swin Transformer . También nos referimos a códigos en KAIR y BasicSR . Por favor, también siga sus licencias. Gracias por sus impresionantes trabajos.



