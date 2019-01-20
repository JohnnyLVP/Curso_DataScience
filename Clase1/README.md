# ¿Que es ciencia de Datos?

Se encuentra en la interseccion de las habilidades de Hacking (OS,Python, Base de Datos, R, etc), Matematica(Algebra lineal, Vectores, etc), Negocio (Conocimiento del Negocio).

Data Science, toma parte del Machine Learning (Modelos)

<p align="center">
	<img width="400" height="300" src="http://www.trcimplan.gob.mx/blog/introduccion-a-la-ciencia-de-datos-parte-1/ciencia-de-datos.png">
</p>

## 1. Tipo de Datos: 

<p align="center">
	<img width="400" height=500" src="http://3.bp.blogspot.com/-RngguMea6hA/VkAdN05YEqI/AAAAAAAABQE/iT6QP-9A7hE/s1600/piramide.png">
</p>

## 2. Exploracion de Datos (EDA)

Encontrar patrones relevantes en la data sin modificacion

## 3. Preproccesing

* Limpieza, depuracion de datos
* Transformacion de los datos

## 3.1. PreProccesing con Python

### 3.1.1. Python Ecosystem

* El creador es Van russel 
* Beneficios:

<p align="center">
	<img width="400" height="300" src="https://www.sitesbay.com/python/images/features-of-python.png">
</p>


### 3.2. PreProccesing Issues

* Inconsistencias en data 
	* Por ejemplo, En columnas de Edad, donde se espera un rango determinado Entero, se podria encontrar negativos, 400 años, etc.
	* Inconsistencias por Tipo de Datos
		* Se espera Entero, pero viene Strings
		* Esperas tipo de datos Date y viene datos tipo Float

* Imputacion de Datos
	
	* Datos Nulos (NaN): 
		* Dependiendo de cantidad de Nulls en filas y columnas se deberian de eliminar
		* Dependiendo de la variable y su distribucion, para imputar podria ponerse el valor de una media o mediana de la variable
		* Algo mas sofistifacado podria hacerse un modelo para imputar datos (KNN, por ejemplo)

* Escalamiento
* Normalización

## 4. Feature Engineering

* *Feature Selection:* Si hay columnas redundantes el modelo saldra erroneo, habra mucho ruido.
* *Feature Extraction:* hay que quedarse con lo necesario.
* *Feature Transformation:* Se modela la info, "tallandola", para tenerla como se necesita.


<p align="center">
	<img width="500" height="450" src="https://i1.wp.com/blog.kaggle.com/wp-content/uploads/2015/04/drop_shadows_background2.png?resize=1024%2C563">
</p>


## 5. Modeling

* Train -> Entrenamiento
* Test -> testing

* Clasificación 
* Regresión
* Clustering

## 6. Tunnning

* Darle un conjunto de Parametros al modelo, de tal manera que de un tiempo 
* Se puede hacer con GridSearch & RandomSearch

## 7. Deployment

* Persistencia: Model.m -> 10 MB
 







