# Práctica 1 de Visión por Computador

Este repositorio contiene ejercicios prácticos realizados en el marco de la primera práctica de la asignatura VC (Visión por Computador). Se han implementado diversas tareas utilizando la biblioteca OpenCV y otras herramientas de procesamiento de imágenes en Python. A continuación se describen  los apartados marcados como TAREA.

## TAREA 1: Generar una Imagen con la Textura de un Tablero de Ajedrez

Descripción:  
Se creó una imagen de tamaño 800x800 píxeles con la textura de un tablero de ajedrez, alternando cuadros blancos y negros. La solución utiliza bucles y estructuras condicionales para rellenar los bloques en función de su posición.

Objetivos de aprendizaje:
- Manipulación de arrays en NumPy.
- Generación de imágenes con múltiples planos de color (RGB).
- Uso de estructuras de control para patrones repetitivos.

## TAREA 2: Imagen Estilo Mondrian

Descripción:  
Se construyó una imagen inspirada en el estilo del artista Piet Mondrian, utilizando formas rectangulares rellenas de colores primarios (rojo, azul, amarillo) y blanco, pero diferenciándolo incluyendo una cruz y dos "ojos" con colores diferentes del fondo. Se utilizaron las funciones de dibujo de OpenCV (`cv2.rectangle`, `cv2.line`, `cv2.circle`, etc.).

Objetivos de aprendizaje:
- Dibujo de formas básicas con OpenCV.
- Composición de obras visuales mediante coordenadas y colores.
- Aplicación creativa del arte digital como herramienta de práctica de visión por computador.

## TAREA 3: Pintar Círculos en los Píxeles Más Claros y Oscuros

Descripción:  
Se implementó una funcionalidad para detectar los píxeles con valores de intensidad máximos y mínimos (más claros y más oscuros) en una imagen, y se dibujaron círculos en dichas posiciones.

Objetivos de aprendizaje:
- Conversión a escala de grises con OpenCV.
- Análisis de intensidad de imagen.
- Detección de extremos (mínimos y máximos) con `cv2.minMaxLoc`.

## TAREA 4: Propuesta Propia de Pop Art (Inspiración: Andy Warhol)

Descripción:  
Se desarrolló una propuesta personalizada de estilo Pop Art, basada en el estilo visual de Andy Warhol. A partir de una imagen capturada con la webcam, se generó una composición 3x3 con variaciones cromáticas entre las versiones.  
- La primera línea contiene 3 imágenes con las salidas RGB correspondientes.  
- La segunda línea presenta las versiones restando los valores RGB a 255.  
- La tercera línea muestra las versiones sumando los valores RGB a 0.  

Objetivos de aprendizaje:
- Manipulación avanzada de canales de color.
- Creación de collages visuales en tiempo real.
- Fusión entre arte y computación visual.

---

## Webgrafía

- [Documentación oficial de OpenCV (Python)](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)  
- [Referencia de funciones de dibujo en OpenCV](https://docs.opencv.org/4.x/dc/da5/tutorial_py_drawing_functions.html)  
- Consultas y apoyo teórico-práctico realizadas con **ChatGPT (OpenAI)**.  
