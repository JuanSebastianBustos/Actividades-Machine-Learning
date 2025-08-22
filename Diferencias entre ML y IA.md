# Diferencias entre Machine Learning y Inteligencia Artificial

CAD612023642C-A

**Estudiantes:**
Daniela Alejandra Alvarez
Cristian Camilo Naranjo
Andres Felipe Venegas
Juan Sebastián Bustos

Universidad de Cundinamarca 
22 de agostos del 2025 
Chía


# Definiciones: Inteligencia Artificial y Machine Learning

## 1. ¿Qué es la Inteligencia Artificial (IA)?

La **Inteligencia Artificial (IA)** es un campo interdisciplinario de la informática que se enfoca en la creación de máquinas capaces de realizar tareas que normalmente requerirían inteligencia humana. Su objetivo es desarrollar sistemas que puedan razonar, aprender, percibir su entorno, comprender el lenguaje y resolver problemas de forma autónoma.

> "La inteligencia artificial es el campo de la informática que se ocupa de la creación de ordenadores y robots capaces de razonar, aprender y actuar de una forma que normalmente requeriría la inteligencia humana, o que implica una facultad mental que suele asociarse a los seres humanos, como la percepción del lenguaje, la memoria y la capacidad para resolver problemas."
>
> — **Virginie Mathivet**, *Inteligencia Artificial* (2018)

Desde una perspectiva más técnica, la IA no busca replicar la conciencia humana, sino **simular procesos cognitivos** mediante algoritmos, modelos matemáticos y grandes volúmenes de datos.

### Clasificación de la IA

| Tipo                         | Descripción                                                                                                                          |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **IA Estrecha (Narrow AI)** | Capaz de realizar una tarea específica con alto nivel de precisión (ej: asistentes virtuales, vehículos autónomos). Es el único tipo de IA que existe actualmente. |
| **IA General (AGI)** | Hipotética IA que podría superar al ser humano en cualquier tarea intelectual. Aún no se ha desarrollado.                              |
| **Superinteligencia Artificial** | Sistema que superaría ampliamente la inteligencia humana en todos los ámbitos. Es un concepto teórico y objeto de debate ético. |

---

## 2. ¿Qué es el Machine Learning (ML)?

El **Machine Learning (aprendizaje automático)** es una **subárea de la Inteligencia Artificial** que se centra en desarrollar algoritmos que permiten a las máquinas **aprender de los datos sin ser programadas explícitamente**. En lugar de seguir un conjunto de reglas estáticas, los modelos de ML identifican patrones en los datos para hacer predicciones o tomar decisiones.

> "El Machine Learning es el campo de estudio que da a los ordenadores la capacidad de aprender sin ser explícitamente programados."
>
> — **Arthur Samuel**, citado en *Machine Learning con R* por Daniel D. Gutierrez (2016)

Es la tecnología que impulsa sistemas como los motores de recomendación personalizados, la detección de fraudes bancarios o la traducción automática.

### Tipos principales de ML

| Tipo                        | Descripción                                                                     | Ejemplo                                     |
| --------------------------- | ------------------------------------------------------------------------------- | ------------------------------------------- |
| **Aprendizaje supervisado** | El modelo aprende de datos etiquetados (entrada + salida correcta).             | Clasificar correos como spam o no spam.     |
| **Aprendizaje no supervisado** | El modelo descubre patrones en datos sin etiquetas.                             | Agrupar clientes por comportamiento de compra. |
| **Aprendizaje por refuerzo** | El modelo aprende mediante prueba y error, recibiendo recompensas o penalizaciones. | Un agente que aprende a jugar ajedrez.      |

### Diferencia clave entre IA y ML

-   **La IA es el objetivo general**: crear sistemas inteligentes.
-   **El ML es un método**: una de las formas más efectivas de lograr la IA, basada en el aprendizaje a partir de datos.


## Diferencias clave IA vs. ML

### Diferencias Estructurales y Metodológicas

