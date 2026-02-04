# ReddiPulse 🚀

<p align="center">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python">
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
</p>

<p align="center">
  <a href="#english">English</a> • 
  <a href="#español">Español</a>
</p>

---

<a name="english"></a>
## English 🇬🇧

**ReddiPulse** is an automated end-to-end data pipeline designed to monitor and analyze the collective sentiment of various Reddit communities in real-time. Developed as part of a specialization in **AI and Big Data**, this project demonstrates a robust architecture for handling semi-structured data and applying Deep Learning models in a cloud-native environment.

### 🛠 Tech Stack
* **Ingestion:** Python (PRAW - Reddit API Wrapper)
* **Storage:** MongoDB Atlas (Cloud-native NoSQL hosted on AWS)
* **AI & NLP:** Hugging Face Transformers (BERT/RoBERTa)
* **Environment:** Python 3.12+ with Dotenv for secure credential management

### 📊 Project Architecture
The system follows a professional data lifecycle:
1. **Extraction:** Automated fetching of "Hot" posts from diverse subreddits (Tech, Cars, Economy, Sports, Politics).
2. **Persistence:** Raw data is stored in MongoDB using an "upsert" strategy to ensure idempotency and data integrity.
3. **Intelligence:** An NLP engine processes unprocessed records to classify sentiment and detect polarity.
4. **Insights:** Data is prepared for visualization to show trends over time.

### 🚀 Key Features
- **Idempotent Pipeline:** Prevents duplicate records through unique ID tracking.
- **Scalable Storage:** Leverages cloud NoSQL for flexible schema evolution.
- **State-of-the-art NLP:** Uses Transformer-based models for contextual sentiment understanding.

---

<a name="español"></a>
## Español 🇪🇸

**ReddiPulse** es un pipeline de datos automatizado de extremo a extremo diseñado para monitorear y analizar el sentimiento colectivo de diversas comunidades de Reddit. Desarrollado como parte de una **especialización en IA y Big Data**, este proyecto demuestra una arquitectura robusta para el manejo de datos semiestructurados y la aplicación de modelos de Deep Learning en la nube.

### 🛠 Stack Tecnológico
* **Ingesta:** Python (PRAW - Reddit API Wrapper)
* **Almacenamiento:** MongoDB Atlas (Cluster NoSQL alojado en AWS)
* **IA y NLP:** Hugging Face Transformers (BERT/RoBERTa)
* **Entorno:** Python 3.12+ con Dotenv para la gestión segura de credenciales

### 📊 Arquitectura del Proyecto
El sistema sigue un ciclo de vida de datos profesional:
1. **Extracción:** Captura automatizada de posts destacados en diversos subreddits (Tecnología, Coches, Economía, Deportes, Política).
2. **Persistencia:** Los datos crudos se guardan en MongoDB mediante una estrategia de "upsert" para garantizar la integridad de los datos.
3. **Inteligencia:** Un motor de NLP procesa registros pendientes para clasificar el sentimiento y detectar la polaridad.
4. **Insights:** Los datos se preparan para su visualización y análisis de tendencias temporales.

### 🚀 Características Principales
- **Pipeline Idempotente:** Evita duplicados mediante el rastreo de IDs únicos.
- **Almacenamiento Escalable:** Aprovecha NoSQL en la nube para una evolución flexible del esquema.
- **NLP de Vanguardia:** Utiliza modelos basados en Transformers para una comprensión contextual del sentimiento.

---
*Developed by a Web Developer & AI/Big Data Specialist.*