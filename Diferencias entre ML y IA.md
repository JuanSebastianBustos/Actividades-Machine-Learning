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

## **Referencias**

BitBoss. (2023, 25 de febrero). _MACHINE LEARNING /Aprendizaje Supervisado, No Supervisado y Por Refuerzo_ [Video]. YouTube. https://www.youtube.com/watch?v=FMkxSsfvMI4
Bergmann, D. (2023, 12 de diciembre). _¿Qué es el aprendizaje semisupervisado?_ IBM. https://www.ibm.com/es-es/think/topics/semi-supervised-learning
Coursera Staff. (2025, 25 de abril). _Reinforcement Learning Algorithms and Use Cases_. Coursera. https://www.coursera.org/articles/reinforcement-learning-algorithms
Google AI. (2025, 21 de agosto). _Investigación sobre Tipos de Machine Learning: Una Exploración Detallada de los Paradigmas Supervisado, No Supervisado y por Refuerzo_. Modelo de lenguaje grande. Documento en rama del repositorio
