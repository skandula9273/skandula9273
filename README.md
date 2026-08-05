# Santosh Kandula

Applied ML — LLM retrieval and evaluation, computer vision. CS junior at UNC Chapel Hill, class of 2027.

I build systems with eval harnesses attached and publish what the harness catches, including
the times it caught me overstating a result.

**Now**

- **[sec-rag-eval](https://github.com/skandula9273/sec-rag-eval)** — retrieval QA over SEC filings
  and the platform that measures it. recall@5 0.44 → 0.64 on FinanceBench-150. Scoring the identical
  retrieval three ways gives 0.09, 0.64, and 0.81, which is why the harness matters more than the
  number. [Live demo](https://sec-rag-web-200217758117.us-east1.run.app)
- **[hoopvec](https://github.com/skandula9273/nba-broadcast-tracking)** — player tracking from NBA
  broadcast video plus a play-embedding model, built to measure how much retrieval degrades on
  reconstructed tracking. HOTA 0.301 → 0.525. Identity switches, not per-frame perception, are what
  break downstream analytics.

**Stack** — Python · PyTorch · TensorFlow · FastAPI · PostgreSQL/pgvector · FAISS · YOLOv8 ·
ByteTrack · ONNX · Docker · GCP Cloud Run · AWS Bedrock

**Reach me** — [LinkedIn](https://www.linkedin.com/in/santoshkandula/) · skandula9273@gmail.com
