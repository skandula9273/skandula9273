# Santosh Kandula

Applied ML — retrieval and ranking systems, and the evaluation that decides what ships.
CS senior at UNC Chapel Hill, graduating May 2027.

Most of what I build comes in two parts: the system, and the harness that tells me whether
the system actually works. The second part is usually where the interesting result is.

**Now:** extending the SEC retrieval eval from offline to online — interleaving two rankers
on live queries, because passing a merge gate isn't the same as being better in production.

**Shipped:**

- **[sec-rag-eval](https://github.com/skandula9273/sec-rag-eval)** — retrieval and ranking
  over SEC filings, ~10,400 companies, live. recall@5 0.44 → 0.64 on FinanceBench-150.
  Table questions went 0.32 → 0.70, which was the weakness I published first. CI blocks any
  merge that drops search quality.

- **[hoopvec](https://github.com/skandula9273/nba-broadcast-tracking)** —
  multi-object tracking from broadcast video. HOTA 0.301 → 0.525. I injected each perception
  error class separately to find which one actually mattered — it was ID switches, not
  homography or detection noise.

**Stack:** Python · PyTorch · pgvector · FAISS · FastAPI · GCP Cloud Run · ONNX · Docker

[santoshkandula.dev](https://santoshkandula.dev) · [LinkedIn](https://linkedin.com/in/santosh-kandula) · skandula9273@gmail.com
