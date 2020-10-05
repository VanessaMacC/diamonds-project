# diamonds-project

<p align="center">
<img src="https://lh3.googleusercontent.com/proxy/xpkAtpNsiuBi8zOUBCjl4gdn8GoDBEYfNeMp2z6tKXlKsmUWavVVBKaXXV7r49rx-Xpx4MC0ybnlYQF-DTBPZlZEaYjGDQ" width="350" height="250">

El **objetivo** de este proyecto es predecir mediante machine learning el precio de los diamantes atendiendo a sus características (peso, color, calidad de corte).

## Estructura

- Input:

1.- *train.csv*\
2.- *predict.csv*\
3.- *sample.csv*

- Tests:

Esta carpeta contiene el archivo de limpieza y análisis del dataset propuesto para realizar el proyecto (*train_completed*).\
Las librerías usadas son las siguientes:

**pandas**\
**requests**\
**matplotlib.pyplot**\
**sklearn**

En él entrenamos varios modelos de predicción y una vez analizadas las métricas, seleccionamos los mejores, en este caso:

RandomForestRegressor\
HistGradientBoostingRegressor\
GradientBoostingRegressor\
DecisionTreeRegressor

- Predicciones:

Tras entrenar los modelos y seleccionar los que nos dan mejores métricas, ejecutamos de nuevo con todos los datos y obtenemos el resultado por modelo para exportarlo a csv.

- Output:

Archivos csv con la predicción obtenida de cada modelo cumpliendo con el formato de la competición Kaggle de nuestro bootcamp (<https://www.kaggle.com/c/diamonds-datamad0820>)

<p align="center">
<img src="./ResumenDiamonsProject.jpg" width="700" height="500">

(<https://www.youtube.com/watch?v=naoknj1ebqI>)










