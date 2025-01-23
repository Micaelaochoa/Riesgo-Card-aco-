# Riesgo-Cardiaco


Los ataques cardíacos son una de las principales causas de muerte a nivel mundial y la predicción temprana del riesgo puede reducir significativamente las tasas de mortalidad.Existen numerosos factores que si son controlados y tratados a tiempo ayudan a prevenir el riesgo. 
Un factor de riesgo cardiovascular (FRCV) es una característica biológica o un hábito o estilo de vida que aumenta la probabilidad de padecer o de fallecer a causa de una enfermedad cardiovascular (ECV), en aquellos individuos que lo padecen.

Este dataset fui obtenido de la pagina kaggle. El mismo contiene 50000 filas, cada una representa a un individuo. 
El conjunto de datos de predicción de riesgo de ataque cardíaco es un conjunto de datos sintético diseñado para modelar factores de la vida real que influyen en los riesgos de ataque cardíaco.En los registros hay información sobre  los diferentes factores que pueden infuir en el riesgo de ataque cardíaco. Estos son: edad,género,actividad fisica,indice de masa corporal (IMC), colesterol,diabetes,riesgo cardiaco,hipertensión arterial, fumador,consumo de alcohol, electrocardiograma e historia familiar. 

Preguntas
-Que porcentaje de la poblacion tiene riesgo alto de contraer un infarto?
-Cuales son los principales factores que lo ocacionan ?

Hipotesis
-Las presencia de diabetes es el principal factor causante en relacion a los demas 
-La edad no es un factor relevante 
-El bajo nivel de actividad fisica, aumenta el riesgo cardiaco.
-


Consultas en SQL Server 
A parir de la siguiente consulta se obutvo la cantidad de personas que tenian nivel de actividad fisica "ALTO" y se hizo una union derecha con la tabla riesgo_ infarto. A partir de la segunda tabla se dio a la conocer las personas que coincidian con la primera concidición (tabla1) y a su vez con la segunda condición "BAJO". 

SELECT  count (AF.ID_INDIVIDUO) Cantidad_ind FROM ['ACTIVIDAD FISICA] AF
RIGHT JOIN RIESGO_INFARTO R
ON AF.ID_INDIVIDUO = R.ID_INDIVIDUO
WHERE [Nivel de actividad Fisica] ='ALTO' AND RIESGO = 'BAJO'
Resultado:
4944




