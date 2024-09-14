# **PROYECTO SERIES TEMPORALES**
  ![Badge JupyterNB](https://img.shields.io/badge/HERRAMIENTA-JUPYTER_NOTEBOOK-orange)
  ![Badge Language](https://img.shields.io/badge/LENGUAJE-PYTHON-green)
  ![Badge Machine](https://img.shields.io/badge/MODELO-MACHINE_LEARNING-yellow)
![Image Temp series](https://aprendeconeli.com/wp-content/uploads/2020/05/AdobeStock_300167162-scaled.jpeg)

## **PROYECTO No 3** : *MODELOS MACHINE LEARNING*


El Objetivo principal de este notebook es el analisis del **FLujo Vehicular de la Estacion Illia** en la ciudad de Buenos Aires con forma de pago en efectivo,
trabajamos con los datos otogados por  el Gobierno de Argentina, realizamos todo el analisis exploratorio, transformacion de features y modelos machine learning.

El dataset contiene datos desde el año 2017  hasta el año 2020.
el dataset contiene atributos como fecha,tipo de vehiculo,forma de pago,estacion y cantidad de pasos,esta ultima se refiere a la cantidad de vehiculos que transitan por el peaje.

Este dataset tiene como finalidad poder predecir el flujo vehicular para el año 2020, establecieron varios modelos intentando conseguir las mejores metricas.

Es importante tener en cuenta que para el año 2020 existe una condicion muy atipica que es la pandemia que estamos atravesando actualmente, lo que hace que el forecasting que realicemos con nuestro modelo no sea adecuado y optimo para realizar una adecuada precision. 

si deseas obtener mas datos del flujo vehicular de Argentina de otros años puedes ingresar al siguiente link : *https://data.buenosaires.gob.ar/dataset/flujo-vehicular-por-unidades-peaje-ausa*


## **PROYECTO No 4** : *SERIES TEMPORALES MODELOS CLASICOS Y LIBRERIA PROPHET*


En este notebook decidimos trabajar los mismos datos del proyecto No 3 pero esta vez trabajamos con modelos clasicos estadisticos para la aplicacion de series temporales, alli transformaremos la serie en una serie estacionaria que permita implementar modelos tales como modelos autorregresivos, modelos medias moviles, modelos SARIMAX, ademas tambien trabajamos con la libreria Prophet creada por facebook.

El objetivo es identificar si mejora la prediccion con la implementacion de estos modelos.
