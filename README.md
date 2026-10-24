<div align="center">
  <h1>Khushal Pareta | @Kennny7</h1>
  
  <p>
    <a href="https://linkedin.com/in/khushal-pareta-704355338"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn"></a>
    <a href="mailto:Khushalpareta9@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail" alt="Email"></a>
    <a href="https://Kennny7.github.io"><img src="https://img.shields.io/badge/Portfolio-Visit-success?style=for-the-badge&logo=github" alt="Portfolio"></a>
    <a href="https://github.com/Kennny7"><img src="https://img.shields.io/badge/GitHub-Follow-lightgrey?style=for-the-badge&logo=github" alt="GitHub"></a>
  </p>
  
  <p>
    <i>Build systems that scale, not scripts that work once.</i>
  </p>
  
</div>

---

AI and ML engineer, about three years in, working mostly on the parts of GenAI that sit below the demo. Retrieval pipelines that have to cite the regulation currently in force and not the one it replaced. Agent workflows that fail loudly instead of quietly. Data pipelines where a dropped record is a real problem and not a rounding error.

I work mainly in Python and SQL. I deploy with Docker, Airflow, and MLflow. A lot of my time goes into Postgres, Milvus, and Neo4j, and lately into getting GPU vector indexes to behave.

---

<details open>
<summary><strong>Core Competencies</strong></summary>
<br>

| Domain | Tools |
|---------------------------|--------|
| **Languages** | Python, SQL, Bash |
| **Generative AI** | OpenAI, Azure OpenAI, Gemini, Claude, Llama, LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, Google ADK, Hugging Face, prompt engineering, RAG, GraphRAG, LoRA fine tuning, model evaluation |
| **Retrieval and Vector Stores** | Milvus (`GPU_CAGRA`, `GPU_IVF_FLAT`, `GPU_IVF_PQ`), Chroma, FAISS, Pinecone, pgvector, hybrid search, reranking, index tuning |
| **Graph and Ontology** | Neo4j, Cypher, property graph modelling, ontology design, LLM assisted entity and relation extraction |
| **Machine Learning** | scikit-learn, XGBoost, LightGBM, statsmodels, regression, classification, clustering, time series forecasting, SHAP |
| **Deep Learning and NLP** | TensorFlow, Keras, PyTorch, BERT and sentence transformers, LSTM and GRU, spaCy, NLTK, OCR (Tesseract, EasyOCR), OpenCV |
| **Data Engineering** | PySpark, Hadoop, Hive, Kafka, Airflow, dbt, Parquet, Avro, ETL and ELT, Great Expectations, medallion architecture |
| **MLOps** | MLflow, Docker, Docker Compose, Kubernetes basics, Helm basics, GitHub Actions, Jenkins, Azure DevOps, model registry, drift monitoring |
| **Cloud** | AWS (S3, Lambda, Glue, Athena, Bedrock, SNS, CloudWatch), Azure (Azure OpenAI, AI Foundry, ML Studio, Blob, Event Hubs, Azure SQL), GCP (Vertex AI, BigQuery basics) |
| **Databases** | PostgreSQL (query tuning, indexing, pgBouncer, PL/pgSQL), MySQL, MongoDB, Neo4j, Milvus, Redis basics |
| **Monitoring and Logging** | Prometheus, Grafana, ELK Stack, Kibana, CloudWatch, Azure Monitor |
| **Visualization** | Streamlit, Power BI, Tableau, Plotly |

</details>

---

<details open>
<summary><strong>What I have built</strong></summary>
<br>

**Thanatos** (personal). A local first multi agent engine. FastAPI backend, Flutter client, and four database engines running under one Docker supervisor: Postgres for state, MongoDB for transcripts, Milvus for vectors, Neo4j for the knowledge graph. Agents can offload work to other machines on a LAN mesh, memory is RAG backed, and every action goes into a tamper evident audit log.

**Maritime Knowledge Cluster** (C-DAC). A GraphRAG assistant over maritime regulations. Hybrid retrieval combining Milvus GPU vector search with k hop expansion over a Neo4j ontology, so answers cite the regulation currently in force and can trace its amendment chain. LangGraph and CrewAI handle the agent layer.

**LRIT** (C-DAC). AIS ingestion plus two models on top. A tree based classifier for malformed and spoofed records, and a GRU route prediction model evaluated on ADE and FDE.

**NFHS** (C-DAC). PySpark ingestion and validation for the National Family Health Survey, with dashboards for the Ministry of Health.

**CotBoz** (C-DAC). Backend for a cotton and bale procurement platform, including validation and reconciliation pipelines.

</details>
