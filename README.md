# Cats-and-dogs

### Enunciado:

Con el fin de emplear las herramientas vistas en el curso se va a desarrollar un proyecto completo en el que utilizaremos diversas de ellas para ver como poder integrarlas en la realización de un proyecto de IA.

En este caso vamos a suponer una aplicación de clasificación de imágenes en la que desarrollaremos el código en un editor (Pycharm) al que conectaremos nuestro repositorio propio (Github) y dónde desarrollaremos el código (Python) empleando librerías de inteligencia artificial (Pytorch). Se usará un dataset y se realizará el entrenamiento de una red neuronal.

La aplicación se encapsulará en un contendor (Docker) y se conectará a una base de datos (MongoDB) que almacenará la información que la IA prediga sobre los datos nuevos empleados.

<img width="688" alt="image" src="https://user-images.githubusercontent.com/91574355/226205965-45f50206-5c97-46be-9d91-2f255e132807.png">

A modo de ejemplo, se realizará una tarea de clasificación mediante redes neuronales. En este caso, el problema a resolver se centrará en la clasificación automática de imágenes de perros y gatos con el fin de predecir si esta es un perro o un gato sin conocimiento previo.

Para ello emplearemos el siguiente dataset que podemos encontrar en Kaggle: 

https://www.kaggle.com/competitions/dogs-vs-cats/data

El dataset consta de un total de 25000 imágenes de las cuales la mitad corresponden a perros y la otra gatos debidamente anotadas. Adicionalmente se proporcionan imágenes de test de las cuales no se conoce su etiqueta y que serán las que podemos usar para predecir.

### Tareas
1 – Clonar repositorio del proyecto (este contiene el código de entrenamiento y predicción así como el modelo previamente entrenado): 

2 – Crear una nueva rama en el proyecto con el siguiente formato (tu nombre de usuario en la plataforma): NombreApellido1Apellido2

3 – Desarrollar el código Python para entrenamiento de una red neuronal con el dataset proporcionado (6_training.py).

4 – Entrenamiento, evaluación de resultados y creación de código para realizar predicciones con el modelo entrenado (7_predict.py). ***Nota: si el entrenamiento lleva mucho tiempo o no se tienen recursos suficientes ya se proporciona el modelo entrenado para su uso.

5 – Almacenamiento de las predicciones en una base de datos Mongo (empleado pymongo en Python).

6 – Encapsulamiento del proyecto en un contenedor Docker que tomará unos datos de entrada de una carpeta y realizará las tareas del script para predicciones.

7 – Añadir nuevos ficheros y cambios (scripts modificados, dockerfile...) al repositorio local (commit) y subir la nueva rama creada al repositorio en Github (push). 

8 – Realizar una pequeña memoria (no más de una página) con los pasos realizados y subirla a la tarea del módulo habilitada para tal efecto.
