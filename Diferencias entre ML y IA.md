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