#### [Atrás](introduccion.md) -- [Índice](index.md) -- [Adelante](datos.md)
***

# Metodología

## Data Augmentation

![augmentation](metodologia/augmentation.png)

## Obtimizado

| Parámetro | Red convolucional simple | Red basada en ResNet| Red basada en DenseNet |
| ------------- | ------------- | ------------- | ------------- |
| Obtimizador | Stochastic gradient descent | Stochastic gradient descent | Stochastic gradient descent |
| Ratio de aprendizaje | 0.0001 | 0.0001 | 0.0005 |
| Momentum | 0.9 | 0.9 | 0.9 |
| Tamaño de batch | 128 | 128 | 128 |
| Número de epochs | 1.000 | 3.000 | 3.000 |

## Red convolucional simple

![convoRGB_plot](convoRGB/convoRGB_plot.png)

![convoRGB_summary](convoRGB/convoRGB_summary.png)


## Transferencia de conocimiento con ResNet

![resNet_plot](resNet/resNet_plot.png)

![resNet_summary](resNet/resNet_summary.png)


## Transferencia de conocimiento con DenseNet

![denseNet_plot](denseNet/denseNet_plot.png)

![denseNet_summary](denseNet/denseNet_summary.png)


## Entorno de ejecución Google Colab

![entorno](colab/entorno.png)

![gpu](colab/gpu.png)

***
#### [Atrás](introduccion.md) -- [Índice](index.md) -- [Adelante](datos.md)