**Alcance y Objetivos**
La diferencia más fundamental reside en el alcance de cada disciplina. Según Goertzel (2014), la IA es un ámbito que tiene como objetivo desarrollar sistemas con inteligencia general artificial, que tengan la capacidad de razonar, planificar y solucionar problemas variados de forma autónoma. En oposición, el ML se enfoca particularmente en la habilidad de aprender automáticamente a partir de los datos y es una herramienta o método dentro del ecosistema más extenso de la IA.

**Enfoques Metodológicos**
Los sistemas de inteligencia artificial se pueden poner en práctica a través de diferentes métodos, como la búsqueda heurística, los sistemas basados en reglas, la lógica formal y las técnicas de aprendizaje automático. El conocimiento explícito codificado por expertos humanos es el fundamento de los enfoques clásicos de IA, como los sistemas expertos (Feigenbaum, 1977). En cambio, el aprenizaje de máquinas se basa solamente en el aprendizaje a partir de los datos, empleando algoritmos matemáticos y estadísticos para identificar patrones y llevar a cabo predicciones.

**Dependencia de Datos**
Una distinción importante es la dependencia de los datos. Los sistemas de ML necesitan, sin excepsión, cantidades significativas de datos para su entrenamiento y para funcionar correctamente (LeCun et al.,2015). Los sistemas de inteligencia artificial convencionales, especialmente los que se fundamentan en conocimiento simbólico, tienen la capacidad de trabajar con conocimiento estructurado sin requerir conjuntos extensos de datos para su entrenamiento.

### Taxonomía de Aplicaciones

**Aplicaciones de Inteligencia Artificial**
Las implementaciones de la Inteligencia Artificial comprenden sistemas de planificación automática, el procesamiento de lenguaje natural fundamentando en reglas, los sistemas de recomendación híbridos, la robótica cognitiva y los asistentes virtuales de alta complejidad. Estos sistemas pueden incorporar diversas técnicas, incluyendo el aprendizaje automático, entre otras (Poole et al., 1998).

**Aplicaciones Específicas de Machine Learning**
El ML se aplica en aplicaciones como la predicción, la clasificación automática, el análisis predictivo, los sistemas de recomendación que se basan en filtrado colaborativo y el procesamiento de imágenes a través de redes neuronales convolucionales (Hastie et al., 2009) donde se presenta específicamente el ML. La dependencia esencial del aprendizaje a partir de datos históricos es lo que distingue a estas aplicaciones.

### Implicaciones Técnica y Consideraciones de Implementación

**Complejidad Computacional**
Los sistemas de IA tienen variaciones notables en sus requerimientos computacionales, según la metodología que se aplique. Los sistemas de ML, sobre todo el aprendizaje profundo, necesitan una gran cantidad de recursos computacionales para el entrenamiento y la inferencia (Goodfellow et al., 2016) en tanto que los sistemas fundamentados en reglas pueden funcionar con recursos limitados.

**Interpretabilidad y Transparencia**
La interpretabilidad es otro aspecto significativo que lo distingue, los sistemas de inteligencia artificial que se basan en la lógica simbólica posibilitan una elevada interpretabilidad, lo cual hace posible seguir el proceso de razonamiento. Los sistemas de ML, sobre todo los modelos complejos como las redes neuronales profundas, tienen propiedades de "caja negra" que restringen la posibilidad de interpretar sus decisiones (Ribeiro et al., 2016).


## **Tipos de Machine Learning**

Las maneras de implementar el ML se clasifican principalmente en tres categorías, determinados por la forma de los datos y la retroalimentación que reciben, estas son: Aprendizaje Supervisado, Aprendizaje No Supervisado y Aprendizaje por Refuerzo.

### **Aprendizaje Supervisado**

