# **Mejora de imágenes con GFPGAN para análisis forense**

Este proyecto utiliza el modelo **GFPGAN** (Generative Facial Prior Generative Adversarial Network) para mejorar la calidad de imágenes, especialmente rostros, y escalarlas al doble de su tamaño original. Está diseñado para ser utilizado en el ámbito del **cómputo forense**, donde la claridad y calidad de las imágenes son cruciales para el análisis e identificación.

![image](https://miro.medium.com/v2/resize:fit:1400/1*EvemeaXd0_SEHPmxGeDLsw.png)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jrleonett/SwinIR/blob/main/SwinIR.ipynb)

---
## **Capturas de Pantalla**
![Imagen Original vs. Mejorada](https://lh3.googleusercontent.com/d/1Wi1lOUsS513PfDp3ubNJuD8iVxx0G1b0)
*Comparación de una imagen original y su versión mejorada.*

## **Descripción.**

El programa está dividido en tres fases principales:

1. **Carga de imágenes**: Se crea una carpeta llamada `EVIDENCIAS` donde se almacenan las imágenes a procesar.
2. **Mejora de imágenes**: Se aplica el modelo GFPGAN para mejorar la calidad de las imágenes, eliminar ruido y escalarlas al doble de su tamaño.
3. **Empaquetado y descarga**: Las imágenes mejoradas se guardan en la carpeta `EVIDENCIAS` con la nomenclatura `nombrearchivo_mejoradoIA.jpg`, y se descargan en un archivo ZIP.

---

## **Instalación del Repositorio**

Sigue estos pasos para instalar y ejecutar el proyecto:

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tuusuario/turepositorio.git
   cd turepositorio
   ```
   
2. **Instala las dependencias:**
```bash
pip install torch==1.13.1 torchvision==0.14.1 --extra-index-url https://download.pytorch.org/whl/cu117
pip install gfpgan realesrgan basicsr
```
3. **Ejecuta el programa:**
- Sube las imágenes a la carpeta EVIDENCIAS.
- Ejecuta las tres fases del programa en Google Colab o en tu entorno local.
---
## **Uso.**
**1. Subir imágenes:**
- Coloca las imágenes que deseas mejorar en la carpeta EVIDENCIAS.

**2. Mejorar imágenes:**
- Ejecuta la Fase 2 para procesar las imágenes y guardar los resultados.

**3. Descargar resultados:**
- Ejecuta la Fase 3 para descargar las imágenes mejoradas en un archivo ZIP.

---

## **Observaciones.**
- **Formatos admitidos:** El programa funciona con imágenes en formato JPG o PNG.
- **Requisitos de hardware:** GFPGAN requiere una GPU para funcionar eficientemente. Asegúrate de que tu entorno esté utilizando una GPU.
- **Tiempo de procesamiento:** Dependiendo del tamaño de la imagen y la complejidad del modelo, el procesamiento puede tardar unos segundos.

--- 

## **Beneficios en el Cómputo Forense.**
Este proyecto es especialmente útil en el ámbito del cómputo forense por las siguientes razones:

- **Mejora de imágenes de baja calidad:** Permite mejorar imágenes borrosas, pixeladas o con ruido, lo que facilita la identificación de rostros y otros detalles.
- **Escalado de imágenes:** Al escalar las imágenes al doble de su tamaño, se pueden visualizar detalles que no eran perceptibles en la imagen original.
- **Automatización del proceso:** El programa automatiza la mejora y el almacenamiento de imágenes, ahorrando tiempo en el análisis forense.
- **Compatibilidad con formatos comunes:** Soporta los formatos de imagen más utilizados en investigaciones forenses (JPG y PNG).

---

## **Facilidad de uso:**
Está diseñado para ser utilizado por profesionales forenses sin necesidad de conocimientos avanzados en programación.

## **Ejemplo de Uso.
Sube una imagen llamada foto.jpg a la carpeta EVIDENCIAS.

**Ejecuta el programa.***
Verás:
- La imagen original.
- La imagen mejorada con GFPGAN (escalada al doble y restaurada).
- La imagen mejorada se guardará como foto_mejoradoIA.jpg en la carpeta EVIDENCIAS.
- Se descargará un archivo ZIP con todas las imágenes mejoradas.

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

