# 🛡️ SentinX: AI-Driven Victim Case Analysis & Recommendation System

SentinX is an advanced Data Science project designed to handle unstructured victim case data. It utilizes Natural Language Processing (NLP) and Unsupervised Machine Learning to identify patterns in case histories, analyze root causes, and suggest preventive actions for the future.

## 🚀 Key Features
- **Unstructured Data Processing**: Cleans and processes raw text data from case details.
- **Semantic Search**: Search cases by ID and retrieve contextually similar historical data.
- **Intelligent Clustering**: Uses **HDBSCAN** and **SBERT** to automatically group cases by root causes without manual labeling.
- **Prescriptive Analytics**: Recommends specific actions to mitigate future occurrences based on historical patterns.

## 🏗️ System Architecture
The system is built on a 4-Pillar Architecture:
1. **Data Ingestion**: Handling CSV/Unstructured text inputs.
2. **Semantic Layer**: Converting text to high-dimensional vectors using `Sentence-Transformers`.
3. **Pattern Engine**: Clustering using `UMAP` (dimensionality reduction) and `HDBSCAN`.
4. **Recommendation Layer**: Mapping clusters to actionable preventive measures.



## 🛠️ Tech Stack
- **Language**: Python 3.x
- **Libraries**: 
  - `Pandas`, `NumPy` (Data Manipulation)
  - `Sentence-Transformers` (SBERT Embeddings)
  - `HDBSCAN` (Clustering)
  - `UMAP-learn` (Dimensionality Reduction)
  - `Scikit-learn` (Evaluation)