El aprendizaje supervisado es un enfoque en el cual se entrena un modelo utilizando un conjunto de datos que ya han sido etiquetados u organizados de manera estructurada, es decir que, para cada entrada de datos, ya hay una variable de salida correspondiente. Estos algoritmos aprenden al recibir ejemplos emparejados donde se conocen los datos de entrada y las salidas correctas.
La idea clave detrás del aprendizaje supervisado es que el modelo aprende a mapear con precisión los datos de entrada y su salida correspondiente basándose en los ejemplos dados en la fase de entrenamiento, una vez entrenado, la idea es que sea capaz de predecir con gran precisión las etiquetas o resultados correctos para datos nuevos y desconocidos. Por ejemplo, si se quiere entrenar un algoritmo para reconocer imágenes de perros, se le proporcionarían imágenes que ya han sido etiquetadas explícitamente como «perros», para que, durante el entrenamiento, el modelo compara sus propias predicciones con las respuestas correctas para evaluar su precisión y después ajusta sus parámetros internos para mejorar su capacidad de reconocer los patrones detrás de estas imágenes.
El hecho de tener de antemano los datos etiquetados con alta precisión es la razón principal por la que el aprendizaje supervisado puede alcanzar niveles tan altos de precisión. Sin embargo, si las etiquetas son inexactas o insuficientes, el modelo carece de una verdad sólida con la que aprender y validar sus predicciones, lo que limita su rendimiento. Esto pone de relieve que invertir en la anotación y la curación de datos es un requisito previo fundamental para el éxito de cualquier proyecto que utilice el aprendizaje supervisado.

Los algoritmos de aprendizaje supervisado se utilizan para resolver: la clasificación, que implica predecir una variable de salida categórica (si/no), junto con la regresión, que predice un valor continuo o numérico (temperatura, dinero). Algunos de los algoritmos del aprendizaje supervisado son:

| Algoritmo | Tipo de Tarea Principal | Descripción Breve |
| :---- | :---- | :---- |
| Regresión Lineal | Regresión | Identifica relaciones lineales para predecir valores continuos.6 |
| Regresión Polinómica | Regresión | Identifica relaciones no lineales (polinómicas) para predecir valores continuos.6 |
| K-Vecinos Más Cercanos (KNN) | Clasificación | Clasifica un punto de datos según la clase mayoritaria de sus 'k' vecinos más cercanos.6 |
| Naive Bayes | Clasificación | Clasificador probabilístico para grandes conjuntos de datos, basado en el teorema de Bayes.6 |
| Árboles de Decisión | Clasificación, Regresión | Divide los datos en ramas basadas en decisiones para predecir categorías o valores.6 |
| Máquinas de Vectores de Soporte (SVM) | Clasificación, Regresión | Encuentra el hiperplano óptimo para separar clases o ajustar datos.16 |
| Bosques Aleatorios (Random Forest) | Clasificación, Regresión | Combina múltiples árboles de decisión para mejorar la precisión.2 |
| Redes Neuronales | Clasificación, Regresión | Simulan el cerebro humano para reconocer patrones complejos (imágenes, voz, texto).2 |

El aprendizaje supervisado es uno de los más utilizados en la práctica, por su precisión en tareas bien definidas, entre sus usos están:

* **Detección de Fraude**: donde se revisan muchos datos transaccionales y el modelo se entrena etiquetando transacciones pasadas como “fraudulentas” y “genuinas” para predecir futuras transacciones.
* **Reconocimiento de Imágenes y Voz**: este apartado es bastante conocido como en el reconocimiento facial, identificación de objetos o asistentes de voz. Se entrenan con miles de imágenes o audios y el sistema aprende a reconocer características clave.
* **Análisis Predictivo**: se utilizan en el campo meteorológico para predecir valores continuos, como el clima. También, son utilizadas en el campo financiero, para predecir el abandono de clientes, entrenando el algoritmo con datos de estos y se puedan tomar mejores decisiones.
* **Ejemplos Concretos**: Google Lens, Twitter (X) / Meta (con sus algoritmos), Tesla Autopilot.

