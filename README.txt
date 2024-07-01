Estudiante: Ramiro Wong (23000952)
Curso: Statistical Learning 1, 2024

Proyecto 1, Fase 2

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

En la segunda fase del proyecto, se exploraron diferentes modelos de clasificación para predecir el churn. Los mismos se compararon con diferentes configuraciones de hiperparámetros, rankeandolos  de mejor a peor

Contenido:
WA_Fn-UseC_-Telco-Customer-Churn.csv - dataset original
output_ing_car.csv - dataset después del proceso de ingenieria de caracaterísticas
proyecto1-1_23000952 - notebook con analisis exploratorio
proyecto1-2_23000952 - notebook con pipeline de ingenieria de caracteristicas
proyecto1-3_23000952 - notebook modelos de clasificacion
ranking_modelos.xlsx - archivo con resultados de modelos optimizados, rankedados de forma descendiene por rendimiento


REFERENCIAS:
Kaggle. (2018). "Telco Customer Churn". En: https://www.kaggle.com/datasets/blastchar/telco-customer-churn. [consultado 02/06/2024]