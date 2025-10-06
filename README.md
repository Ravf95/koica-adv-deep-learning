# Deep Learning

**Autor:** Rodrigo Villalba

**Fecha:** 2025-09-05

Este repositorio contiene implementaciones de diferentes técnicas y modelos de Deep Learning, junto con sus resultados, métricas de evaluación y notebooks en Python para su análisis y experimentación.

## 📘 Notebooks de Python disponibles

Las notebooks estan disponibles en el directorio [projects/notebooks](./projects/notebooks/), la documentación de los casos de uso, objetivos estan disponibles en el archivo [docs/report.md](./docs/report.md).

A continuación se listan los proyectos disponibles con las técnicas y modelos utilizados:

1. DNN Classification: Clasificación entre perros y gatos a partir de imágenes.
1. SAE Autoencoder: Compresión y reconstrucción de dígitos manuscritos.
1. Simple RNN: Predicción de temperaturas.
1. Bidirectional RNN: Análisis de sentimientos de las reseñas hechas en IMDB.
1. Seq2Seq: Traducciónes de textos en ingles al español.
1. Generative AI:  Análisis de sentimientos de imágenes obtenidas usando la webcam.
1. RAG Transcription: Realizar preguntas y respuestas utilizando la transcripción de un video de Youtube.
1. RAG SQL: Generación automática de consultas SQL basadas en preguntas en lenguaje natural.
1. VAEs y GANs: Generación de estructuras de edificios usando como estructuras existentes como entrenamiento.

## 📊 Resultados y métricas

Los resultados obtenidos y las métricas utilizadas para evaluar cada implementación están disponibles en formato CSV en el directorio [results](./results/).

## Estructura del repositorio
```
├── README.md
├── docs
│   └── report.md
├── projects
│   ├── notebooks
│   │   ├── 01_dnn_clasification.ipynb
│   │   ├── 02_sae_autoencoder.ipynb
│   │   ├── 03_simple_rnn.ipynb
│   │   ├── 04_bidirectional_rnn.ipynb
│   │   ├── 05_sec2sec_phrase_translation.ipynb
│   │   ├── 06_generative_ai.ipynb
│   │   ├── 07_rags_youtube_transcription.ipynb
│   │   ├── 08_rags_sql_generator.ipynb
│   └── └── 09_vae_gans.ipynb
└── results
    ├── 01_dnn_clasification_summary.csv
    ├── 02_sae_autoencoder_summary.csv
    ├── 03_simple_rnn_summary.csv
    ├── 04_bidirectional_rnn_summary.csv
    ├── 05_sec2sec_phrase_translation_summary.csv
    ├── 06_generative_ai_summary.csv
    └── 09_vae_gans_summary.cs
```