### **Aprendizaje No Supervisado**
El aprendizaje no supervisado es un paradigma de ML caracterizado por trabajar con datos sin etiquetar. A diferencia del aprendizaje supervisado, el algoritmo no recibe instrucciones previas sobre el resultado esperado, este busca descubrir patrones ocultos, estructuras subyacentes o relaciones inherentes dentro de los datos por sí mismo, sin intervención humana directa.
Este aprendizaje se basa en la capacidad del algoritmo para analizar los datos de entrada y encontrar similitudes, agrupando elementos que comparten características comunes o extrayendo patrones significativos. Por ejemplo, si se le proporciona un conjunto de imágenes de perros y gatos sin etiquetarlos, este algoritmo trabajará de forma autónoma para agrupar las imágenes que corresponden a un perro y un gato, esto basándose únicamente en las características visuales que detecta. La principal ventaja es no requerir datos etiquetados, lo que ahorra tiempo y costes asociados al hecho de asignar etiquetas, aunque se ve limitada por: la dificultad en la precisión de los resultados, ya que, no se le da esa verdad fundamental para la evaluación, a su vez, la validación de los modelos no supervisados a menudo requiere métodos cualitativos o métricas intrínsecas que evalúen la coherencia y la interpretabilidad de los patrones descubiertos en los datos.
El aprendizaje no supervisado es eficaz para el modelo descriptivo y en la identificación de patrones en datos complejos, centrándose en la agrupación, asociación y reducción de dimensionalidad. Algunos de los mas utilizados son:
| Algoritmo | Tipo de Tarea Principal | Descripción Breve |
| :---- | :---- | :---- |
| K-means Clustering | Clustering | Agrupa puntos de datos en 'K' clústeres basados en la proximidad a un centroide.4 |
| Hierarchical Clustering | Clustering | Crea una jerarquía de clústeres mediante fusión (aglomerativa) o división (divisiva).4 |
| Modelos de Mezcla Gaussiana (GMM) | Clustering Probabilístico | Agrupa puntos de datos basándose en la probabilidad de pertenecer a distribuciones gaussianas.19 |
| Análisis de Componentes Principales (PCA) | Reducción de Dimensionalidad | Transforma datos a un espacio de menor dimensión, preservando la varianza.16 |
| Descomposición en Valores Singulares (SVD) | Reducción de Dimensionalidad | Descompone matrices para identificar patrones y reducir dimensiones.16 |
| Independent Component Analysis (ICA) | Reducción de Dimensionalidad | Separa una señal multivariada en componentes aditivos subyacentes no gaussianos e independientes.16 |
| Apriori | Asociación | Descubre reglas de asociación entre elementos en grandes conjuntos de datos.19 |

A pesar de que el aprendizaje no supervisado no tiene la misma precisión, es indispensable para reconocer patrones y generar conocimiento a partir de datos no etiquetados. Algunos de sus usos son:
* **Segmentación de clientes**: donde se agrupan clientes con características similares, permitiendo una atención más personalizada y efectiva
* **Agrupación de Documentos**: este enfoque permite organizar grandes volúmenes de documentos y clasificarlos en categorías lógicas basándose en su semántica, facilitando la búsqueda de información.
* **Sistemas de Recomendación**: utilizados en plataformas de comercio electrónico o servidores de streaming, se basan en este tipo de aprendizaje para buscar similitudes entre usuarios y productos, sugiriendo elementos relevantes.
* **Visualizacion de Big Data**: aquí se utiliza la reducción de dimensionalidad y la agrupacion, para visualizar grandes volúmenes de información, permitiendo analizar tendencias y relaciones ocultas.
* **Ejemplos Concretos**: Spotify's "Discover Weekly", Google News.

### **Aprendizaje Por Refuerzo**

El aprendizaje por refuerzo es otro enfoque del ML que es parecido a “aprender haciendo” a través de prueba y error. Esta dentro del ámbito de la programación dinámica y entrena algoritmos utilizando un sistema de recompensas y castigos.
En este, un agente interactúa con cierto entorno, realizando acciones con el objetivo de alcanzar una meta predeterminada. Las acciones del agente se evalúan y este recibe una recompensa si la acción es beneficiosa o un castigo si es perjudicial, basándose en una métrica establecida. A través de la repetición de estas interacciones, el agente aprende progresivamente las estrategias óptimas para maximizar la recompensa acumulada, en el entorno, el agente tendrá que decidir entre explorar nuevas acciones para descubrir recompensas mayores o aprovechar acciones conocidas que ya han demostrado generar grandes recompensas. Una diferencia fundamental con respecto a los otros paradigmas es que el agente no recibe instrucciones sobre lo que debe realizar, sino que descubre por sí mismo las mejores acciones mediante la interacción dinámica con su entorno, al tener la capacidad de autoaprendizaje en entornos interactivos le da una ventaja distintiva sobre otros paradigmas para tareas de control, planificación y toma de decisiones secuenciales.
A pesar de no tener algoritmos asociados específicos se le puede asignar principalmente al Deep RL, junto con estos algoritmos derivados a este tipo de enfoque, siendo:

