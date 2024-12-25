# **Mejoras de imágenes digitales usando OpenCV.**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jrleonett/SwinIR/blob/main/SwinIR.ipynb)

Este proyecto está diseñado para mejorar la calidad de imágenes y empaquetar los resultados en un archivo ZIP descargable. Está dividido en tres fases principales:

1. **Carga de imágenes**: Se crea una carpeta llamada `EVIDENCIAS` y se cargan las imágenes a procesar.
2. **Mejora de imágenes**: Se aplica un algoritmo de mejora a las imágenes, se muestran los resultados en pantalla y se guardan en una carpeta llamada `RESULTADOS`.
3. **Empaquetado y descarga**: Las imágenes originales y mejoradas se comprimen en un archivo ZIP y se descargan automáticamente.

---

## **Tecnologías Utilizadas**
- **Python**: Lenguaje de programación principal.
- **OpenCV**: Biblioteca para procesamiento de imágenes.
- **Google Colab**: Entorno de ejecución en la nube.
- **Matplotlib**: Visualización de imágenes en pantalla.

---

## **Instrucciones de Uso**
1. **Subir imágenes**: Ejecuta la **Parte 1** para crear la carpeta `EVIDENCIAS` y subir las imágenes a procesar.
2. **Mejorar imágenes**: Ejecuta la **Parte 2** para mejorar las imágenes, mostrar los resultados y guardarlos en la carpeta `RESULTADOS`.
3. **Descargar resultados**: Ejecuta la **Parte 3** para empaquetar las imágenes originales y mejoradas en un archivo ZIP y descargarlo.

---

## **Observaciones**
- **Formatos de imagen admitidos**: El proyecto funciona con imágenes en formato JPG o PNG.
- **Carpetas generadas**: Se crean dos carpetas automáticamente:
  - `EVIDENCIAS`: Almacena las imágenes originales subidas por el usuario.
  - `RESULTADOS`: Contiene las imágenes mejoradas.
- **Algoritmo de mejora**: Se utiliza la función `detailEnhance` de OpenCV para mejorar la calidad de las imágenes. Puedes ajustar los parámetros `sigma_s` y `sigma_r` para personalizar el resultado.

---

## **Recomendaciones**
1. **Calidad de las imágenes**: Para obtener mejores resultados, utiliza imágenes con una resolución adecuada.
2. **Personalización del algoritmo**: Si deseas aplicar otros filtros o técnicas de mejora, modifica la función `mejorar_imagen` en la **Parte 2**.
3. **Organización de archivos**: Si trabajas con muchas imágenes, asegúrate de nombrarlas de manera descriptiva para facilitar su identificación.
4. **Uso en Google Colab**: Este proyecto está diseñado para ejecutarse en Google Colab. Si lo usas en otro entorno, asegúrate de instalar las dependencias necesarias (`opencv-python`, `matplotlib`).

---

## **Ejemplo de Uso**
1. Sube una imagen llamada `foto.jpg` a la carpeta `EVIDENCIAS`.
2. Ejecuta la **Parte 2** para mejorar la imagen y ver los resultados en pantalla.
3. Ejecuta la **Parte 3** para descargar un archivo ZIP que contiene:
   - `foto.jpg` (imagen original).
   - `foto_Mejorada.JPG` (imagen mejorada).

---

## **Contribuciones**
Si deseas contribuir a este proyecto, ¡eres bienvenido! Puedes:
- Mejorar el algoritmo de procesamiento de imágenes.
- Agregar soporte para más formatos de imagen.
- Optimizar el código para manejar grandes volúmenes de imágenes.

---
# Cómo citar este trabajo.
Usa la siguiente entrada BibTeX si utilizas este trabajo en tu investigación:
```bash
@article{joséRLeonett,
  title={Análisis Error de ELA y Matadatos en imágenes digitales},
  author={José R. Leonett},
  year={2024}
}
```
---

**Licencia.**
- Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

---

## **Capturas de Pantalla**
![Imagen Original vs. Mejorada](https://via.placeholder.com/600x300)  
*Comparación de una imagen original y su versión mejorada.*
