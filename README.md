# Riesgo-Cardiaco


Los ataques cardíacos son una de las principales causas de muerte a nivel mundial y la predicción temprana del riesgo puede reducir significativamente las tasas de mortalidad.Existen numerosos factores que si son controlados y tratados a tiempo ayudan a prevenir el riesgo. 
Un factor de riesgo cardiovascular (FRCV) es una característica biológica o un hábito o estilo de vida que aumenta la probabilidad de padecer o de fallecer a causa de una enfermedad cardiovascular (ECV), en aquellos individuos que lo padecen.

Este dataset fue obtenido de la pagina kaggle. El mismo contiene 50000 filas, cada una representa a un individuo. 
El conjunto de datos de predicción de riesgo de ataque cardíaco es un conjunto de datos sintético diseñado para modelar factores de la vida real que influyen en los riesgos de ataque cardíaco.En los registros hay información sobre  los diferentes factores que pueden infuir en el riesgo de ataque cardíaco. Estos son: edad,género,actividad fisica,indice de masa corporal (IMC), colesterol,diabetes,riesgo cardiaco,hipertensión arterial, fumador,consumo de alcohol, electrocardiograma e historia familiar. 

Se realizó el analisis estadístico de los datos donde se importo el dataset en un notebook de jupyter
Donde se importaron las librerias(pandas,numpy)para la visualización, limpieza y análisis de los datos. En el analisis estadistico que se implemento es de tipo descriptiva e inferencial. 

Pregunta
-Que porcentaje de la poblacion tiene riesgo alto de contraer un infarto?

Respuesta
- Solo un 20% de la población en estudio tiene alto riesgo de contraer un infarto

Hipotesis
-HO: Las mujeres mayores a 50 años tienen la misma probabilidad que los hombres de igual edad, de contraer un ataque cardiaco.
 HI:Las mujeres mayores a 50 años tienen menos probabilidad que los hombres de igual edad, de contraer un ataque cardiaco.
 
-HO: El bajo nivel de actividad física, aumenta el riesgo cardíaco.
 HI: El nivel de actividad física no está relacionado con el riesgo cardíaco.
 
-HO: Las personas con obesidad son más propensas a desarrollar diabetes.  
 HI:No hay relación entre la obesidad y el desarrollo de diabetes.
   

Resultados: 
 Las 3 hipótesis planteadas son aceptadas con un 95% de confianza.Dado que el valor de p, obtenido del test de chi2, fue mayor a 0.05. Por lo que se aceptan las hipotesis nulas(HO)



 