| Algoritmo/Tipo | Descripción Breve |
| :---- | :---- |
| Deep Reinforcement Learning (Deep RL) | Combina redes neuronales profundas con aprendizaje por refuerzo para manejar entornos complejos y datos de alta dimensión.28 |
| Optimización de Políticas de Región de Confianza (TRPO) | Un algoritmo de Deep RL que optimiza políticas de manera iterativa con garantías de mejora.28 |
| OpenAI Gym (Toolkit) | Un kit de herramientas de código abierto que proporciona entornos para desarrollar y probar algoritmos de RL.29 |
| Q-learning o Redes Q Profundas (DQN)| Algoritmo de aprendizaje sin modelo que permite que un modelo de este enfoque aprenda sin conocimiento previo ni política (se le puede integrar DeepRL) |
| SARSA (Estado, Acción, Recompensa, Estado, Acción) | Algoritmo sin modelos como Q-learning, pero aprendizaje en función de las acciones que realmente realiza. |
| REINFORCE| Algoritmo de gradiente de política, busca identificar la política optima mientras manipula su entorno. |

El aprendizaje por refuerzo es potente en entornos de toma de decisiones secuencial e interacción dinámica, logrando resultados que superan las capacidades humanas algunos de sus aplicaciones son:
* **Videojuegos y Juegos de Mesa**: este enfoque ha alcanzado logros impresionantes en este ámbito como deepmind AlphaGo que aprendió a jugar al go, imitando movimientos humanos y luego jugando contra sí mismo donde llego al punto de derrotar a los mejores jugadores humanos.

* **Robótica y Vehículos Autónomos**: utilizado para el desarrollo de sistemas autónomos, para los vehículos se le penaliza al modelo cuando toma una mala decisión, aprendiendo a no volver a repetir esto, también se utiliza para enseñar a robots en tareas humanas o movimientos complejos.
* **Optimización de Procesos**:  se utilizó en la compresión de video para mantener calidad visual y reducir datos, siendo crucial para servicios de streaming, también en la eficiencia energética donde se plantea para optimizar la eficiencia energética, reduciendo costos a largo plazo.
* **Ejemplos Concretos**: DeepMind's AlphaGo y AlphaStar, OpenAI's Dactyl (brazo robótico que aprendió a resolver un cubo de Rubik).

### **Aprendizaje Semi-Supervisado**
Este tipo de aprendizaje no se pidió en la actividad sin embargo ha tenido impacto en la actualidad con modelos como GPT
El aprendizaje semi-supervisado es un tipo de aprendizaje automático que combina una pequeña cantidad de datos etiquetados con una gran cantidad de datos no etiquetados. Es especialmente útil cuando obtener datos etiquetados es costoso o laborioso, pero se dispone de abundantes datos sin etiquetar.  Se basan en supuestos como la hipótesis de continuidad, agrupamiento y variedad. Algunos algoritmos utilizados son:
| Categorial | Algoritmo | Descripción Breve |
| :---- | :---- | :---- |
| Métodos Wrapper| Autoentrenamiento (Self-Training) | Un clasificador base (que debe poder predecir probabilidades) se entrena primero con los datos etiquetados. Luego, etiqueta los datos no etiquetados en los que tiene mayor confianza. Estas pseudoetiquetas de alta confianza se añaden al conjunto de entrenamiento y el proceso se repite iterativamente|
| Métodos Wrapper| Coentrenamiento (Co-Training) | Se utilizan dos o más clasificadores diferentes, cada uno entrenado con una conjunto de características distinto del mismo dato. Cada clasificador etiqueta los datos no etiquetados para los que es más confidente y luego alimenta con esas nuevas etiquetas al otro clasificador, enriqueciendo mutuamente el aprendizaje|


