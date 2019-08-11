# Taller de Deep Learning

Estos son algunos ejercicios y ejemplos que facilitan la transición hacia los temas de redes neuronales
y proveen de los elementos necesarios de Deep Learning para trabajar con redes neuronales convolucionales.

## Estructura del repositorio

Son libretas de Jupyter, escritas en Python y utilizando en su mayoría [`keras`](https://keras.io/),
[`TensorFlow`](https://www.tensorflow.org/), entre otras librerías de ayuda.

Cada libreta está autocontenida, todo el material necesario para trabajar está en cada libreta, junto con
código, explicaciones y/o comentarios relevantes de cada tema.

La estructura está basada e inspirada en el libro [Deep Learning](https://www.deeplearningbook.org/), de
donde se tomaron algunas ideas de implementación.

## Uso del repositorio

Para utilizar este repositorio es tan fácil como clonarlo

`git clone https://github.com/edwinb-ai/deep-workshop.git`

lo que va a crear un nuevo directorio con todos los documentos.

Este repositorio tiene su propio entorno de [`conda`](https://conda.io/en/latest/), que puede ser creado con el
siguiente comando

`cd deep-workshop`

`conda env create -f entorno.yml`

Este comando pedirá confirmación de que se van a agregar todas las librerías y dependencias necesarias para
ejecutar el contenido de este repositorio.

Una vez descargadas todas las librerías hace falta **activar el entorno**, que se puede hacer con el siguiente
comando

`conda activate deep_workshop`

activando el entorno, y permitiendo ejecutar efectivamente todo el repositorio.
