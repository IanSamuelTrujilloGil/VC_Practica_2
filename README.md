# VC_Practica_2

## Trabajo realizado.

En esta práctica se han trabajado los siguientes aspectos:


## Lista de tareas realizadas

### TAREA 1: Realiza la cuenta de píxeles blancos por filas (en lugar de por columnas). Determina el valor máximo de píxeles blancos para filas, maxfil, mostrando el número de filas y sus respectivas posiciones, con un número de píxeles blancos mayor o igual que 0.90*maxfil.

Descripción del trabajo:
1. Se leyó la imagen mandril.jpg y se convirtió a escala de grises.
2. Se aplicó el detector de bordes Canny para obtener una imagen binaria.
3. Se realizó la cuenta de píxeles blancos (valor 255) por cada fila.
4. Se determinó el valor máximo maxfil y las filas que superan el 90% de dicho máximo.

Resultados obtenidos:
Filas con más del 90% de píxeles blancos: [6, 12, 15, 20, 21, 88, 100]
Número total de filas que cumplen la condición: 7


### TAREA 2: Aplica umbralizado a la imagen resultante de Sobel (convertida a 8 bits), y posteriormente realiza el conteo por filas y columnas similar al realizado en el ejemplo con la salida de Canny de píxeles no nulos. Calcula el valor máximo de la cuenta por filas y columnas, y determina las filas y columnas por encima del 0.90*máximo. Remarca con alguna primitiva gráfica dichas filas y columnas sobre la imagen del mandril. ¿Cómo se comparan los resultados obtenidos a partir de Sobel y Canny?

### TAREA 3: Proponer un demostrador que capture las imágenes de la cámara, y les permita exhibir lo aprendido en estas dos prácticas ante quienes no cursen la asignatura :). Es por ello que además de poder mostrar la imagen original de la webcam, permita cambiar de modo, incluyendo al menos dos procesamientos diferentes como resultado de aplicar las funciones de OpenCV trabajadas hasta ahora.

Se utiliza la librería de Python Tkinter para crear una ventana interactiva que muestra la imagen capturada por la cámara del dispositivo y mediante una barra vertical, permite seleccionar uno de los siguientes modos:
- Normal mode
- Black and white
- Darkest and brightest pixel
- Thresholding
- Border detector
- Frame substraction

Según el modo seleccionado, la imagen que se muestra en la interfaz experimenta diferentes variaciones.


### TAREA 4: Tras ver los vídeos [My little piece of privacy](https://www.niklasroy.com/project/88/my-little-piece-of-privacy), [Messa di voce](https://youtu.be/GfoqiyB1ndE?feature=shared) y [Virtual air guitar](https://youtu.be/FIAmyoEpV5c?feature=shared) proponer un demostrador reinterpretando la parte de procesamiento de la imagen, tomando como punto de partida alguna de dichas instalaciones.

## Requisitos de ejecución

Para poder ejecutar el cuaderno de la entrega se requiere utilizar mínimo la versión de python 3.11.5, y tener instaladas las librerías: 

- opencv-python
- matplotlib
- numpy
- mediapipe
- pillow
- tkinter (Viene por defecto en la instalación de Python)

## Autoría 

- Tycho Quintana Santana. 
- Ian Samuel Trujillo Gil.

## Referencias a fuentes

- https://numpy.org/doc/2.1/reference/generated/numpy.ndarray.size.html
- https://docs.opencv.org/4.x/d2/de8/group__core__array.html#ga4b78072a303f29d9031d56e5638da78e
- https://numpy.org/doc/stable/reference/generated/numpy.where.html
- https://numpy.org/doc/stable/reference/generated/numpy.ndarray.max.html
- https://www.tutorialspoint.com/how-to-place-an-image-into-a-frame-in-tkinter
- https://www.geeksforgeeks.org/python/how-to-change-the-title-bar-in-tkinter/
- https://recursospython.com/guias-y-manuales/panel-de-pestanas-notebook-tkinter/
- https://docs.opencv.org/4.x/d2/de8/group__core__array.html#ga8873b86a29c5af51cafdcee82f8150a7
- https://www.youtube.com/watch?v=v-ebX04SNYM
- https://medium.com/@TENOCLOGY/hand-landmark-detection-and-tracking-with-mediapipe-e5268cd1c897
