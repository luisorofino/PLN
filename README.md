# Detección de Fake News con NLP y Deep Learning

Práctica 4 para la asignatura de **Inteligencia Artificial II**. 
El objetivo de este proyecto es clasificar noticias como *Reales* o *Falsas* utilizando técnicas de Procesamiento del Lenguaje Natural (PLN) y comparando modelos de Machine Learning clásico frente a Deep Learning.

## Autores
* **Daniel Casquero Palencia**
* **Luis Orofino Álvarez**

## Dataset
Debido al tamaño de los archivos, los datasets están disponibles aquí:
* [Dataset Fake.csv (Google Drive)](https://drive.google.com/file/d/1kPuMWKYG-TofjxO-2rUNsEunY4Pzjxfp/view?usp=sharing)
* [Dataset True.csv (Google Drive)](https://drive.google.com/file/d/1WbX9rmNAsUfYK6IMcU3joHCcWs5jZLvY/view?usp=sharing)

## Contenido del Proyecto

El notebook incluye un flujo de trabajo completo de Data Science:

1.  **Preprocesamiento de Texto:**
    * Limpieza de datos (minúsculas, eliminación de puntuación).
    * Eliminación de *Stopwords* (NLTK).
    * Normalización y Tokenización.
2.  **Representación de Datos:**
    * Bolsa de Palabras (Bag of Words).
    * TF-IDF.
    * Word Embeddings (GloVe).
3.  **Modelos Comparados:**
    * **Naive Bayes Multinomial** (Ajuste de *alpha*).
    * **Support Vector Machines (SVM)** (LinearSVC).
    * **k-Nearest Neighbors (kNN)**.
    * **Redes Neuronales (Keras):**
        * Sin embeddings pre-entrenados.
        * Con embeddings congelados (GloVe).
        * Con embeddings sin congelar (Fine-tuning).
      
Para ejecutar este cuaderno necesitas las siguientes librerías:

```bash
pip install -r requirements.txt
