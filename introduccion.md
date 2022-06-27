#### [Atrás](index.md) -- [Índice](index.md) -- [Siguiente](metodologia.md)
***

# Introduccion

## La red neuronal

Las neuronas son estructuras biológicas del sistema nervioso capaz de enviar mensajes electroquímicos a través del cuerpo. Las neuronas se catacterizan por tener una entrada y una salida o muchas de ellas. Las neuronas son capaces de analizar las entradas y enviar dicho análisis en un mensaje por sus salidas. Es decir, una neurona toma decisiones basadas en la información disponible en sus inputs. 

Las neuronas se interconectan formando redes, donde cada una tiene una función específica: las primeras reciben datos del exterior, las neuronas ocultas hacen cálculos y procesos internos, mientras que las últimas ofrecen las respuestas al exterior. Las neuronas ocultas aprenden gracias a ejemplos cuya respuesta se conoce, mediante el entrenamiento. Tras éste, son capaces de contestar también a las preguntas sobre nuevos casos que nunca vieron previamente.

Un conjunto grande de neuronas es capaz de aprender a resolver problemas complejos. Por esto en el Deep Learning existe una rama denominada redes neuronales artificiales que tomando como base el concepto de red neuronal desarrolla algoritmos capaces de aprender de una manera similar a las redes neuronales.

## Redes neuronales artificiales

Los orígenes de las redes neuronales se situan en la mitad del siglo XX, pero resurgió con intensidad a principios del XXI gracias a nuevos trabajos y a la capacidad de los ordenadores y las GPUs para procesar datos de manera masiva.

Las redes neuronales son sistemas basados en combinaciones lineales a la que se aplica una función de activación que le dota de un caracter no lineal. Los coeficientes de dichas combinaciones lineales se ajustan de manera iterativa con el conocido método de "back propagation" que mejora los parámetros en función de su gradiente.

Las redes neuronales se agrupan por capas, que se relacionan entre ellas. Hay diversos tipos de capas de redes neuronales entre las que destacan las densas y las convolucionales. Las neuronas de una capa densa actúan como se ha descrito previamente, mientras que las capas convolucionales están formadas por filtros de ventana flotante que se desplazan sobre una imagen para obtener alguna característica geométrica 2D o característica tonal de la misma. Un conjunto de capas convolucionales aspira a caracterizar la mayoría de rasgos que el sistema visual humano observa y reconoce en una imagen.

## Frameworks para redes neuronales

La expansión y generalización del lenguaje de programación Python y de sus extensiones para cálculo científico, fue un verdadero terreno abonado para la aparición de frameworks expecíficos de Data Science y en particular de redes neuronales o inteligencia artificial. Entre las múltiples propuestas que se encuentran en la bibliografía, destaca a criterio del autor TensorFlow y su API Keras.

Por otro lado, herramientas y paradigmas como los Jupyter-Notebooks, así como los servicios de cálculo en línea como los ofrecidos por Google-Colab, han democratizado el acceso a la vez que extendido el uso y aplicaciones de la inteligencia artificial tanto para problemas clásicos como para nuevos desafíos. 

## Cápsula endoscópica

Uno de los campos de aplicación de cualquier desarrollo tecnológico es el ámbito de la salud. La miríada de pruebas diagnósticas que tienen por resultado una imagen o serie de imágenes crece de manera ingente cada año. El análisis automático o asistido de dichas imágenes tiene una indudable utilidad por lo que centra el interés de muchos grupos de trabajo.

En el marco anterior, existe un trabajo para la elaboración de un repositorio de imágenes endoscópicas del sistema digestivo humano que constituye el punto de partida de este Capstone Project. Así se pretende hacer una prospección de la capacidad de las redes neuronales convolucionales para la identificación de lesiones y regiones características en imágenes medicas de dicho dataset.

En los siguientes apartados de detalla la metodología empleada y se describe el dataset. A continuación se muestran los resultados y las conclusiones de este trabajo.

***
#### [Atrás](index.md) -- [Índice](index.md) -- [Siguiente](metodologia.md)
