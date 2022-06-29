#### [Atrás](resultados.md) -- [Índice](index.md) -- [Siguiente](bibliografia.md)
***

# Conclusiones

- Se ha descrito el objetivo del trabajo, aplicación de redes neuronales artificiales, a un dataset preexistente, el Kvasir-Capsule, con 3 modelos basados en redes convolucionales y con el uso de transferencia de aprendizaje.

- El modelo convoRGB, entrenado completamente con el dataset, presenta métricas entre 80% y 90% según se consideren todas las muestras o se evaluen por métrica y posteriormente se agregen.

- Los modelos ResNet y DenseNet, que hacen uso de transferencia de conocimiento, obtiene resultados que no difieren sustancialmente de los obtenidos por ConvoRGB.

- El dataset está muy desbalanceado, lo que compromete la mejora de resultados con estas u otras metodologías. Además, despierta cierto recelo sobre su exactitud, lo que de nuevo incidiría en la calidad del modelado.

- Las redes neuronales artificiales parecen un instrumento adecuado para la clasificación de imágenes endoscópicas como las del dataset Kvasir-Capsule, con las limitaciones reseñadas previamente.

- De las pruebas realizadas no se ha evidenciado una mejora significativa en los resultados derivados del uso de redes complejas y profundas preentrenadas previamente (transferencia de aprendizaje).

# Perspectivas abiertas

- Uso de **otras redes neuronales**: en los últimos años se han desarrollado nuevas redes neuronales capaces de mejorar los resultados de ResNet y DenseNet. Se suguiere explorar si otras redes son capaces de mejorar los resultados de los modelos de este trabajo.

- **Desbalanceado**: el dataset empleado está claramente desbalanceado. Se ha evidenciado que supone un inconveniente (a la luz de las métricas) y por tanto una limitación. Se sugiere la búsqueda de metodologías para compensar este balance, como pesos, augmentation selectiva u otra.
- **Revisión dataset**: desde el declarado desconocimiento del campo del dataset, sería conveniente una revisión del mismo, puesto que no tiene demasiado sentido modelar a partir de datos en los que no se confía.

- Uso de **splits**: en trabajos previos sobre este dataset se emplearon unos splits que sería interesante estudiar y comparar en resultados con el uso de todo el dataset.

***
#### [Atrás](resultados.md) -- [Índice](index.md) -- [Siguiente](bibliografia.md)
