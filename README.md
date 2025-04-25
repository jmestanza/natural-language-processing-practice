# 🌐 Procesamiento de Lenguaje Natural (NLP) - CEIA FIUBA

Este repositorio contiene el material de clases y desafíos prácticos del curso de **Procesamiento de Lenguaje Natural (NLP)** dictado en el CEIA de la FIUBA. Incluye resúmenes teóricos, notebooks interactivos y datasets utilizados en las actividades.

## 📚 Contenido

### 🏫 Clases

1. **Clase 1**: Introducción al PLN y Vectorización de Texto  
   ✏️ Introducción al procesamiento de lenguaje natural, conceptos básicos y técnicas de vectorización de texto como Bag of Words (BoW) y TF-IDF.

2. **Clase 2**: Word Embeddings y Representaciones Semánticas  
   🧠 Representaciones vectoriales de palabras mediante embeddings, introducción a Word2Vec y su aplicación en tareas de PLN.

3. **Clase 3**: RNN, LSTM, GRU y Modelos de Lenguaje  
   🔄 Introducción a redes neuronales recurrentes (RNN), LSTM y GRU. Aplicación en el entrenamiento de modelos de lenguaje.

4. **Clase 4**: RNNs, LSTM, Perplejidad y Generación de Texto  
   📝 Uso de RNNs y LSTM para generación de texto, cálculo de perplejidad y evaluación de modelos de lenguaje.

5. **Clase 5**: Representación y Clasificación de Texto con Redes Neuronales  
   🕵️ Técnicas avanzadas de representación de texto y clasificación utilizando redes neuronales profundas.

6. **Clase 6**: Arquitectura Encoder–Decoder y Secuencia a Secuencia  
   🔗 Introducción a la arquitectura Encoder-Decoder y su aplicación en tareas de secuencia a secuencia como traducción automática.

7. **Clase 7**: Modelos de Atención y Transformers  
   ⚡ Introducción a los modelos de atención y su evolución hacia los Transformers. Aplicaciones en tareas como traducción automática y generación de texto.

---

### 🚀 Desafíos

Los desafíos prácticos están organizados en carpetas y contienen notebooks interactivos que implementan técnicas y modelos de PLN.

1. **Desafío 1**: Vectorización de documentos y análisis de similitud

   - **Conceptos trabajados**:
     - 📄 Representación de texto mediante técnicas como Bag of Words (BoW) y TF-IDF.
     - 📊 Cálculo de similitud entre documentos utilizando métricas como el coseno.
   - **Notebook**: En este notebook se implementaron técnicas de vectorización para representar documentos como vectores numéricos. Además, se calculó la similitud entre documentos para identificar cuáles son más parecidos entre sí.

2. **Desafío 2**: Creación de embeddings con Gensim y pruebas de analogías

   - **Conceptos trabajados**:
     - 🧩 Entrenamiento de modelos Word2Vec para generar embeddings de palabras.
     - 🔍 Evaluación de embeddings mediante pruebas de analogías (e.g., "Rey - Hombre + Mujer = Reina").
   - **Notebook**: En este notebook se entrenaron modelos Word2Vec utilizando Gensim para generar representaciones vectoriales de palabras. También se realizaron pruebas de analogías para evaluar la calidad de los embeddings generados.

3. **Desafío 3**: Entrenamiento de modelos de lenguaje con RNN, LSTM y GRU

   - **Conceptos trabajados**:
     - 🔄 Implementación de modelos secuenciales como RNN, LSTM y GRU.
     - 📈 Entrenamiento de modelos de lenguaje para predecir la siguiente palabra en una secuencia.
   - **Notebook**: En este notebook se implementaron modelos de redes neuronales recurrentes (RNN, LSTM y GRU) para entrenar un modelo de lenguaje. Se evaluó el desempeño del modelo en la predicción de palabras en secuencias de texto.

4. **Desafío 4**: Construcción de un bot de preguntas y respuestas (QA) con LSTM
   - **Conceptos trabajados**:
     - 🤖 Uso de LSTM para construir un modelo de preguntas y respuestas.
     - 📚 Entrenamiento con datasets de preguntas y respuestas para generar respuestas automáticas.
   - **Notebook**: En este notebook se desarrolló un modelo basado en LSTM para responder preguntas. Se utilizó un dataset de preguntas y respuestas para entrenar el modelo y evaluar su capacidad de generar respuestas coherentes.

---

## 🎓 Créditos

- **Autor**: Mestanza Joaquín
- **Curso**: CEIA - FIUBA
- **Profesores**: [Lista de profesores](clases/procesamiento_lenguaje_natural/README.md)

---
