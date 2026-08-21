# Hi, I'm Varun 👋

I'm a Software Engineer with a background in AI systems, backend engineering, and infrastructure automation. I build things that are meant to run in production — agentic workflows, RAG pipelines, GPU-optimized inference systems, ETL pipelines, and full-stack applications. I recently completed my M.S. in Computer Science at UCF (3.9/4.0) and have 3+ years of professional experience across research, startup, and data engineering environments.

I default to AI-assisted development (Claude Code, GitHub Copilot) and care about building systems that are observable, secure, and maintainable — not just demos that work once.

---

## 🛠️ What I Build

| Area | What |
|------|------|
| **Agentic AI** | Multi-agent systems, LangGraph orchestration, MCP tool-calling, Google ADK, A2A protocol |
| **RAG & Retrieval** | pgvector, Pinecone, Weaviate hybrid search, LlamaIndex, semantic chunking, eval pipelines |
| **Backend & APIs** | FastAPI, Flask, REST APIs, PostgreSQL, Redis, SQLAlchemy, Pydantic |
| **ML & Inference** | PyTorch, JAX, TensorFlow, CUDA C++, ONNX Runtime, vLLM, Flash Attention v2 |
| **Data Engineering** | ETL/ELT pipelines, Scrapy, Pandas, NumPy, Apache Spark, Databricks |
| **Infrastructure** | Docker, Kubernetes, Helm, GitOps, OpenShift, GitHub Actions CI/CD, OpenTelemetry |
| **Cloud** | GCP, AWS, Azure (OpenAI, AI Foundry, Cosmos DB, Monitor) |
| **Full Stack** | React, TypeScript, WebSockets, C# / .NET 8, Semantic Kernel |

---

## 🚀 Projects

### 🤖 [Hermes](https://github.com/varunmuchanapally)
**Multi-Agent Real-Time Coordination System**  
80 concurrent autonomous agents orchestrated via Google ADK and the Agent2Agent (A2A) protocol. A Supervisor Agent routes JSON schema state contexts to domain-isolated execution agents. Real-time Mapbox dashboard streamed over WebSockets. Every service instrumented with OpenTelemetry v1.26. Deployed on Kubernetes with Helm under GitOps.  
`Python 3.11` `Google ADK` `LangGraph` `FastAPI` `Redis 7.2` `WebSockets` `React` `TypeScript` `OpenTelemetry` `Kubernetes`

---

### 🧭 [CivicPath](https://github.com/varunmuchanapally)
**Agentic RAG Platform for Policy Navigation**  
LangGraph orchestrates a 4-stage retrieval pipeline: semantic chunking, multi-query expansion, Pinecone ANN search, cross-encoder reranking. Automated evaluation pipeline tracking answer relevance, citation recall, hallucination rate, and p95 latency. Redis caching cut LLM API costs 40%. Deployed on GCP Cloud Run with GitHub Actions CI/CD.  
`Python 3.11` `LangGraph` `LangChain` `LlamaIndex` `Pinecone` `FastAPI` `React` `GCP Cloud Run` `Redis` `OpenTelemetry`

---

### ⚡ [CUDA Kernel Optimization](https://github.com/varunmuchanapally)
**GEMM Performance Tuning on Ampere Architecture**  
Three-iteration GEMM kernel optimization: naive global-memory (2 TFLOPS) → shared-memory tiling (28 TFLOPS) → Tensor Core wmma (112 TFLOPS). 1.32x speedup vs cuBLAS. SM utilization 12% → 82%. 80% bank conflict reduction confirmed via Nsight Compute.  
`CUDA C++ (sm_80)` `Nsight Compute` `wmma API` `Tensor Cores` `cuBLAS v2` `A100`

---

### 🔍 [LLaMA-2-7B Inference Optimization](https://github.com/varunmuchanapally)
**Bottleneck Analysis and Latency Optimization**  
Profiled decode phase with PyTorch Profiler and Nsight Compute. Identified memory-bound bottleneck at 28% GPU utilization via roofline model analysis. Flash Attention v2 + INT8 quantization → 3.2x latency improvement (71ms → 22ms/token), 45% cost reduction.  
`PyTorch 2.0` `Nsight Compute` `Flash Attention v2` `vLLM` `INT8 Quantization` `A100`

---

### 🧬 [Gemma-2B Fine-Tuning Pipeline](https://github.com/varunmuchanapally)
**Parameter-Efficient LLM Training in JAX/Flax**  
LoRA fine-tuning from scratch in JAX/Flax using jax.jit and jax.vmap. 2.1x throughput on a single NVIDIA T4 GPU. Custom gradient checkpointing routine reducing peak VRAM by 45%.  
`JAX` `Flax` `Optax` `LoRA` `Hugging Face` `NVIDIA T4`

---

