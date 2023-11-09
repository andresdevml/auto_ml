# Predicción de satisfacción de clientes con AutoML 🤖


Dadas las características del cliente y las respuestas dadas en la data, nuestro objetivo es predecir la respuesta del cliente al servicio, como satisfactorio o no satisfactorio. 

Utilizaremos una librería que automatiza el proceso de ingeniería de características, optimización y despliegue del modelo predictivo. 

# Herramientas 🔧


* Python
* Numpy
* Pandas
* Pycaret


# Tubería de procesamiento- entrenamiento-predicción  🧪

Luego de extraer la data del repositorio de Kaggle con _**data_extraction.ipynb**_, aplicamos la tubería de preprocesamiento y entrenamiento. Esta funcionalidad ejecuta de manera automática el proceso iterativo de diseñar un modelo predictivo, probando varios modelos para la configuración de preprocesamiento definida y devolviendo el modelo con mejor desempeño, obteniendo una calificación AUC del 81% . Esta implementación se encuentra en _**pipeline_model.ipynb**_. 

Finalización de la tubería 🏁

Finalmente exportamos la tubería generada y probamos sobre data cruda de los clientes. Donde podemos observar que la tubería pre procesa la data, la entrega al modelo y arroja una predicción, contrastando estas predicciones con los resultados conocidos de antemano el modelo conserva la calificación AUC, obteniendo un 85%. Este proceso puede observarse en _**predict_moder.ipynb**_. Por lo cual se tiene un modelo listo para exportar y utilizar en producción.

