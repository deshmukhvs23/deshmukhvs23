# Hi, I'm Vedant Deshmukh 👋

**Software Engineer | C++ · Python · AI Systems**

M.Tech in Computational & Data Science from NIT Karnataka, with one year of software development experience at Siemens Digital Industries Software.

I build systems at the intersection of software engineering, AI infrastructure, automated validation, and performance engineering. I prefer understanding and measuring how a system works—not merely connecting APIs.

Currently seeking entry-level **Software Engineering, AI Infrastructure, ML Systems, and C++/Python** opportunities.

---

## Featured Projects

### [cpp-modernize-agent](https://github.com/deshmukhvs23/cpp-modernize-agent)

AI-assisted C++ modernization agent powered by NVIDIA Nemotron through Nebius Token Factory.

- Detects legacy C++ patterns and requests structured, exact-match edits
- Validates every change through CMake builds and CTest
- Retries failed edits with a stronger model and restores unsuccessful changes
- Preserves CRLF/LF formatting and records attempt-level evaluation metrics
- Successfully validated `NULL → nullptr` on the TinyXML-2 repository
- `Python` `C++` `NVIDIA Nemotron` `Nebius Token Factory` `CMake` `CTest` `pytest`

### [InferX — LLM Inference Engine](https://github.com/deshmukhvs23/inferx)

Experimental LLM-serving engine for understanding inference internals and performance engineering.

- Implemented explicit prefill and iterative decoding using KV caching
- Added latency, throughput, token-count, and device-level measurements
- Served Qwen2.5-0.5B-Instruct through a REST API
- Achieved approximately 24.9 generated tokens/second on a 4 GB GTX 1050
- Roadmap includes batching, quantization, request scheduling, paged KV cache, and CUDA kernels
- `Python` `PyTorch` `Transformers` `CUDA` `FastAPI` `Linux`

### [Automated 3D PDF Validation Pipeline](https://github.com/deshmukhvs23/Image-Comparison-Autotest)

Developed during my M.Tech project and Siemens internship to verify visual fidelity between Siemens NX views and exported Technical Data Packages.

- Rendered reference views from STL geometry
- Extracted camera-to-world matrices from 3D PDFs and reconstructed viewpoints
- Compared silhouettes using SSIM, IoU, dilation, and difference maps
- Built an automated pass/fail pipeline for regression detection
- `C++` `Python` `NX Open` `OpenCV` `SSIM` `IoU` `3D PDF/PRC`

### [ML-Based Stock Direction Analysis](https://github.com/deshmukhvs23/ML-Driven-Trading-Signals)

Evaluated whether technical indicators provide a measurable signal for next-day stock direction.

- Engineered SMA, RSI, CCI, Bollinger Band, OBV, momentum, and volatility features
- Compared Logistic Regression, Random Forest, XGBoost, LightGBM, CatBoost, and AdaBoost
- Used chronological train/test splits to reduce data leakage
- Reported the weak AUC result honestly instead of overstating model performance
- `Python` `scikit-learn` `XGBoost` `LightGBM` `CatBoost` `Pandas`

---

## Experience

### Siemens Digital Industries Software — NX Software Developer Intern

*June 2025 – June 2026*

- Contributed to the Model Based Definition team using production C++ and Python
- Developed an automated image-comparison pipeline for NX Technical Data Package testing
- Worked with NX Open, 3D PDF/PRC, camera matrices, poster images, and engineering geometry
- Investigated defects and regressions across export, rendering, and validation workflows
- Built utilities and automated tests for repeatable verification

---

## Technical Skills

```text
Languages       C++ · Python · Java · C · SQL
AI / ML         PyTorch · scikit-learn · OpenCV · XGBoost · CatBoost
GPU / Parallel  CUDA · OpenMP · MPI · GPU inference fundamentals
Systems         Linux · WSL2 · CMake · Git · REST APIs · Debugging
Backend         FastAPI · Django · SQL · API development
Engineering     Testing · Regression automation · Performance measurement
Domain Tools    NX Open · 3D PDF/PRC · SSIM · IoU · Camera matrices
```

---

## Education

- **M.Tech, Computational & Data Science** — National Institute of Technology Karnataka, Surathkal *(2024–2026)*
- **B.Tech, Instrumentation and Control Engineering** — Vishwakarma Institute of Technology, Pune *(2019–2023)*
- **GATE CSE 2024** — AIR 2067

---

## Current Focus

- Modern C++ and Linux systems programming
- LLM inference and AI infrastructure
- CUDA and GPU performance engineering
- Reliable AI-assisted software development
- Data structures, algorithms, and software design

---

## Connect

- GitHub: [github.com/deshmukhvs23](https://github.com/deshmukhvs23)