# **CONCLUSIÓN Y SINTESIS**
## A.Definiciones: Inteligencia Artificial y Machine Learning
 **SINTESIS**
+ la inteligencia artificial (IA) es el campo de la informatica que busca desarrollar maquinas capaces de realizar tareas que requieren inteligencia humana, como razonar,aprender, percibir el entorno y resolver problemas. La IA se clasifica en tres niveles:
+ IA Estrecha(Narrow AI):se enfoca en tareas especificas (ej.asistentes virtuales).
+ IA General(AGI): hipotetica,capaz de igualar o superar al ser humano en cualquier actividad intelectual.
+ Superinteligencia: un concepto teórico que superaría ampliamente la inteligencia humana.
  
Dentro de la IA se encuentra el **Machine Lerning (ML)**, que es una subárea dedicada a crea algoritmos capaces de aprender de los datos sin ser programados explicitamente.El ML se basa en identificar patrones y hacer predicciones o tomar decisiones a partir de grandes volumenes de información.
 Existen tres enfoques principales:
  +  Aprendizaje suoervisado: aprende de datos etiquetados(ej. deteccion de spam).
  +  Aprendizaje no supervisado: encuentra patrones en datos sin etiquetas(ej. segmentacion de clientes).
  +  Aprendizaje por refuerzo: aprende por prueba y error mediante recompensas o castigos(ej. un agente que  aprende a jugar ajedrez).
la diferencia fundamental es que:
+ La IA es el objetivo general: construir sistemas inteligentes.
+ El ML es un metodo: lograr IA a traves del aprendizaje con datos.

  **CONCLUSIÓN**
 +  La IA y el ML son dos áreas estrechamente relacionadas pero con alcances diferentes: la IA busca la creación de sistemas inteligentes en un sentido amplio, mientras que el ML es una de las herramientas más poderosas para lograrlo, basada en el aprendizaje a partir de datos. Gracias a estas tecnologías hoy existen avances como asistentes virtuales, traducción automática, vehículos autónomos y sistemas de recomendación, que muestran cómo la combinación de IA y ML está transformando la vida cotidiana y los procesos en múltiples industrias.
   
## B. Diferencias clave IA vs. ML

**SINTESIS**
+ La Inteligencia Artificial (IA) y el Aprendizaje Automatico(ML) difieren principalmente en su alcance, metodologia y dependencia de datos. La IA busca desarrollar sistemas inteligentes capaces de razonar, planificar y resolver problemas, utilizando enfoques como la logica formal, la busqueda heuristica o los sistemas expertos. En cambio, el ML es una rama de la IA enfocada en el aprender automaticamente a partir de datos, aplicando algoritmos estadisticos y matematicos.

  mientras la IA puede trabajar con conocimiento estructurado sin necesidad de grandes volumenes de datos,el ML requiere conjuntos masivos de informacion para entrenarse y funcionar. En cuanto a aplicaciones, la IA abarca sistemas complejos como robotica ccognitiva o asistentes virtuales, mientras que el ML se especializa en tareas predictivas, clasificacion y reconocimiento de patrones. Finalmente, la IA simbolica pfrece mayor interpretabilidad, mientras que los modelos avanzados de ML, como el deep learning, presentan retos por su naturaleza de "caja negra" yelevada demanda computacional.
  
   **CONCLUSIÓN**
  + La relacion entre IA y ML no es de oposicion, sino de complementariedad: la IA represenya el marco general para construir sistemas inteligentes, mientras que el ML es una de sus tecnicas mas potentes,centrada en el aprovechamiento de datos.Las diferencias merodologicas, de aplicaciones y de recursos computacionales reflejan que cada enfoque tiene fortalezas y limitaciones segun el contexto en que se implemente.comprender estas distinciones permimte aprovechar las ventajas de ambos, ya sea buscando la transparencia y explicabilidad de la IA simboloca o la capacidad predictiva y de adaptacion dell ML, lo que resulta esencial para el desarrollo de soluciones tecnologicas eficientes y responsables.

## C. Tipos de ML (supervisado, no supervisado, por refuerzo)

**SINTESIS**

