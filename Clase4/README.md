# Clase 4

## Maldicion de la alta dimensionalidad 

Existe un problema con los atributos que son altamente redundantes, si tenemos muchas variables la ejecucion del algoritmo demorara mucho mas. Si bien es cierto, las computadoras de hoy en dia tienen mucha capacidad, si metemos variables redundantes, inservibles sera por las puras tener una computadora con alto rendimiento para un modelo con variables que no necesita. 

## Como evitar Redundancia (Maldicion)

* Reducir la cantidad de dimensiones
	* Redundancia
	* Correlacion
	* ACP
	* Factorial
	* Clustering

* Seleccionar la cantidad necesaria de atributos
	* Stepwise
	* Random Forest
	* Boruta
	* Algoritmos Geneticos

### Analisis de Componentes Principales

Consiste en buscar conbinaciones lineales, de las variables originales. Que representa lo mejor posible a la variabilidad presente en los datos. 

#### Pasos:

* Analisis de matriz de correlaciones
* Seleccion de componentes principales
* Analisis de la matriz factorial
* Interpretacion del CP
	* Los coeficientes factoriales deben ser proximos a 1
	* Una variable debe tener coeficientes elevados solo con un factor
	* No deben existir factores con coeficientes similares
* Calculo de las puntuaciones factoriales

<p align="center">
	<img src="http://www.nlpca.org/fig_pca_principal_component_analysis.png">
</p>


