Objetivo:
El objetivo principal de este proyecto es desarrollar una aplicación de Android capaz de clasificar gestos en tiempo real utilizando redes neuronales implementadas con TensorFlow Lite. Se pretende proporcionar una herramienta interactiva y práctica para reconocer gestos humanos, con aplicaciones potenciales en sistemas de control de dispositivos y accesibilidad.

Aplicación móvil de clasificación de gestos:

Esta aplicación de cámara clasifica de manera continua los gestos capturados por la cámara frontal de su dispositivo. Las siguientes instrucciones le guiarán en el proceso de creación y ejecución de la demostración en un dispositivo Android.
Los archivos del modelo se descargan automáticamente a través de scripts de Gradle durante la construcción y ejecución de la aplicación. No es necesario realizar ninguna acción adicional para descargar explícitamente los modelos TFLite en el proyecto.

El modelo ha sido entrenado con las siguientes imágenes de gestos con las manos:
![image](https://github.com/erikzon/proyectofinalIA/assets/112149263/57996fa5-77ef-4c69-87a3-f3ef49442c4e)
 
El proyecto se basa en TensorFlow Lite, una versión optimizada de TensorFlow diseñada para aplicaciones móviles y de dispositivos embebidos. Se implementa un modelo de red neuronal convolucional (CNN) entrenado para clasificar gestos humanos utilizando datos de entrada de sensores del acelerómetro y el giroscopio de dispositivos Android.
