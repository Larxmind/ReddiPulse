# ReddiPulse 🚀

**ReddiPulse** is an automated data pipeline designed to analyze the collective mood of various Reddit communities in real-time. 

## 🛠 Tech Stack
* **Ingestion:** Python (PRAW)
* **Storage:** MongoDB Atlas (Cloud-native NoSQL)
* **AI Model:** Hugging Face Transformers (NLP)
* **Cloud Infrastructure:** AWS (via GitHub Student Benefits)

## 📊 Project Architecture


1. **Extraction:** Fetching posts from Tech, Sports, Cars, and Politics subreddits.
2. **Processing:** Text cleaning and Sentiment Analysis using Deep Learning.
3. **Insights:** Visualizing sentiment trends and community polarity.

-------------------------------------------------------------------------

# ReddiPulse 🚀

**ReddiPulse** es un pipeline de datos automatizado de extremo a extremo diseñado para monitorear y analizar el sentimiento colectivo de diversas comunidades de Reddit. Desarrollado como parte de una **especialización en IA y Big Data**, este proyecto demuestra una arquitectura robusta para el manejo de datos semiestructurados y la aplicación de modelos de Deep Learning en la nube.

## 🛠 Stack Tecnológico
* **Ingesta:** Python (PRAW - Reddit API Wrapper)
* **Almacenamiento:** MongoDB Atlas (Cluster NoSQL alojado en AWS)
* **IA y NLP:** Hugging Face Transformers (BERT/RoBERTa)
* **Entorno:** Python 3.12+ con Dotenv para la gestión segura de credenciales

## 📊 Arquitectura del Proyecto
El sistema sigue un ciclo de vida de datos profesional:
1. **Extracción:** Captura automatizada de posts destacados en diversos subreddits (Tecnología, Coches, Economía, Deportes, Política).
2. **Persistencia:** Los datos crudos se guardan en MongoDB mediante una estrategia de "upsert" para garantizar la integridad de los datos.
3. **Inteligencia:** Un motor de NLP procesa registros pendientes para clasificar el sentimiento y detectar la polaridad.
4. **Insights:** Los datos se preparan para su visualización y análisis de tendencias temporales.

## 🚀 Características Principales
- **Pipeline Idempotente:** Evita duplicados mediante el rastreo de IDs únicos.
- **Almacenamiento Escalable:** Aprovecha NoSQL en la nube para una evolución flexible del esquema.
- **NLP de Vanguardia:** Utiliza modelos basados en Transformers para una comprensión contextual del sentimiento.
