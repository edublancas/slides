# Machine Learning 101

---

# Objetvos

* Clarificar la terminología: Inteligencia Artificial, Machine Learning, Data Science, etc.
* Desmitificar algunas creencias sobre el estado de la Inteligencia Artificial en 2017
* Explicar la relación que existe entre Machine Learning y Estadística
* Resumen de los conceptos más importantes en Machine Learning

---

# Parte I: Introducción

---

# 1. Inteligencia Artificial (AI)

---

# 1.1 ¿Qué es Inteligencia Artificial?

* Este término se aplica cuando una máquina imita funciones **cognitivas** que son propias de los seres humanos (Fuente: Wikipedia)
* La dificultad radica en definir cuáles son esas funciones cognitivas: ¿sumar? ¿reconocer un objeto? ¿entender el lenguaje?
* Es por ello que existe mucha ambigüedad respecto a qué es y qué no es Inteligencia Artificial

---

# 1.2 Inteligencia Artificial General

* El objetivo último de la Inteligencia Artificial es lo que se conoce como *Inteligencia Artificial General* (General AI) que consiste en diseñar una máquina que pueda realizar **cualquier** trabajo intelectual
* Y aunque **parece** que cada vez estamos más cerca de lograrlo (coches autónomos, máquinas que juegan go), la verdad que es aún estamos muy muy lejos de lograrlo...

---

# 1.3 Brevísima historia de la Inteligencia Artificial

* La Inteligencia Artificial inició en el *Darthmouth Summer Research Project on Artificial Intelligence* en 1956
* Después de la reunión hubo *avances muy significativos* en el campo, ¡las computadoras podían resolver problemas algebraicos!
* Durante esa época, los avances más significativos se dieron en Inteligencia Artificial **simbólica**

---

# 1.4 Límites de la Inteligencia Artificial simbólica

* La Inteligencia Artificial simbólica consiste en resolver problemas escribiéndolos como una serie de reglas (ej: ¿tiene orejas y cuatro patas? Entonces es  un perro)
* Dicho acercamiento es muy limitante, imaginemos escribir una lista exhaustiva de reglas para el manejo de un automóvil
* En la decada de los 90 la Inteligencia Artificial cambia completamente de un enfoque simbólico a un enfoque de uso de datos
* O dicho de otra manera: **en los 90 la comunidad de AI descubrió la Estadística**

---

# 1.5 Inteligencia Artificial basada en aprendizaje

* A lo que los medios se refieren por Inteligencia Artificial (al menos en 2017) es en realidad a un conjunto *muy* específico de técnicas de **análisis de datos**
* En los últimos años, la técnica que más avances ha tenido ha sido lo que se conoce como **Deep Learning**, que sigue siendo un conjunto de técnicas de aprendizaje
* La limitante actual de estos algoritmos es que son muy expecíficos, solo saben hacer una cosa (Ej: identificar elementos en una foto, comprender el lenguaje hablado, etc)


---

# 2. Estadística

---

# 2.1 Estadística

* Una rama de las matemáticas que comprende una serie de técnicas para **analizar datos** que presentan variabilidad
* El análisis de estos datos puede ser **descriptivo** (por ejemplo: las gráficas y tablas usadas por el INEGI para mostrar los resultados del censo de población)
* El análisis puede ser **inferencial** si pretende alcanzar conclusiones acerca de una *población* a partir de una *muestra*

---

# 2.2 Brevísima historia de la estadística

* Obtener conclusiones a partir de *datos incompletos* es un problema muy común
* A pesar de que los orígenes de la Estadística se oueden encontrar hasta el siglo V a.C., las técnicas *modernas* de estadística datan de finales del siglo XIX

Fuente: Wikipedia

---

# 2.3 Métodos estadísticos tradicionales

* Estimación puntual
	* Da un número sobre la cantidad que queremos *estimar* a partir de la muestra
	* Ej: ¿cuál es la estatura media de la *población* mexicana?
* Estimación por intervalo
	* Da un intervalo sobre la cantidad que queremos *estimar* tomando en cuenta la **variabilidad** en la muestra
	* Ej: ¿entre qué valores se encuentra la estatura media de la *población* mexicana?
* Pruebas de hipótesis
	* Permite contrastar dos *hipótesis*
	* Ej: ¿la estatura media de la *población* mexicana es mayor a 1.70 m?

---

# 2.4 ¿Cómo estimar en un escenario con incertidumbre?

* Para hacer *inferencias* sobre la realidad, la Estadística abstrae la realidad por medio de un *modelo estadístico*
* Para modelar la *incertidumbre* que tenemos al no conocer a toda la *población* la Estadística hace uso de la **Teoría de la probabilidad**

