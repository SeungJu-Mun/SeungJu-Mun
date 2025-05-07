<div align="center">

# 👋 Hello, I'm Seungju. I'm conducting research on sLLM. 
![header](https://capsule-render.vercel.app/api?type=wave&height=300&color=ADFF2F&text=NUMCHCOMCH&reversal=false&fontAlignY=48&descAlign=47&descAlignY=63&fontAlign=52)
</div>

## 🔭About me
We are interested in developing non-English LLMs and transferring knowledge from large language models to smaller ones.

### ⚡ research Experience
Development of Finance-domain Specialized LLM 2024.04 ~ 2024.06
→ Fine-tuned small LLMs (Gemma, LLaMA) with LoRA and SFT/DPO for finance-specific tasks such as consultations, product guides, and investment analysis.
→ Built a preprocessing pipeline using SimHash deduplication, OCR, and LLM-based quality filtering.
→ Optimized LoRA hyperparameters, and utilized Accelerate & FSDP for distributed training.
→ Quantized the model with GPTQ (8-bit), integrated vLLM for fast inference, and deployed a benchmark via Streamlit.
→ Achieved 20% performance improvement and halved inference latency.

Development of Korean Financial LLM Leaderboard 2024.06 ~ 2024.06
→ Created domain-specific evaluation benchmark and leaderboard in collaboration with universities and experts.

Development of On-device sLLM for Summarization 2024.07 ~ 2024.09
→ Constructed a continual pretraining setup on 8×A100 GPUs using Axolotl and Accelerate.
→ Extended tokenizer with SentencePiece and initialized embeddings via token-average.
→ Applied group_by_length batching for efficient resource usage, and fine-tuned using SFT/DPO with Evol-Instruct datasets.
→ Quantized model to 4/8-bit using llama.cpp for CPU inference.
→ Improved ROUGE summarization scores by 25%, with 30% compression gain on Korean tokens.

RAG Pipeline Design and Deployment 2024.11 ~ 2025.03
→ Designed and deployed RAG systems for finance, law, and public sectors using Chroma, Qdrant, and OpenSearch.
→ Parsed documents across PDF, DOCX, PPTX, and HWP using OCR and customized parsers.
→ Applied various chunking strategies (recursive, markdown, semantic) and implemented metadata filtering based on intent classification.
→ Enhanced retrieval accuracy with hybrid search and rerankers; implemented function-calling agents for tabular insights.
→ Containerized and deployed via FastAPI and Docker Compose, reducing QA time through automated testing.

### 😄 Areas of Interest
- Machine Learning / Deep Learning
- LLM Pretrain / Fine-Tuning
- Quantization / Knowledge Distillation

<div>

## ⚡ Skills ⚡

  ### 💻 Programming Language
  <img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white">
  <img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"> <br/> 
 
  ### 📚 Stacks
<!-- Python & ML Stack -->
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=Pandas&logoColor=white">
<img src="https://img.shields.io/badge/Numpy-013243?style=flat-square&logo=NumPy&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=Matplotlib&logoColor=white">

<!-- Backend & DevOps -->
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=black">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white">

<!-- Vector DB & LLM -->
<img src="https://img.shields.io/badge/Qdrant-6E40C9?style=flat-square&logo=Qdrant&logoColor=white">
<img src="https://img.shields.io/badge/Hugging Face-FFD21F?style=flat-square&logo=HuggingFace&logoColor=black">

  
  ### 🛠 Tools
  <img src="https://img.shields.io/badge/PyCharm-000000?style=flat&logo=PyCharm&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=Jupyter&logoColor=white"/>  
  <img src="https://img.shields.io/badge/Anaconda-44A833?style=flat&logo=Anaconda&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=Tableau&logoColor=white"/>

 </div>
 
### 📫Contact
[![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:anstmdwn34@gmail.com)](mailto:anstmdwn34@gmail.com) 
[![Velog Badge](https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=velog&logoColor=white)](https://velog.io/@anstmdwn34/posts)

## 🏆 Competitions
- 🥇 2023 인공지능콘텐츠융합창작랩 AI 융합 콘텐츠 공모전(AI+ 콘텐츠 결과 부문) - **1nd placed** [[overview](https://www.gicon.or.kr/board.es?mid=a10201000000&bid=0001&act=view&list_no=29919)]
- 🥈 2024 국립국어원 인공지능의 한국어 능력 평가 경진대회 - 대화맥락추론(나) 부분 은상 수상 [[overview](https://kli.korean.go.kr/benchmark/taskBoardsOrdtm/boardsOrdtm/noticeView.do?page=0&recordId=134&boardOrdtmId=&base.condition=boardOrdtm.title&base.keyword=&size=10)]
- 🥉 2024 국립국어원 인공지능의 한국어 능력 평가 경진대회 - 일상대화요약(나) 부분 특별상 수상 [[overview](https://kli.korean.go.kr/benchmark/taskBoardsOrdtm/boardsOrdtm/noticeView.do?page=0&recordId=134&boardOrdtmId=&base.condition=boardOrdtm.title&base.keyword=&size=10)]
- 2024 데이콘 재정정보 AI 검색 알고리즘 경진대회 - Top 9.5% (34/359) [[overview](https://dacon.io/competitions/official/236295/leaderboard)]
