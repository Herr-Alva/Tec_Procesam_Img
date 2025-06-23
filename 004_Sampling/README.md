# LAB_IMG_004_Alva_Sampling

Este cuaderno explora el proceso de **muestreo (sampling)** en el contexto del procesamiento digital de imágenes. Forma parte de la materia *Técnicas de Procesamiento de Imágenes* y busca mostrar cómo se reduce la resolución espacial de una imagen, evaluando sus efectos en la calidad visual y la reconstrucción.

## Autor

**Hernán Alva de Pedro**  
Materia: *Técnicas de Procesamiento de Imágenes*

## Descripción

El muestreo es una etapa fundamental en el procesamiento de imágenes digitales. En este notebook se abordan:

- Principios de muestreo espacial
- Reducción de resolución (downsampling)
- Interpolación para reconstrucción (upsampling)
- Comparación visual entre distintas resoluciones
- Evaluación de pérdidas de información

Las imágenes procesadas permiten observar cómo se degrada o conserva la información visual según la frecuencia de muestreo aplicada.

## Requisitos

Para ejecutar este notebook necesitas tener instaladas las siguientes librerías:

```bash
pip install opencv-python matplotlib numpy
