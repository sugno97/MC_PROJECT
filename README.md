Estos son ejercicios personales donde realizo entrenamiento y predicciones.
Uso el archivo study_performace.csv para analizar los datos numericos y categoricos
Se analiza el score obteniendo su promedio de los scores de los estudiantes
Para analizar las variables categoricas se usa One hot encoder para transformarlo en 1 y 0
Se usa tambien el ordinal encoder para clasificar las categorias de mayor a menor.
Por ultimo se usa dos modelos de machine learning como RandomForestRegressor y LinearRegression.
Asimismo entrenamos y predicimos los valores.Sin embargo, para comprobar si estan bien los resultados dividimos se usa un 80% de datos entrenos y el 20 % de prueba.
De esta manera, con el sklearn.metrics podemos verificar el porcentaje de predicciones tiene el modelo.

