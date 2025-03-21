# 3_deeplearning
📈 Análisis de Sentimientos en Twitter sobre las Elecciones EE.UU. 2025



Este proyecto aplica Procesamiento de Lenguaje Natural (NLP) y Deep Learning para analizar el sentimiento de miles de tweets en español relacionados con las elecciones presidenciales de Estados Unidos en 2025, con foco en figuras como Elon Musk y Donald Trump.

🧰 Dataset

Tweets recolectados sobre el contexto de la toma de posesión presidencial.

Total de registros: 465,769

Tweets en español filtrados: 32,477

🛠️ Proceso ETL

Eliminación de columnas irrelevantes y vacías

Filtrado por idioma (solo es)

Limpieza textual: stopwords, URLs, menciones, puntuación, palabras vacías

Normalización y transformación para preparación del modelo

🧐 NLP Exploratorio

Clasificación de sentimiento con VADER y TextBlob

Visualización con:

Nubes de palabras por sentimiento

Gráficos de barras por frecuencia

🧬 Deep Learning

Modelo de red neuronal simple entrenado con Keras:

Embedding → GlobalAveragePooling → Dense → Softmax

Accuracy alcanzado: 71%

Mejora aplicada: Dropout (0.5) para evitar overfitting

🌐 Métricas del modelo con Dropout

Clase

Precisión

Recall

F1-score

Negativo

0.74

0.51

0.60

Neutral

0.70

0.93

0.80

Positivo

0.77

0.21

0.33

Accuracy global: 71%

Macro avg F1: 0.58

📊 Visualizaciones destacadas

Matriz de confusión

Curvas de entrenamiento (accuracy y loss)

Nubes de palabras por clase

🚀 Conclusiones

La clase Neutral fue la más sencilla de predecir

La clase Positiva fue la más difícil por baja representación

La mejora con Dropout ayudó a estabilizar el rendimiento

💼 Autor

Jairo SandovalProyecto realizado para entrega final del curso de NLP & Deep Learning

📚 Tecnologías

Python

TensorFlow / Keras

NLTK / VADER / TextBlob

Matplotlib / Seaborn / WordCloud

Pandas / Scikit-learn

🔗 Enlaces

https://www.linkedin.com/in/jairosandovalbiandpo/

https://github.com/Jairosandoval/3_deeplearning/blob/main/DS_opiniones_Usa_Elon_Trump.ipynb)

Gracias por visitar este proyecto 🚀 ¡Tus sugerencias son bienvenidas!
