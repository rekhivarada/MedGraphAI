#  MedGraph AI

### Symptom-Based Disease & Treatment Assistant

MedGraph AI is an interactive healthcare application that analyzes user symptoms and patient information to identify **possible conditions, assess risk, and provide personalized health insights**.

##  Features

*  **Hybrid Disease Search** using semantic search + exact symptom matching
*  **AI Embeddings** with Sentence Transformers and ChromaDB
*  **Knowledge Graph** using Neo4j for disease, symptom, medication, and precaution relationships
*  **Risk Assessment** based on symptoms, severity, age, and medical conditions
*  **Medication Safety Checks** based on allergies, conditions, age, and current medications
*  **Lab Test & Specialist Recommendations**
*  **Interactive Visualizations** using Plotly
*  **PDF Health Report** generation
*  **Personalized Recommendations** based on patient profile

##  Tech Stack

```text
Python
Streamlit
Sentence Transformers
ChromaDB
Neo4j
Pandas
Plotly
FPDF
```

##  Architecture

```text
User Symptoms
      ↓
Semantic Search + Exact Matching
      ↓
Hybrid Disease Ranking
      ↓
Neo4j Knowledge Graph
      ↓
Risk & Personalization
      ↓
Tests + Specialists + Recommendations
      ↓
Interactive Dashboard + PDF Report
```

##  Setup

```bash
git clone https://github.com/your-username/MedGraph-AI.git
cd MedGraph-AI

pip install streamlit pandas chromadb neo4j sentence-transformers plotly fpdf2
```

Prepare the datasets:

```bash
python loaddata.py
```

Run the application:

```bash
streamlit run Final.py
```

##  Project Structure

```text
MedGraph-AI/
├── Final.py
├── loaddata.py
├── Datasets/
├── master_disease_data.csv
├── *_edges.csv
├── *_nodes.csv
└── README.md
```

##  Disclaimer

MedGraph AI is an **educational project** and does not provide medical diagnosis or replace professional medical advice.

