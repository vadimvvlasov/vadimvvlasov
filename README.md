## Vadim Vlasov · AI/LLM Engineer, ML Engineer (Geospatial CV)

5+ years in production ML: computer vision and satellite imagery analysis at state scale.
Since 2026 I build LLM services: AI agents, RAG systems and evaluation of model answers.

---

### LLM projects

| Project | What it shows |
|---|---|
| [anti-scope-creep](https://github.com/vadimvvlasov/anti-scope-creep) | LLM contract review for freelancers, in production on AWS and Cloudflare. Eval on 52 held-out contracts: recall 0.85 (17 of 20 risks), precision 0.65-0.74; a plain prompt gets 2 of 10 findings right. Groq vs Gemini comparison, prompt injection tests, 450+ automated tests, CI/CD with manual approval for production |
| [llm-fact-checker](https://github.com/vadimvvlasov/llm-fact-checker) | RAG fact-checking of business reports: hybrid search (pgvector + full text), reranking, RAGAS evaluation, 79% correct verdicts on 76 claims |
| [order-tracker](https://github.com/vadimvvlasov/order-tracker) | AI agent that took an error alert, found the bug and fixed it with regression tests |
| [household-chores-manager](https://github.com/vadimvvlasov/household-chores-manager) | App built by a team of AI agents with PM, engineer and QA roles |

---

### Geospatial ML at Agro Software (fieldstat.ai)

| What | Numbers |
|---|---|
| Field boundary model (ResUNet-A), fine-tuning | Brazil MCC 0.81 → 0.89, Argentina 0.87 |
| Production pipeline stages (Airflow + AWS) | 23 US and 14 Brazilian states, about 10M km²; about 20M fields in the US |
| Post-processing, São Paulo state (~1.5M fields) | 33h → 18h, peak memory 50 → 31 GB |
| Satellite image download | 2.7x faster (retry pauses and a thread lock removed) |
| Crop classification (Transformer Encoder) | location and acquisition week encoders: macro F1 +6.2% |

Public demo: [satellite-field-segmentation](https://github.com/vadimvvlasov/satellite-field-segmentation), field boundary detection with ResUNet-A, geospatial post-processing, GeoPackage output.

---

### Stack

`Python` `LLM APIs` `RAG` `FastAPI` `PostgreSQL` `React` `GitHub Actions` `Docker`
`PyTorch` `TensorFlow` `Apache Airflow` `AWS` `GDAL` `Rasterio` `GeoPandas` `eo-learn` `STAC` `Sentinel-2`

---

📍 Open to remote roles &nbsp;·&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/vadim-vlasov-181503b6/) &nbsp;·&nbsp; 🌐 [CV](https://vadimvvlasov.github.io/cv/)
