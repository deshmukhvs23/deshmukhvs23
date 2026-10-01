# Vedant Deshmukh

**C++ · Python · AI Systems**

M.Tech in Computational & Data Science from **NIT Karnataka**, with **one year of software-development experience at Siemens Digital Industries Software**.

Interested in C++, Python, AI systems, automated validation, GPU/ML systems, and performance engineering. Currently seeking **entry-level Software Engineering, AI Infrastructure, ML Systems, and C++/Python roles**.

## Featured Projects

### [SupersedAI — AI-Assisted C++ Modernization Agent](https://github.com/deshmukhvs23/SupersedAI)

A validation-first AI agent for safely modernizing legacy C++, using NVIDIA Nemotron through Nebius Token Factory.

- **20/20 validated patches** across TinyXML-2 and pugixml; **95% first-pass success**, one strong-model escalation, and **72 offline tests**
- Benchmark scope: **one pattern, 10 candidates, and one run per repository**
- Uses `clang-tidy` semantic discovery, bounded, location-anchored model context, and exact-match, location-aware patching
- Validates changes with CMake builds, CTest discovery, and tests; rejects zero-test repositories
- Supports fast-to-strong model escalation and rollback of unsuccessful changes
- Records attempt-level latency, failure, revision, CMake, and token telemetry

### [InferX — LLM Inference Engine](https://github.com/deshmukhvs23/inferx)

An experimental LLM inference engine focused on inference internals and GPU performance.

- Achieved approximately **24.9 generated tokens/second on a 4 GB NVIDIA GTX 1050**
- Implemented explicit prefill and iterative token decoding with KV caching; served Qwen2.5-0.5B-Instruct through FastAPI
- Measured prefill/decode latency, throughput, token counts, and device-level metrics

### [Automated 3D PDF Validation Pipeline](https://github.com/deshmukhvs23/Image-Comparison-Autotest)

Developed during my M.Tech project and Siemens internship to validate visual fidelity between Siemens NX views and exported Technical Data Packages.

- Rendered STL reference views and reconstructed matching viewpoints from 3D PDF camera-to-world matrices
- Compared silhouettes using SSIM, IoU, dilation, and difference maps
- Automated pass/fail checks for visual regression detection

### [ML-Based Stock Direction Analysis](https://github.com/deshmukhvs23/ML-Driven-Trading-Signals)

Evaluated technical indicators for next-day stock direction.

- Engineered momentum, volume, volatility, and trend features; compared linear and tree-based classifiers
- Used chronological train/test splits to reduce time-series leakage
- Observed weak AUC performance; results did not establish a reliable predictive signal

## Experience

### Siemens Digital Industries Software — NX Software Developer Intern

*June 2025 – June 2026*

- Contributed C++ and Python code to the NX Model Based Definition team
- Developed an automated image-comparison pipeline for Technical Data Package validation
- Integrated third-party APIs and implemented backend logic for engineering annotation workflows
- Investigated export, rendering, viewport, and digital-signature defects; built utilities and automated regression tests
- Worked with code reviews and debugging in a large engineering software codebase

## Technical Skills

- **Languages:** C++, Python
- **AI/ML:** PyTorch, Transformers, scikit-learn, LLM inference, KV caching
- **Development & validation:** Linux, Git, CMake, CTest, clang-tidy, FastAPI, OpenCV

## Education

- **M.Tech, Computational & Data Science — NIT Karnataka**, 2024–2026
- **B.Tech, Instrumentation and Control Engineering — VIT Pune**, 2019–2023
- **GATE CSE 2024:** Score **621**, AIR **2067**

## Connect

[GitHub — deshmukhvs23](https://github.com/deshmukhvs23)
