# Diabetes_readmision_project
En este repositorio se encuentran cuatro directorios diferentes: Aplicación, archivos_csv, modelos y notebooks. A continuación, se explica lo que archivos contiene cada uno de estos:
1-Aplicación
En este directorio se puede encontrar la aplicación de Django que se ha desarrollado, y la plantilla del archivo csv que se necesita para utilizar la aplicación. En esta plantilla hay que introducir los datos de cada paciente en filas diferentes y estos datos tienen que ir en la misma celda separados por una coma.
2-archivos_csv 
Este directorio contiene los siguientes directorios y archivos:
  •	Datos entrenamiento:
    o	X_tes.csv, y_Test.csv: Los datos que se han utilizado para las pruebas de los modelos.
    o	X_val.csv, y_val.csv: Los datos de validación que se han utilizado en los entrenamientos de Redes Neuronales.
    o	X_train_rn.csv, y_train_rn.csv: Los datos de entrenamiento que se han utilizado para entrenar las redes neuronales.
    o	X_train.csv, y_train.csv: Los datos que se han utilizado en el entrenamiento de los Árboles de decisión y Random Forest. Son la unión de los datos que se encuentran en X_val.csv, y_val.csv, X_train_rn.csv, y y_train_rn.csv.
    o	Los datos que se han utilizado para las pruebas de los modelos.
    o	Los datos de validación que se han utilizado en las redes neuronales.
    •	Datos iniciales:
    o	diabetic_data.csv: La base de datos inicial.
    o	IDs_mappings.csv: el mapeo de los datos iniciales.
  •	Datos preprocesados:
    o	Datos_procesados.rar: archivo que contiene el archivo CSV con los datos procesados en la etapa de preparación y limpieza de los datos.													
3-Modelos:
Este directorio contiene los 30 modelos que se han creado durante el proyecto.
4-Notebooks:
Contiene los tres notebooks creados para la comprensión de los datos, para la preparación y limpieza de los datos y para el modelado y análisis de resultados.
