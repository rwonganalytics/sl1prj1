# sl1prj1
Proyecto 1 Statistical Learning 1
Estudiante: Ramiro Wong (23000952)
Curso: Statistical Learning 1, 2024


Trabajamos con el dataset Telco Customer Churn, el cual busca predecir el "churn" (si un cliente dejará el servicio a final de mes), basado en data del cliente
y los servicios que contrata, con el objetivo de entender su comportamiento y retenerlo. 

Cada registro representa a un cliente. Cada columna representa un atributo del cliente.

El dataset contiene información como: 

*clientes que dejaron el servicio durante el ultimo mes - columna churn
* Serivicios a los que se ha suscrito el cliente - telefono, líneas multiples, internet, seguridad en linea, backup en linea, proteccion de dispositivo, 
soporte tecnico, streaming de TV, streaming de peliculas
* Informacion de la cuenta del cliente - cuanto tiempo han sido clientes, contrato, metodo de pago, si tienen facturacion sin papel, cargos mensuales y cargos totales
* Informacion demografica de clientes - genero, rango de edad y si tienen pareja y dependientes.

En la primera fase del proyecto, se tenía como objetivo analizar el dataset y prepararlo para cargarlo al algoritmo de Machine Learning
para clasificación. Se trabajaron dos notebooks de Pyhton:

1. Analisis exploratorio y seleccion de variables
2. Pipeline de ingeniería de características: imputacion de faltantes, codificación de variables categóricas, tratamiento de outliers, transformación de variables y estandarizacion


REFERENCIAS:
Kaggle. (2018). "Telco Customer Churn". En: https://www.kaggle.com/datasets/blastchar/telco-customer-churn. [consultado 02/06/2024]