---

# 3. Probabilidad

---

# 3.1 Probabilidad

* ¿Qué es probabilidad?
* No existe una **interpretación** única y este hecho ha marcado la historia de la Estadística desde sus inicios
* En palabras coloquiales podemos decir que probabilidad es *una medida de la certeza de que cierto evento ocurra*
* A pesar de que no haya una interpretación única, la teoría de la probabilidad se encarga de dotar de rigurosidad matemática a esta teoría por medio de lo *axiomas de la probabilidad*

---

# 3.2 Probabilidad y Estadística

* La estadística hace una interpretación de probabilidad muy específico, visto desde un punto de vista **frecuentista**
* Define la probabilidad de un evento como el **limite de su frecuencia relativa en un número grande de eventos**
* Esta interpretación suena razonable por ejemplo en un experimento científico llevado a cabo a través de procesos repetibles y por tanto carentes de opinión **subjetiva**
* Esta interpretación es útil en muchos casos, sin embargo en otros no es tan intuitiva (Ej: ¿cuál es la probabilidad de que EPN sea un alienígena?)

Fuente: Wikipedia

---

# 3.3 ¿Podemos hacer estadística con otra interpretación de la probabilidad?

* Esta pregunta ha causado acaloradas discusiones desde hace siglos y durante mucho tiempo todo hiciera Estadística saliéndose de la *noción frecuentista* era duramente criticado
* Sin embargo, en muchos problemas la noción de frecuencia **no es coherente**
* La otra gran corriente de la Estadística se basa en una interpretación diferente de la probabilidad y se conoce como **Estadística Bayesiana**

---

# 4. Estadística Bayesiana

---

# 4.1 Estadística Bayesiana

* La Estadística Bayesiana es la otra gran corriente de la Estadística
* La principal diferencia es que basa su noción de probabilidad como un **estado de información subjetivo** en vez de definirlo como frecuencia relativa
* Se fundamenta en las leyes de la probabilidad y en la teoría de decisión
* Debido a que sus fundamentos descansan en la teoría de la probabilidad provee una estructura coherente a los problemas estadísticos
* La discusión sobre su uso ha sido objeto de *acalorados* debates por **siglos**

---

## Lectura recomendada

*Malakoff, D. (1999). Bayes offers a 'new' way to make sense of numbers. Science, Vol. 286,  pp. 1460-1464.*

---

# 5. Machine Learning

---

# 5.1 Machine Learning (ML)

* Machine Learning pretende dar a las computadoras la habilidad de **aprender** sin ser programadas explícitamente para ello (Arthur Samuel, 1959)
* Específicamente se ocupa de la construcción de **algoritmos** que puedan aprender y hacer predicciones sobre los datos
* Las herramientas empleadas en ML son básicamente herramientas estadísticas

---

# 5.2 Machine Learning vs. Estadística

* Durante los 90, el campo de ML era criticado de ser un *re-branding* de la Estadística, pues su objetivo es básicamente el mismo: hacer inferencias a partir de datos
* A pesar de que las herramientas se traslapan mucho entre un campo y otro la *filosofía* de los dos campos es muy diferente
* Lo anterior se debe a que ML se *incubó* dentro de los departamentos de Ciencias de la Computación de las universidades *lejos* de la rígida estructura intelectual de la comunidad de la Estadística

---

# 5.3 Diferencias entre Machine Learning y Estadística

* El énfasis de ML está en hacer buenas **predicciones** a partir de los datos (Ej: ¿cuál es la probabilidad de que esta imagen sea la de un perro?), por otro lado, la Estadística no hace un énfasis en la predicción, sino en un espectro de problemas más grande
* En general ML trata problemas con **cantidades masivas** de datos, en Estadística los datos suelen ser escasos

---

## Lectura recomendada

*Breiman, L. Statistical Modeling: The Two Cultures. Statistical Science, Vol. 16, No. 3 (Aug., 2001), pp. 199-215*


---

# 6. Data Science

---

# 6.1 Data Science

* Data Science es el *último chico cool en llegar al barrio* del análisis de datos
* Pretende ser un *concepto unificador* de todos los métodos, campos y demás elementos relacionados con el fenómeno de los datos
* Sus principales detractores afirma que solo es un *re-branding* de la Estadística que ya conocemos
* Aún es muy pronto para saber si el término se consolidará o se unirá el club de *buzzwords* olvidadas como *Bussiness Analytics*, *Predictive Analytics*, *Knowledge Discovery in Databases*, entre otras