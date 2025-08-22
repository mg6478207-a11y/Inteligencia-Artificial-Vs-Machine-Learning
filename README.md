# Tipos de Machine Learning

## 1. Machine Learning Supervisado

El **machine learning supervisado** es un tipo de aprendizaje en el que el modelo se entrena con un conjunto de datos **etiquetados** (es decir, se conoce la variable objetivo o de resultado).  

Por ejemplo, si los científicos de datos estuvieran construyendo un modelo para la predicción de tornados, las variables de entrada podrían incluir la fecha, la ubicación, la temperatura, los patrones de flujo del viento y más, y el output sería la actividad real de tornados registrada para esos días.  

###  Algoritmos principales

- **Regresión**  
  Predicen valores numéricos o continuos (ej: temperatura, salario).  
  *Ejemplos:* Regresión lineal, Bosque aleatorio, Gradient Boosting.  

- **Clasificación**  
  Predicen categorías o etiquetas (ej: “basura” / “no basura”).  
  *Ejemplos:* Regresión logística, K-vecinos más próximos, Máquinas de Vectores de Soporte (SVM).  

- **Naïve Bayes**  
  Usados para clasificación en grandes conjuntos de datos.  
  Pertenecen al aprendizaje generativo y modelan la distribución de entrada de cada clase.  
  Relacionados también con *árboles de decisión*, aplicables en regresión y clasificación.  

- **Redes neuronales**  
  Imitan el cerebro humano mediante nodos interconectados.  
  *Aplicaciones:* traducción automática, reconocimiento de imágenes, voz y generación de contenido.  

- **Bosque aleatorio**  
  Conjunto de *árboles de decisión* que combinan sus resultados para predecir valores (regresión) o categorías (clasificación).  



## 2. Machine Learning No Supervisado

Se aplica a conjuntos de datos **no etiquetados** y busca descubrir patrones ocultos, relaciones y estructuras sin necesidad de una variable objetivo.  

Este enfoque facilita el análisis exploratorio de datos, la segmentación de clientes, la detección de anomalías y la reducción de la dimensionalidad.  

Entre sus métodos más comunes se encuentra el **análisis de conglomerados (clustering)**, que organiza los datos en grupos en función de su similitud.  

###  Algoritmos principales
- **K-medias**  
  Divide los datos en *k* grupos según cercanía a centroides.  
  *Usos:* segmentación de mercado, agrupación de documentos, segmentación y compresión de imágenes.  

- **Agrupación jerárquica**  
  - *Aglomerativa*: fusiona progresivamente puntos en clústeres.  
  - *Divisiva*: divide un grupo inicial en subgrupos según diferencias.  

- **Agrupación probabilística**  
  Basada en la probabilidad de pertenencia de un dato a una distribución, como los **modelos de mezclas gaussianas (GMM)**.  

- **Otros métodos**  
  - *PCA (Análisis de Componentes Principales)* → reducción de dimensionalidad.  
  - *Algoritmos de asociación* → identificación de relaciones en grandes bases de datos.  



## 3. Aprendizaje por Refuerzo

El **aprendizaje por refuerzo** es una técnica de inteligencia artificial basada en la **programación dinámica** que entrena a un agente mediante un sistema de recompensas y castigos.  

En este enfoque, el agente interactúa con un entorno realizando acciones para alcanzar un objetivo, recibiendo retroalimentación positiva o negativa en función de una métrica predefinida.  

Este mecanismo incentiva la repetición de conductas correctas y la eliminación de las ineficaces, permitiendo que, con la práctica, el agente aprenda estrategias óptimas de decisión.  

El aprendizaje por refuerzo, en variantes como el **RLHF (Reinforcement Learning with Human Feedback)**, se emplea ampliamente en el desarrollo de **videojuegos** y en la **robótica**, donde se utiliza para enseñar a los robots a reproducir y perfeccionar tareas humanas.  
