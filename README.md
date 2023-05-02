# ProyectoFinalAnalitica
Este es el codigo del proyecto final de la clase de Analítica de Datos en la USFQ.
# 📚 Clase de Analitica

👋 ¡Hola a todos! Bienvenidos al repositorio de **Nuestro Proyecto de la clase de Analítica **. Aquí encontrarás información detallada sobre cómo configurar y utilizar este proyecto. ¡Vamos a sumergirnos en los detalles! 😄

## 📖 Introducción

**El proyecto** 

A lo largo de este documento, te guiaremos paso a paso para que puedas configurar y utilizar **Mi Proyecto Genial**. ¡Estamos seguros de que te encantará! 💖

## 🚀 Contexto

Se utilizó una base de datos de un hospital público para desarrollar un modelo de predicción efectivo que pueda identificar a los pacientes con alta probabilidad de sufrir un accidente cerebrovascular. El objetivo es abordar uno de los problemas de salud más graves a nivel mundial. En el proyecto se realizará una limpieza de datos adecuada, se analizarán las variables predictivas y se implementarán algoritmos de predicción adecuados.

## 🛠️ Base de datos

Base de Datos:
**Varibables predictivas	Descripción**
Hypertension (categórica)	1: Paciente tiene hipertensión
0: Paciente no tiene hipertensión
Hearth Disease (categórica)	1: Paciente tiene enfermedad cardiaca 0: Paciente no tiene enfermedad cardiaca
Married (categórica)	Yes: Paciente se ha casado
No: Paciente no se ha casado
Work (categórica)	Children: Cuida niños Govt_jov: Trabaja en el gobierno Never_worked: Nunca ha trabajado Private: Trabaja en el sector privado Self-employed : Trabajador por cuenta propia
Residence (categórica)	Rural: Vive en área rural 
Urban: Vive en área urbana
Avg glucose level	Nivel de glucose promedio
Bmi	Body mass index
Smoking	Formerly smoked, never smoked, smokes, Unknown
Gender	Male, Female, Other
Age	Edad del paciente

**Variable de respuesta	Descripción**
Stroke	1: Paciente ha tenido ataque cerebral 
0: Paciente no ha tenido ataque cerebral



## 🤝 Contacto

Si tienes preguntas o comentarios sobre el proyecto, no dudes en ponerte en contacto con [tu nombre] a través de [tu correo electrónico] o [redes sociales].



## 🎉 Conclusión
Conclusiones.
•	La parte de preprocesamiento es la más importante y es clave para el correcto manejo de los datos en los siguientes pasos.
•	Por medio de los gráficos podemos ver la distribución de datos y mucha información de medidas de tendencia central para cada variable. 
•	Existen muchos métodos para balancear el set de entrenamiento y muchos modelos a implementar, por lo que no se puede asegurar que el procedimiento hecho sea el óptimo. De los dos modelos implementados el de Ensamble es más robusto y mejor según la métrica Recall, ya que al se un modelo que predice una condición medica grave, se debe minimizar los falsos negativos, es decir tratar de que no existan personas propensas a tener el ataque y que no se los medique o controle.
•	Se optimizaron los modelos de Redes Neuronales y de Regresión logistica, enfocandonos en maximisar el RECALL, como resultado se obtuvo los mejores valores en esta metrica con estos dos modelos en comparación a otros modelos.
•	Sabiendo que una AUC ROC aleatoria tendría una puntuación de 0.5, lo que significa que el modelo no tiene habilidad de clasificación, y que para ningun modelo se obtuvo un valor cercano a 0.5, se puede afirmar que todos los modelos tanto para el set de validación como el de prueba tiene habilidad de clasificación.
•	Por medio de los valores AUC en los sets para cada modelo se puede asegurar que el mejor puntuado, tanto en test como en validation, es el modelo de RegresiónLogistica, lo que indica que es el que tiene mejor habilidad de clasificación.
•	Por medio del valor de sensibilidad, tanto para train como validación, se puede ver que el modelo de regresión logistica es el que mejor minimiza los falsos negativos.


• Referencias
•	https://www.medigraphic.com/pdfs/conapeme/pm-2012/pm124g.pdf
•	https://www.mayoclinic.org/es-es/diseases-conditions/prediabetes/diagnosis-treatment/drc-20355284
•	https://repositorio.utp.edu.co/server/api/core/bitstreams/767003ef-6a5a-4b19-8d13-0c3a25b8f128/content
•	https://repositorio.saludcapital.gov.co/bitstream/handle/20.500.14206/4034/SDS-SHAREPOINT2-0107.pdf?sequence=1
•	Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., ... & Vanderplas, J. (2011). Scikit-learn: Machine learning in Python. Journal of Machine Learning Research, 12, 2825-2830.
•	Nocedal, J., & Wright, S. (2006). Numerical Optimization. Springer Series in Operations Research and Financial Engineering.
•	Hastie, T., Tibshirani, R., & Friedman, J. (2009). The Elements of Statistical Learning: Data Mining, Inference, and Prediction. Springer Series in Statistics.
•	Friedman, J. H. (2002). Stochastic gradient boosting. Computational Statistics & Data Analysis, 38(4), 367-378
•	Breiman, L. (1996). Bagging predictors. Machine Learning
•	Liaw, A., & Wiener, M. (2002). Classification and Regression by randomForest
•	Glorot, X., Bordes, A., & Bengio, Y. (2011). Deep sparse rectifier neural networks

     



 🥳
