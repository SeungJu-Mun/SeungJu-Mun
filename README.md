<div align="center">

# 👋 Hello, I'm Seungju
### LLM Product Engineer

![header](https://capsule-render.vercel.app/api?type=wave&height=300&color=ADFF2F&text=NUMCHCOMCH&reversal=false&fontAlignY=48&descAlign=47&descAlignY=63&fontAlign=52)

</div>

## 🔭 About Me

I focus on developing non-English LLMs and building efficient ML pipelines for production environments. My work spans the full MLOps lifecycle—from data preprocessing and model training to inference optimization and monitoring.

## ⚡ Research & Project Experience

### 1. Legal Domain Translation LLM Pipeline 
*End-to-end LLMOps infrastructure for low-resource language translation*

- Designed data preprocessing pipeline with MQM-based quality filtering and MinHash deduplication
- Built inference infrastructure using vLLM and TEI on AWS GPU instances (L40s/H100)
- Implemented comprehensive observability stack: OpenTelemetry, Jaeger, Grafana, Prometheus
- Achieved significant BLEU score improvements for Japanese, Urdu, and French translation tasks
- Optimized training environment with NVMe migration, improving efficiency by 37%

### 2. Legal Domain RAG System Development 
*Production-grade retrieval-augmented generation for enterprise applications*

- Deployed RAG systems for finance, legal, and public sector domains using Qdrant and OpenSearch
- Implemented hybrid search with HNSW parameter tuning, achieving 33~50% latency reduction
- Built multi-format document parsing pipeline (PDF, DOCX, PPTX, HWP/HWPX) with OCR integration
- Developed LLM routing architecture for multi-model orchestration and scalability
- Created automated evaluation system using Levenshtein distance and BLEU score metrics
- Established real-time monitoring for TPS, token usage, and retrieval relevance tracking

### 3. Finance-Domain Specialized LLM 
*Domain-adapted small language models for financial services*

- Fine-tuned Gemma and LLaMA with LoRA using SFT/DPO for finance-specific tasks
- Built preprocessing pipeline: SimHash deduplication, OCR, LLM-based quality filtering
- Utilized Accelerate & FSDP for distributed training, quantized with GPTQ (8-bit)
- Deployed inference server with vLLM, achieving 50% latency reduction and 20% performance gain

### 4. On-Device sLLM for Summarization 
*Lightweight language model optimized for edge deployment*

- Conducted continual pretraining on 8×A100 GPUs using Axolotl and Accelerate
- Extended tokenizer with SentencePiece, initialized embeddings via token-average method
- Quantized to 4/8-bit using llama.cpp for CPU inference
- Improved ROUGE scores by 25% with 30% compression gain on Korean tokens

### 5. Korean Financial LLM Leaderboard 
- Co-developed domain-specific evaluation benchmark in collaboration with universities and industry experts

## 📝 Tech Blog Contributions

| Platform | Title | Description |
|----------|-------|-------------|
| [Devocean OpenLab](https://devocean.sk.com/community/detail.do?ID=167787) | 나만의 온디바이스 AI 구현을 위한 로컬 LLM 환경 구축 | Data preprocessing pipeline & training environment setup for on-device spam filtering LLM using SimHash deduplication, Curriculum Learning, and Knowledge Distillation |

## 😄 Areas of Interest

- LLM Pretraining / Fine-tuning (SFT, DPO, RLHF)
- Quantization / Knowledge Distillation
- RAG / Agent Development
- MLOps / LLMOps Infrastructure
- Observability & Monitoring

<div>

## ⚡ Skills

### 💻 Languages
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white">

### 🤖 ML/DL Stack
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white">
<img src="https://img.shields.io/badge/Hugging Face-FFD21F?style=flat-square&logo=HuggingFace&logoColor=black">
<img src="https://img.shields.io/badge/vLLM-000000?style=flat-square&logo=v&logoColor=white">
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
<img src="https://img.shields.io/badge/Axolotl-FF6B6B?style=flat-square">

### 🗄️ Data & Vector DB
<img src="https://img.shields.io/badge/Qdrant-6E40C9?style=flat-square&logo=Qdrant&logoColor=white">
<img src="https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">

### ☁️ Infrastructure & DevOps
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=black">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white">

### 📊 Observability
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white">
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white">
<img src="https://img.shields.io/badge/Jaeger-66CFE3?style=flat-square&logo=jaeger&logoColor=black">
<img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white">

### 🛠️ Tools
<img src="https://img.shields.io/badge/VS Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white">
<img src="https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white">

</div>

## 🏆 Competitions

| Year | Competition | Result |
|------|-------------|--------|
| 2025 | 국립국어원 인공지능의 한국어 능력 평가 - 한국문화질의응답(나) | 🥈 Silver |
| 2025 | 국립국어원 인공지능의 한국어 능력 평가 - 한국문화질의응답(나) | 🥉 Special Award |
| 2024 | 국립국어원 인공지능의 한국어 능력 평가 - 대화맥락추론(나) | 🥈 Silver |
| 2024 | 국립국어원 인공지능의 한국어 능력 평가 - 일상대화요약(나) | 🥉 Special Award |
| 2024 | 데이콘 재정정보 AI 검색 알고리즘 경진대회 | Top 9.5% (34/359) |
| 2023 | 인공지능콘텐츠융합창작랩 AI 융합 콘텐츠 공모전 | 🥇 1st Place |

## 📫 Contact

[![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:anstmdwn34@gmail.com)](mailto:anstmdwn34@gmail.com) 
[![Velog Badge](https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=velog&logoColor=white)](https://velog.io/@anstmdwn34/posts)