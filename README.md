# Hi, I'm Vedant Deshmukh 👋

M.Tech Computational & Data Science @ NIT Karnataka · Applied AI Engineer · Siemens Industry Software Intern

---

## About me

I build rigorous, production-oriented AI and engineering systems — not just demos. My work spans automated validation pipelines, ML-driven trading engines, and GenAI applications. I care about understanding *why* something works, not just *that* it works.

Currently finishing my MTech thesis on automated 3D PDF validation at Siemens Industry Software, and actively looking for Applied AI / SDE roles.

---

## Projects

### 🔬 [Image Comparison Autotest](https://github.com/deshmukhvs23/Image-Comparison-Autotest)
Automated 3D PDF export validation pipeline built during my MTech thesis at Siemens Industry Software.
- **Stage 1** — Orthographic STL rendering (8 NX standard views)
- **Stage 2** — C2W matrix extraction from 3D PDF and view reconstruction
- **Stage 3** — Silhouette comparison with SSIM + IoU, color-coded diff maps, HTML report
- Deployable on CI servers — no NX license or Adobe Acrobat required
- `Python` `OpenCV` `pikepdf` `SSIM` `IoU` `trimesh` `matplotlib`

---

### 📈 [ML-Driven Trading Signals](https://github.com/deshmukhvs23/ML-Driven-Trading-Signals)
Binary classification pipeline predicting next-day stock direction for 10 high-liquidity stocks.
- 14+ technical features across momentum, volume, volatility, and trend categories
- Chronological train/test split to prevent data leakage
- Confidence-threshold three-zone strategy (Buy ≥0.55, Short ≤0.45, Hold)
- Honest finding: AUC ~0.51 — marginal but consistent edge, aligned with EMH
- `Python` `XGBoost` `AdaBoost` `CatBoost` `AUC-ROC` `Pandas` `yfinance`

---

### 🤖 [RAG Pipeline](https://github.com/deshmukhvs23/rag-pipeline)
Retrieval-Augmented Generation pipeline built from scratch — no framework magic hidden.
- PDF ingestion → chunking → embedding → FAISS index → retrieval → LLM answer
- Every design decision documented: chunk size trade-offs, why cosine similarity, flat vs IVF index
- Evaluation layer with retrieval quality scoring
- `Python` `sentence-transformers` `FAISS` `pypdf` `Anthropic`

---

## Experience

**Siemens Industry Software** — Intern, NX Software *(Jun 2025 – Present)*
- Delivered Image Comparison Autotest POC — integrated Python validation into NX C++ core
- Developed Edge Transition Symbol (ETS) backend logic for MBD annotation workflows
- Resolved critical defects in NX 3D PDF workflows — Viewport APIs, Digital Signature APIs

---

## Skills

```
Languages     Python · C/C++ · Java · SQL
ML / AI       XGBoost · CatBoost · OpenCV · scikit-learn · NumPy · Pandas
GenAI         RAG · Embeddings · Vector DBs · Prompt engineering · LangChain
Backend       FastAPI · REST APIs · Git · Docker
AI Engineering SSIM · IoU · Morphological processing · C2W matrix reconstruction
```

---

## Education

- **M.Tech** Computational & Data Science — NIT Karnataka, Surathkal *(2024–2026)*
- **B.Tech** Instrumentation and Control Engineering — Vishwakarma Institute of Technology, Pune *(2019–2023)*

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vedant_Deshmukh-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/vedant-deshmukh)
[![GitHub](https://img.shields.io/badge/GitHub-deshmukhvs23-181717?style=flat&logo=github)](https://github.com/deshmukhvs23)
[![Email](https://img.shields.io/badge/Email-vedantdeshmukh0444@gmail.com-D14836?style=flat&logo=gmail)](mailto:vedantdeshmukh0444@gmail.com)
