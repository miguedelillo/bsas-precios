# bsas-precios
Predicción de precios. Departamentos Buenos Aires. 

Proyecto básico de análisis de datos y machine learning. Realizado con datasets públicos obtenidos del Gobierno de la Ciudad de Buenos Aires.
Consiste por una parte la exploración del dataset utilizado, para la posterior identificación de los atributos útiles para el modelo de predicción.
La misma se realizó gráficamente con la biblioeta Seaborn y MatPlotLib. 
Luego, se presentan dos modelos para la predicción, árbol de regresión y Ridge, y se compara el rendimiento.
Al día de la fecha se consiguió un puntaje R2 de 0.74. Puede deberse a la falta de características en el dataset que modificarían el precio de la
propiedad, como pueden ser si tiene pilea o no, antiguedad del edificio, cercanía a un espacio verde, entre otros. 
Por eso el próximo objetivo en este proyecto es ampliar el dataset con diversos datos geográficos que puedan ser obtenidos con la dirección
de la propiedad junto con otros datasets, como la cercanía con estaciones de Subte, paradas del metrobús, etc. La principal dificultad que
veo recide en la ausencia de los valores de longitud y latitud en el dataset. Para superar este obstáculo se prevee el uso de APIS para traducir
la dirección de la propiedad en longitud y latitud. 