### 📦 [Enterprise Inventory ETL and RAG Pipeline](https://github.com/varunmuchanapally)
**Bidirectional ETL Across Enterprise Systems with Natural Language Queries**  
Integrates SCCM 2309, ManageEngine AssetExplorer v14, and ServiceNow REST APIs into a unified PostgreSQL 16 data platform serving 10,000+ endpoints. LLaMA 3.1-8B RAG via LlamaIndex + pgvector enables plain-English inventory queries.  
`Python 3.11` `FastAPI` `PostgreSQL 16` `pgvector` `SQLAlchemy` `Docker` `Kubernetes`

---

### 🔬 [MCP ASIC Register Map & C Code-Gen Platform](https://github.com/varunmuchanapally)
**MCP-Integrated AI Code Generation with GCC Validation**  
MCP v0.4.0 exposes JSON/XML hardware registers to GPT-4o and Claude 3.5 Sonnet. Processed 5,000+ legacy registers into C99 macro headers. GCC 13 compiler validation runs in Dockerized GitHub Actions CI/CD.  
`Python 3.11` `MCP v0.4.0` `FastAPI` `Redis 7.2` `GPT-4o` `Claude 3.5` `Docker` `GitHub Actions` `GCC 13`

---

### 📊 [Annotation-Free Semantic Segmentation Engine](https://github.com/varunmuchanapally)
**PyTorch Training, INT8 Quantization, and ONNX Inference**  
ResNet-34 + U-Net trained on COCO-Stuff 2017 (80K images). 97.06% validation accuracy, 0.8776 Dice score. INT8 PTQ compressed model 74%. ONNX Runtime via TorchScript cut CPU inference from 110ms to 24ms.  
`PyTorch` `ResNet-34` `U-Net` `ONNX Runtime` `TorchScript` `INT8 PTQ` `COCO-Stuff 2017`

---

### 📈 [Yield Curve Prediction with XGBoost](https://github.com/varunmuchanapally)
**Quantitative ML Forecasting on Macroeconomic Indicators**  
XGBoost model predicting yield curve movements using FRED API macroeconomic indicators. Scikit-Learn evaluation metrics, 5-fold stratified cross-validation, Bayesian hyperparameter tuning via Optuna.  
`Python` `XGBoost` `Scikit-Learn` `Pandas` `NumPy` `FRED API` `Optuna`

---

## 💼 Experience

| Role | Company | Period |
|------|---------|--------|
| AI Information Technology Engineer | Institute for Simulation & Training, UCF | Jun 2025 – May 2026 |
| Machine Learning Engineer | Stealth AI Startup | May 2023 – Jun 2024 |
| Machine Learning Fellow | Amazon ML Summer School | Sep 2023 – Nov 2023 |
| Python Developer | Forage AI | Apr 2022 – Apr 2023 |

---

## 🎓 Education

**M.S. Computer Science** — University of Central Florida (GPA: 3.9/4.0) | Aug 2024 – May 2026  
**B.Tech Computer Science** — BV Raju Institute of Technology | Nov 2020 – May 2024

---

## 📜 Certifications

- NVIDIA AI Operations Associate
- AWS ML Engineer Associate
- Databricks ML Professional
- Azure AI Engineer Associate
- Azure AI Fundamentals
- Microsoft Power Platform Fundamentals (PL-900)

---

## 🧰 Tech Stack

```
Languages      Python 3.11 · C++17 · C · C# · TypeScript · JavaScript · SQL · Bash
AI / Agents    LangGraph · LangChain · LlamaIndex · Google ADK · MCP v0.4.0 · Semantic Kernel
               OpenAI API · Anthropic API · RAG · Prompt Engineering · LLM Evaluation
ML / Training  PyTorch · JAX · Flax · TensorFlow · Scikit-Learn · Hugging Face · LoRA · ONNX Runtime
GPU / Systems  CUDA C++ (sm_80) · Nsight Compute · wmma API · Flash Attention v2 · vLLM · cuBLAS
Vector / Data  pgvector · Pinecone · Weaviate · PostgreSQL 16 · Redis 7.2 · MongoDB · Pandas · NumPy
Cloud          GCP · AWS · Azure (OpenAI · AI Foundry · Cosmos DB · Monitor · Document Intelligence)
DevOps         Docker · Kubernetes · Helm · GitOps · OpenShift · GitHub Actions CI/CD · OpenTelemetry
Web / Backend  FastAPI · Flask · ASP.NET Core · React · WebSockets · REST APIs
```

---

## 📬 Contact

- 📧 varunmuchanapally@gmail.com
- 💼 [linkedin.com/in/varun-pm](https://linkedin.com/in/varun-pm)
- 🌐 [varunmuchanapally.github.io/Portfolio-space](https://varunmuchanapally.github.io/Portfolio-space)
