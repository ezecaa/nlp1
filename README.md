# Proyectos para la materia Procesamiento de Lenguaje Natural I (NLP) - Curso de Especialización en Inteligencia Artificial - FIUBA

![Banner del Curso NLP](https://github.com/ezecaa/nlp1/blob/main/portrait.png)

Este repositorio es un portfolio que recopila los proyectos y desafíos que desarrollé como parte de mi curso de **Procesamiento de Lenguaje Natural I**. Aquí se reflejan las habilidades y conocimientos adquiridos en el diseño, implementación y evaluación de modelos de lenguaje, sistemas de traducción automática, bots conversacionales y otras aplicaciones de NLP utilizando diversas técnicas.

Cada proyecto aborda un problema específico de NLP, desde la preparación de datos hasta la implementación y evaluación de modelos.

---

## Trabajos Prácticos del Curso

A continuación, se presenta una breve descripción de cada uno de los desafíos o trabajos prácticos realizados, con enlaces directos a los notebooks correspondientes para su exploración detallada.

---

### **Trabajo Práctico 1: Clasificación de Texto y Similitud (TP1.ipynb)**

**Descripción:**
En este trabajo práctico inicial, se exploraron los fundamentos del preprocesamiento de texto y la aplicación de modelos clásicos de Machine Learning para tareas de NLP. Se trabajó con algoritmos de clasificación como **Naive Bayes Multinomial y ComplementNB** para clasificar documentos. Además, se investigó la **similitud de documentos y palabras**, sentando las bases para la representación vectorial del texto.

**Tecnologías Clave:**
* Python
* Scikit-learn (para clasificación y herramientas de ML)
* Numpy (para manipulación de datos)
* Conceptos de preprocesamiento de texto y vectorización

**Notebook:** [TrabajoPractico1/TP1.ipynb](TrabajoPractico1/TP1.ipynb)
* Abrir en Google Colab: [TP1.ipynb](https://colab.research.google.com/github/ezecaa/nlp1/blob/main/TrabajoPractico1/TP1.ipynb)

---

### **Trabajo Práctico 2: Custom Embeddings con Gensim (TP2.ipynb)**

**Descripción:**
Este trabajo práctico se centró en la creación y análisis de **embeddings de palabras personalizados** utilizando la librería **Gensim**. Se entrenaron vectores de palabras sobre un dataset específico (la obra "Hamlet" de William Shakespeare), y se exploró el espacio de embeddings para identificar y explicar **similitudes y diferencias entre palabras**. Se realizaron visualizaciones para comprender mejor las relaciones semánticas capturadas por los vectores.

**Tecnologías Clave:**
* Python
* Gensim (para Word2Vec u otros embeddings)
* Análisis de similitud de vectores
* Visualización de embeddings

**Notebook:** [TrabajoPractico2/TP2.ipynb](TrabajoPractico2/TP2.ipynb)
* Abrir en Google Colab: [TP2.ipynb](https://colab.research.google.com/github/ezecaa/nlp1/blob/main/TrabajoPractico2/TP2.ipynb)

---

### **Trabajo Práctico 3: Modelo de Lenguaje con Tokenización por Caracteres (TP3.ipynb)**

**Descripción:**
En este desafío, se implementó un modelo de lenguaje a nivel de caracteres utilizando Redes Neuronales Recurrentes (RNNs), específicamente unidades LSTM. El objetivo principal fue aprender la distribución de probabilidad de secuencias de caracteres para poder generar texto coherente. Se exploraron conceptos fundamentales como la tokenización a nivel de carácter, la estructuración de datasets para modelos de lenguaje, y la importancia de métricas como la perplejidad. Se trabajó en la optimización del entrenamiento y se experimentó con estrategias de generación de texto como *greedy search* y *beam search*, analizando el impacto de la temperatura en la diversidad de las salidas generadas.

**Tecnologías Clave:**
* TensorFlow / Keras
* LSTMs (Long Short-Term Memory) - GRU
* Tokenización por caracteres
* Perplejidad (Perplexity)
* Greedy Search, Beam Search, Sampling con Temperatura

**Notebook:** [TrabajoPractico3/TP3.ipynb](TrabajoPractico3/TP3.ipynb)
* Abrir en Google Colab: [TP3.ipynb](https://colab.research.google.com/github/ezecaa/nlp1/blob/main/TrabajoPractico3/TP3.ipynb)

---

### **Trabajo Práctico 4a: Traductor Automático Seq2Seq con LSTM (TP4a.ipynb)**

**Descripción:**
Este proyecto se centró en la creación de un sistema de **traducción automática neuronal (NMT)** utilizando la arquitectura **Encoder-Decoder con LSTMs**. El modelo fue entrenado para traducir frases entre diferentes idiomas (basado en datos de Anki). Se implementó un Encoder para codificar la frase de entrada en un vector de contexto y un Decoder para generar la frase traducida, abordando el preprocesamiento de datos específico para NMT y la inferencia paso a paso.

**Tecnologías Clave:**
* TensorFlow / Keras
* Arquitectura Encoder-Decoder
* LSTMs (Long Short-Term Memory)
* Preprocesamiento de datos para NMT
* Inferencia de modelos Seq2Seq

**Notebook:** [TrabajoPractico4/TP4a.ipynb](TrabajoPractico4/TP4a.ipynb)
* Abrir en Google Colab: [TP4a.ipynb](https://colab.research.google.com/github/ezecaa/nlp1/blob/main/TrabajoPractico4/TP4a.ipynb)

---

### **Trabajo Práctico 4b: Bot Conversacional (Question-Answering) con LSTM y FastText (TP4b.ipynb)**

**Descripción:**
El objetivo de este desafío fue desarrollar un **bot conversacional de Preguntas y Respuestas (QA)** utilizando el dataset ConvAI2. Se aplicaron técnicas de procesamiento de lenguaje natural y se construyó un modelo basado en redes recurrentes, integrando **embeddings FastText** para la representación de palabras. Se exploraron los resultados del modelo en la generación de respuestas y se discutieron observaciones importantes como el **overfitting** y la necesidad de optimización de parámetros y recursos.

**Tecnologías Clave:**
* TensorFlow / Keras
* Modelos de Seq2Seq (aplicado a QA)
* Embeddings FastText
* Preprocesamiento de datos para QA
* Manejo de diálogos y generación de respuestas

**Notebook:** [TrabajoPractico4/TP4b.ipynb](TrabajoPractico4/TP4b.ipynb)
* Abrir en Google Colab: [TP4b.ipynb](https://colab.research.google.com/github/ezecaa/nlp1/blob/main/TrabajoPractico4/TP4b.ipynb)

---

## 🔑 Cómo Ver los Notebooks en Colab

Si deseas ejecutar o interactuar con los notebooks directamente en Google Colab, puedes hacer clic en los enlaces "Abrir en Google Colab" proporcionados para cada trabajo práctico. Asegúrate de tener una cuenta de Google activa para acceder.

---

## 🛠️ Configuración del Entorno

Los proyectos fueron desarrollados en un entorno de Google Colab, utilizando librerías populares de Python para Machine Learning y Procesamiento de Lenguaje Natural.

**Requisitos Generales:**
* Python 3.x
* TensorFlow / Keras
* Numpy
* Pandas
* Gensim (para embeddings)
* Otras librerías específicas según el TP (ej. NLTK, spaCy, Tqdm, Matplotlib, Seaborn)

Las dependencias exactas se listan en las primeras celdas de cada notebook.

---

## 🤝 Contribuciones y Contacto

Este repositorio es una muestra de mi aprendizaje y desarrollo en el campo del NLP. Estoy abierto a nuevas ideas y colaboraciones.

**Contacto:**
* GitHub: [ezecaa](https://github.com/ezecaa)

---

**¡Gracias por visitar mi portfolio!**
