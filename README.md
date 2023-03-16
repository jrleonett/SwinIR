# SwinIR
Restauración de imágenes usando SwinIR: Swin Transformer.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jrleonett/SwinIR/blob/main/SwinIR.ipynb)
[![Open In Colab](https://camo.githubusercontent.com/20b418d7ddeb1333ede2072424b57335f561826132379bdd139a7e7a74c7eb1f/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d44656d6f266d6573736167653d48756767696e676661636525323047726164696f26636f6c6f723d6f72616e6765)](https://huggingface.co/spaces/vicalloy/GFPGAN)
[![Open In Colab](https://camo.githubusercontent.com/b102d8cbe56d7e016e4515439f8594f0564b26586ab9c4de236f81b93e96a9da/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d44656d6f266d6573736167653d5265706c696361746526636f6c6f723d626c7565)](https://replicate.com/tencentarc/gfpgan)



La restauración de imágenes es un problema de visión de bajo nivel de larga data que tiene como objetivo restaurar imágenes de alta calidad a partir de imágenes de baja calidad (por ejemplo, imágenes reducidas, ruidosas y comprimidas). Si bien los métodos de restauración de imágenes de última generación se basan en redes neuronales convolucionales, se han realizado pocos intentos con transformadores que muestren un rendimiento impresionante en tareas de visión de alto nivel. En este documento, proponemos un sólido modelo de referencia SwinIR para la restauración de imágenes basado en Swin Transformer. SwinIR consta de tres partes: extracción de características superficiales, extracción de características profundas y reconstrucción de imágenes de alta calidad. En particular, el módulo de extracción de características profundas se compone de varios bloques de transformadores Swin residuales (RSTB), cada uno de los cuales tiene varias capas de transformadores Swin junto con una conexión residual. Realizamos experimentos en tres tareas representativas: superresolución de imagen (incluida la superresolución de imagen clásica, liviana y del mundo real), eliminación de ruido de imagen (incluida la eliminación de ruido de imagen en escala de grises y en color) y reducción de artefactos de compresión JPEG. Los resultados experimentales demuestran que SwinIR supera a los métodos más avanzados en diferentes tareas hasta en 0,14~0,45 dB, mientras que el número total de parámetros se puede reducir hasta en un 67%.

![image](https://user-images.githubusercontent.com/41134438/198924164-0e06700e-9cda-4287-a50c-ee986784bc62.png)

# Licencia y Reconocimiento
Este proyecto se publica bajo la licencia Apache 2.0. Los códigos se basan en gran medida en Swin Transformer . También nos referimos a códigos en KAIR y BasicSR . Por favor, también siga sus licencias. Gracias por sus impresionantes trabajos.



