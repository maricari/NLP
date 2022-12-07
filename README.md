# Procesamiento de lenguaje natural (NLP)

5ta Cohorte

Alumna: María Carina Roldán

### EJERCICIOS

#### 1. Word2Vec
![alt text](https://github.com/maricari/NLP/blob/main/img/ch1.jpg)
- **Objetivo**: Realizar una función que reciba un corpus y el índice de un documento y devuelva los documentos ordenados por la similitud coseno.
- **Código**: [1a_word2vec.ipynb](https://github.com/maricari/NLP/blob/main/1a_word2vec.ipynb)
--- 
#### 2. Bot con Spacy utilizando un corpus de la web
![alt text](https://github.com/maricari/NLP/blob/main/img/ch2.jpg)
- **Objetivo**: Tomar un ejemplo de los bots utilizados en clase y construir el propio.

Utilizando vectores TF-IDF y similitud coseno, el sistema intenta encontrar la parte de la página que más se relaciona con el texto de entrada. La idea es que un humano diga una expresión y el bot responda con una reflexión acorde. Por ejemplo:

    humano: por qué estoy trabajando!
    
    bot: La noche se ha hecho para descansar y el día para trabajar

Para el ejercicio se consumieron datos de una [página con refranes alusivos al tiempo](https://www.cervantesvirtual.com/obra-visor/refranes-alusivos-al-tiempo/html/).

- **Código**: [2d_bot_tfidf_spacy_esp.ipynb](https://github.com/maricari/NLP/blob/main/2d_bot_tfidf_spacy_esp.ipynb)
---
#### 3. Custom embedddings con Gensim
![alt text](https://github.com/maricari/NLP/blob/main/img/ch3.jpg)
- **Objetivo**: Crear sus propios vectores con Gensim basado en lo visto en clase pero con otro dataset. Probar términos de interés y explicar similitudes en el espacio de embeddings.

Para el ejercicio se consumieron datos de la misma [página con refranes alusivos al tiempo](https://www.cervantesvirtual.com/obra-visor/refranes-alusivos-al-tiempo/html/) utilizada en el ejercicio 2 y una [página con frases positivas, refranes y dichos](https://www.xuliocs.com/frasespositiv.htm).

- **Código**: [3c_Custom_embedding_con_Gensim_homework.ipynb](https://github.com/maricari/NLP/blob/main/3c_Custom_embedding_con_Gensim_homework.ipynb)
---
#### 4. Predicción de próxima palabra
![alt text](https://github.com/maricari/NLP/blob/main/img/ch4.jpg)
- **Objetivo**: Utilizar un corpus para crear embeddings de palabras basado en ese contexto utilizando la layer Embedding de Keras. Utilizar esos embeddings junto con layers LSTM para la predicción de la próxima palabra.

Para el ejercicio se utilizó el libro [Origen de los indios de América](https://www.gutenberg.org/cache/epub/56219/pg56219-images.html).

- **Código**: [4e_prediccion_palabra_homework.ipynb](https://github.com/maricari/NLP/blob/main/4e_predicci%C3%B3n_palabra_homework.ipynb)
---
#### 5. Sentimental Analysis
![alt text](https://github.com/maricari/NLP/blob/main/img/ch5.jpg)
- **Objetivo**: Utilizar Embeddings + LSTM para clasificar críticas de compradores de ropa. Se deberá balancear el dataset, y probar con y sin embeddings pre-entrenados. El accuracy de validación deberá rondar entre los 0.5 y 0.7.

Para este ejercicio se utilizaron datos de [Women's E-Commerce Clothing Reviews](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews) de Kaggle.

- **Código**: [5_clothing_ecommerce_reviews.ipynb](https://github.com/maricari/NLP/blob/main/5_clothing_ecommerce_reviews.ipynb)
---
#### 6. QA Bot
![alt text](https://github.com/maricari/NLP/blob/main/img/ch6.jpg)
- **Objetivo**: Construir un Bot de preguntas y respuestas utilizando embeddings preentrenados (Fasttext).

Para este ejercicio se utilizaron datos del challenge [ConvAI2](https://convai.io/) (Conversational Intelligence Challenge 2) de conversaciones en inglés.

- **Código**: [6_bot_qa.ipynb](https://github.com/maricari/NLP/blob/main/6_bot_qa.ipynb)
