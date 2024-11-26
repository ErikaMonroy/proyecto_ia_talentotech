
# 📊 Análisis de Sentimientos en Reseñas de Clientes de Amazon

Proyecto final presentado para el **Bootcamp de Inteligencia Artificial Nivel Básico  a través de la iniciativa de Talento Tech del Ministerio de Tecnologías de la Información y las Comunicaciones.** Finalizado en septiembre de 2024. Este proyecto aborda el problema de clasificación de sentimientos utilizando técnicas de **Procesamiento de Lenguaje Natural (PLN)** y **Machine Learning** aplicadas a reseñas de clientes de Amazon. El objetivo principal es clasificar los comentarios en tres categorías: positivos, negativos y neutros, permitiendo comprender mejor la percepción de los usuarios sobre los productos o servicios.


## 📑 Indice

**1.** Introducción

**2.** Objetivos

**3.** Metodología

**4.** Resultados

**5.** Tecnologías Utilizadas

**6.** Próximos Pasos

**7.** Referencias

**8.** Agradecimientos
## 📖 Introducción

💡 El análisis de sentimientos detecta emociones en reseñas y es una herramienta clave para áreas como:

- 📈 Marketing
- 🛠️ Mejora de productos
- 💬 Atención al cliente


**❓Pregunta de investigación:**

¿Cómo se pueden utilizar técnicas de Procesamiento de Lenguaje Natural (PLN) para clasificar los comentarios de clientes como positivos, negativos o neutros, y qué palabras clave influyen en estas clasificaciones?
## 🎯 Objetivos

 **Objetivo General 🌟**

Desarrollar un sistema que clasifique automáticamente los sentimientos de los comentarios de los clientes, basado en técnicas de aprendizaje automático y PLN.

**Objetivos Específicos ✅**

**1.** Recopilación y preprocesamiento de datos: Descargar el dataset de reseñas de Amazon, limpiar y normalizar el texto para eliminar ruido y obtener datos relevantes para el análisis.

**2.** Análisis exploratorio de datos (EDA): Realizar un análisis inicial para conocer la distribución de los datos, identificar patrones en las reseñas y detectar posibles problemas como desequilibrio en las clases.

**3.** Implementación de técnicas de PLN: Aplicar técnicas como la tokenización, lematización y la vectorización de texto (TF-IDF o embeddings) para extraer características útiles para el modelo.

**4.** Entrenamiento y evaluación del modelo: Se utilizar un algoritmo de aprendizaje automático (Naive Bayes) y evaluaremos su rendimiento utilizando métricas como precisión, recall y F1-score.
## 🛠️ Metodología

**1. Preprocesamiento de datos 📄:**

- Eliminación de duplicados, puntuación y stopwords.
- Tokenización y lematización.

**2. Análisis exploratorio 📊:**

- Visualización de la distribución de clases y longitud de reseñas.
- Identificación de palabras más frecuentes por sentimiento.

**3. Entrenamiento del modelo 🤖:**

- Modelo base: Naive Bayes.
- Ajuste de hiperparámetros (alpha).
- Validación cruzada y matriz de confusión.

**4. Evaluación 📈:**

- Métricas utilizadas: precisión, recall, F1-score y accuracy.
## 📊 Resultados

**1.** 🎯 Precisión global: 95.6%.

**2.** 📋 Matriz de confusión: Errores mínimos entre clases positivas y neutras.

**3.** 🗣️ Palabras clave por sentimiento:

- great, good, fast.
- problem, defectuoso.
- use, work.

✔️ El modelo es altamente confiable para clasificar reseñas cortas y balanceadas.
## 💻 Tecnologías Utilizadas

- 🐍 Python: Desarrollo del pipeline y análisis de datos.
- 📚 NLTK: Procesamiento de lenguaje natural.
- 📊 Scikit-learn: Modelado y métricas de evaluación.
- 📈 Matplotlib y Seaborn: Visualización de datos.
- 🐍 Anaconda: Entorno integrado para la gestión de paquetes y dependencias.
- 📓 Jupyter Notebook: Plataforma para desarrollar y documentar el proyecto de manera interactiva.

## 🔮 Próximos Pasos

- 🤖 Explorar modelos avanzados como BERT para mejorar la clasificación en casos ambiguos.
- 🧠 Implementar embeddings de palabras (Word2Vec, GloVe).
- 📂 Ampliar el dataset para mayor robustez.
- 🌐 Integrar el modelo en aplicaciones reales para análisis de sentimientos en tiempo real.
- 📊 Mejorar la visualización de resultados con dashboards interactivos.
## 📚 Referencias

- Dataset de reseñas de Amazon obtenido de Kaggle
- Documentación oficial de NLTK: https://www.nltk.org/.
- Tutoriales del Bootcamp de Inteligencia Artificial de Talento Tech.
- Documentación oficial de Scikit-learn: https://scikit-learn.org/.
## 🤝 Agradecimientos

A la iniciativa de Talento Tech, impulsada por el Ministerio de Tecnologías de la Información y las Comunicaciones, por promover el desarrollo del talento digital en Colombia y proporcionar oportunidades educativas de alta calidad en tecnologías emergentes.
## ⚡ Este proyecto es una herramienta poderosa para extraer insights valiosos y mejorar decisiones estratégicas.
¡Explora el código, aprende y contribuye! 🙌