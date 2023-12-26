# Predicción de satisfacción de clientes con AutoML 🤖


Implementacion de procesamineto automatico. Utilizaremos una librería que automatiza el proceso de ingeniería de características, entrenamiento y despliegue del modelo predictivo. 

# Herramientas 🔧

* Python
* Numpy
* Pandas
* Pycaret


# Tubería de procesamiento, entrenamiento y predicción  🧪

Luego de extraer la data de la fuente de datos, aplicamos la tubería de preprocesamiento y entrenamiento. Esta funcionalidad ejecuta de manera automática el proceso iterativo de diseñar un modelo predictivo, probando varios modelos para la configuración de preprocesamiento definida y devolviendo el modelo con mejor desempeño, obteniendo una calificación AUC del 81% . Esta implementación se encuentra en _**pipeline_model.ipynb**_. 

# Finalización de la tubería 🏁

Finalmente exportamos la tubería generada y probamos sobre data cruda. Donde podemos observar que la tubería pre procesa la data, la entrega al modelo y arroja una predicción. Contrastando estas predicciones con los resultados conocidos de antemano, el modelo conserva la calificación AUC, obteniendo un 85%. 

Este proceso puede observarse en _**predict_model.ipynb**_. Por lo cual se tiene un modelo listo para exportar y utilizar en producción.