El aprendizaje supervisado se centra en el uso de datos etiquetados para entrenar modelos capaces de clasificar o predecir resultados con alta precisión. Su madurez lo hace esencial en áreas como la detección de fraude, el reconocimiento de imágenes o los sistemas de recomendación, aunque depende fuertemente de la calidad y disponibilidad de datos anotados.
El aprendizaje no supervisado, en contraste, analiza datos sin etiquetar para descubrir patrones ocultos y estructuras subyacentes. Aunque su precisión es difícil de medir, resulta clave en la segmentación de clientes, la detección de anomalías y la reducción de dimensionalidad, especialmente en el contexto del Big Data.
Por último, el aprendizaje por refuerzo (RL) se orienta a la toma de decisiones secuenciales en entornos cambiantes, donde un agente aprende mediante prueba y error con recompensas y castigos. Sus aplicaciones destacan en robótica, videojuegos y conducción autónoma, demostrando su utilidad en problemas donde la interacción continua es esencial.

  **CONCLUSIÓN**
  
Los tres enfoques de Machine Learning representan diferentes formas de aprender de los datos y del entorno, cada uno con fortalezas específicas: el supervisado ofrece precisión y fiabilidad en tareas predictivas, el no supervisado potencia el descubrimiento de información desconocida en grandes volúmenes de datos, y el refuerzo abre el camino a sistemas autónomos capaces de adaptarse y optimizar su comportamiento en situaciones dinámicas. Comprender estas modalidades permite seleccionar el tipo de aprendizaje adecuado según el contexto, equilibrando precisión, exploración de patrones y toma de decisiones autónomas.

De esta manera, el ML se consolida como un campo versátil que no solo sustenta el avance de la Inteligencia Artificial, sino que también impulsa aplicaciones prácticas en sectores como la salud, las finanzas, la industria y el transporte, convirtiéndose en un pilar tecnológico para el futuro.


# Referencias
- **Gutierrez, D. D. (2016).** *Machine Learning con R: Desarrollo de modelos predictivos inteligentes*. Ediciones B - B de Books.
- **Macías Moles, Y. (2021).** *La tecnología y la Inteligencia Artificial en el sistema educativo*. Máster en Profesor/a de ESO y Bachiller, FP y Enseñanza de Idiomas.
- **Mathivet, V. (2018).** *Inteligencia Artificial*. Ediciones ENI.
- Goertzel, B. (2014). Artificial general intelligence: Concept, state of the art, and future prospects. Journal of Artificial General Intelligence, 5(1), 1-48.
- Feigenbaum, E. A. (1977). The art of artificial intelligence: Themes and case studies of knowledge engineering. Proceedings of the 5th International Joint Conference on Artificial Intelligence, 1014-1029.
- LeCun, Y., Bengio, Y., & Hinton, G. (2015). Deep learning. Nature, 521(7553), 436-444.
- Poole, D., Mackworth, A., & Goebel, R. (1998). Computational intelligence: A logical approach. Oxford University Press.
- Hastie, T., Tibshirani, R., & Friedman, J. (2009). The elements of statistical learning: Data mining, inference, and prediction (2nd ed.). Springer.
- Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT Press.
- Ribeiro, M. T., Singh, S., & Guestrin, C. (2016). "Why should I trust you?" Explaining the predictions of any classifier. Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 1135-1144.
- BitBoss. (2023, 25 de febrero). _MACHINE LEARNING /Aprendizaje Supervisado, No Supervisado y Por Refuerzo_ [Video]. YouTube. https://www.youtube.com/watch?v=FMkxSsfvMI4
- Bergmann, D. (2023, 12 de diciembre). _¿Qué es el aprendizaje semisupervisado?_ IBM. https://www.ibm.com/es-es/think/topics/semi-supervised-learning
- Coursera Staff. (2025, 25 de abril). _Reinforcement Learning Algorithms and Use Cases_. Coursera. https://www.coursera.org/articles/reinforcement-learning-algorithms
- Google AI. (2025, 21 de agosto). _Investigación sobre Tipos de Machine Learning: Una Exploración Detallada de los Paradigmas Supervisado, No Supervisado y por Refuerzo_. Modelo de lenguaje grande. Documento en rama del repositorio

