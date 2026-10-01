# Hi, I'm Vedant Deshmukh 👋

**Software Engineer | C++ · Python · AI Systems**

M.Tech graduate in Computational & Data Science from NIT Karnataka, with one year of software-development experience at Siemens Digital Industries Software.

I build systems at the intersection of software engineering, AI infrastructure, automated validation, and performance engineering. I focus on understanding, measuring, and validating how systems work—not merely connecting APIs.

Currently seeking entry-level **Software Engineering, AI Infrastructure, ML Systems, and C++/Python** opportunities.

---

## Featured Projects

### [SupersedAI — AI-Assisted C++ Modernization Agent](https://github.com/deshmukhvs23/SupersedAI)

A validation-first AI agent that safely modernizes legacy C++ using NVIDIA Nemotron models through Nebius Token Factory.

- Uses `clang-tidy` for semantic candidate discovery, with regex scanning as a fallback
- Sends bounded, location-anchored source context to NVIDIA Nemotron for structured edits
- Applies exact-match, location-aware patches while preserving LF and CRLF line endings
- Validates every accumulated change through CMake builds, CTest discovery, and repository tests
- Rejects repositories with no registered tests to prevent false validation
- Retries failed edits with diagnostic feedback, escalates from Nano to Super, and rolls back unsuccessful changes
- Records per-attempt latency, model tier, failure category, repository revision, CMake configuration, and token usage
- Validated **20/20 patches across TinyXML-2 and pugixml**, with **95% first-pass success** and only one strong-model escalation
- Supported by **72 offline tests** and committed, reproducible evaluation artifacts
- `Python` `C++` `clang-tidy` `NVIDIA Nemotron` `Nebius Token Factory` `CMake` `CTest` `pytest`

### [InferX — LLM Inference Engine](https://github.com/deshmukhvs23/inferx)

An experimental LLM-serving engine built to understand inference internals and GPU performance engineering.

- Implemented explicit prefill and iterative token decoding with KV caching
- Added prefill latency, decode latency, throughput, token-count, and device-level measurements
- Served Qwen2.5-0.5B-Instruct through a FastAPI REST endpoint
- Achieved approximately **24.9 generated tokens/second** on a 4 GB NVIDIA GTX 1050
- Built a foundation for batching, quantization, request scheduling, paged KV caching, and custom CUDA kernels
- `Python` `PyTorch` `Transformers` `CUDA` `FastAPI` `Linux`

### [Automated 3D PDF Validation Pipeline](https://github.com/deshmukhvs23/Image-Comparison-Autotest)

Developed during my M.Tech project and Siemens internship to verify visual fidelity between Siemens NX views and exported Technical Data Packages.

- Rendered reference views from STL geometry using standard engineering viewpoints
- Extracted camera-to-world matrices from 3D PDFs and reconstructed matching viewpoints
- Compared silhouettes using SSIM, IoU, dilation, and color-coded difference maps
- Built an automated pass/fail pipeline for visual regression detection
- Reduced dependence on manual inspection and licensed desktop tools during validation
- `C++` `Python` `NX Open` `OpenCV` `SSIM` `IoU` `3D PDF/PRC`

### [ML-Based Stock Direction Analysis](https://github.com/deshmukhvs23/ML-Driven-Trading-Signals)

Evaluated whether technical indicators provide a measurable signal for next-day stock direction.

- Engineered momentum, volume, volatility, and trend features including SMA, RSI, CCI, Bollinger Bands, and OBV
- Compared Logistic Regression, Random Forest, XGBoost, LightGBM, CatBoost, and AdaBoost
- Used chronological train/test splits to reduce time-series data leakage
- Reported the weak AUC result honestly instead of overstating model performance
- `Python` `scikit-learn` `XGBoost` `LightGBM` `CatBoost` `Pandas`

---

## Experience

### Siemens Digital Industries Software — NX Software Developer Intern

*June 2025 – June 2026*

- Contributed production C++ and Python code within the NX Model Based Definition team
- Developed an automated image-comparison pipeline for Technical Data Package validation
- Integrated third-party APIs into the NX C++ codebase
- Implemented backend logic for engineering annotation workflows
- Investigated defects and regressions across 3D PDF export, rendering, viewport, and digital-signature workflows
- Built utilities and automated tests for repeatable regression verification
- Worked with code reviews, debugging, API integration, and validation in a large engineering software codebase

---

## Technical Skills

```text
Languages       C++ · Python · Java · C · SQL
AI / ML         PyTorch · scikit-learn · OpenCV · XGBoost · CatBoost
AI Systems      LLM inference · KV caching · Model APIs · Prompt design · Evaluation
GPU / Parallel  CUDA · OpenMP · MPI · GPU inference fundamentals
Systems         Linux · WSL2 · CMake · CTest · Git · Debugging · Profiling
Backend         FastAPI · Django · REST APIs · SQL
Engineering     Testing · Code review · Regression automation · Performance measurement
Domain Tools    NX Open · 3D PDF/PRC · SSIM · IoU · Camera matrices
```

---

## Education

- **M.Tech, Computational & Data Science** — National Institute of Technology Karnataka, Surathkal *(2024–2026)*
- **B.Tech, Instrumentation and Control Engineering** — Vishwakarma Institute of Technology, Pune *(2019–2023)*
- **GATE CSE 2024** — Score 621 · AIR 2067

---

## Current Focus

- Modern C++ and Linux systems programming
- LLM inference and AI infrastructure
- CUDA and GPU performance engineering
- Reliable AI-assisted software development
- Profiling, benchmarking, and evaluation
- Data structures, algorithms, and software design

---

## Connect

- GitHub: [github.com/deshmukhvs23](https://github.com/deshmukhvs23)
