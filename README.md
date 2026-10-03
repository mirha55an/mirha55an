<h1 align="center">Hey there, I'm Hassan Shahzad</h1>

<p align="center">
  <strong>Software Engineer · Generative AI &amp; LLMs · Retrieval-Augmented Generation</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"></a>
  <a href="https://huggingface.co/mirha55an"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"></a>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LLM%20Evaluation-7C3AED?style=flat-square" alt="LLM Evaluation">
  <img src="https://img.shields.io/badge/RAG%20Systems-2563EB?style=flat-square" alt="RAG Systems">
  <img src="https://img.shields.io/badge/LLM%20Fine--Tuning-DB2777?style=flat-square" alt="LLM Fine-Tuning">
  <img src="https://img.shields.io/badge/NLP-F97316?style=flat-square" alt="NLP">
</p>

---

## About Me

I'm a software engineer focused on **Generative AI, LLMs, and Retrieval-Augmented Generation**. I build and evaluate AI systems end-to-end — from agentic RAG pipelines and LLM fine-tuning to automated testing and evaluation harnesses for frontier models.

- Currently working with **agentic RAG**, **hybrid retrieval**, and **LLM evaluation**
- Experienced in benchmarking outputs from **Google Gemini, Anthropic Claude, and DeepSeek**
- Comfortable across the stack: **PyTorch · Hugging Face · LangGraph · FastAPI · Docker**
- B.CS at the Institute of Management Sciences, Peshawar (2022 – 2026)

---

## Featured Projects

### [HF Docs Agent](https://github.com/mirha55an/hf-docs-agent) — Agentic RAG over Hugging Face docs

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B4A?style=flat)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

A production-oriented agentic RAG system that answers questions over the Hugging Face Transformers and PEFT documentation.

- **LangGraph ReAct agent** that picks between two tools per query: hybrid doc retrieval and GitHub source-code search
- **Hybrid retrieval**: BM25 lexical + ChromaDB vector search, fused with Reciprocal Rank Fusion and reranked by a **BGE cross-encoder**
- Evaluated with **RAGAS** — 0.81 Faithfulness · 0.94 Answer Relevancy
- Dockerized **FastAPI** service deployed on Hugging Face Spaces

<p align="center">
  <a href="https://github.com/mirha55an/hf-docs-agent"><img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github&style=flat-square" alt="GitHub"></a>
  <a href="https://huggingface.co/spaces/mirha55an/hf-docs-agent"><img src="https://img.shields.io/badge/Live%20Demo-Hugging%20Face-FFD21E?logo=huggingface&logoColor=black&style=flat-square" alt="Live Demo"></a>
</p>

---

### [AssignGuard](https://github.com/mirha55an/AssignGuard) — Academic Similarity Detection

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-F97316?style=flat)
![Starlette](https://img.shields.io/badge/Starlette-009688?style=flat)

An NLP-based plagiarism detection system that flags highly similar academic submissions.

- **TF-IDF + cosine similarity, Jaccard similarity, PCA, and DBSCAN clustering** over student submissions
- Full NLP pipeline: tokenization, stopword removal, lemmatization, feature extraction, similarity ranking
- Dark-mode **web dashboard** (Starlette + vanilla JS) with interactive heatmaps and PCA projections

<p align="center">
  <a href="https://github.com/mirha55an/AssignGuard"><img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github&style=flat-square" alt="GitHub"></a>
  <a href="https://assignguard-vercel.vercel.app/"><img src="https://img.shields.io/badge/Live%20Demo-Vercel-000000?logo=vercel&style=flat-square" alt="Live Demo"></a>
</p>

---

### [Multimodal RAG Chatbot](https://github.com/mirha55an/multimodal-rag-chatbot) — Q&amp;A over PDFs &amp; Images

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?logo=googlegemini&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B4A?style=flat)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)

A document intelligence chatbot that answers questions about PDFs and images using RAG powered by Google Gemini.

- Upload a PDF → semantic search over indexed chunks → grounded answers with **page-level source attribution**
- Attaches **Gemini Vision** image understanding alongside retrieved document context
- Built with ChromaDB, LangChain, PyMuPDF, and Streamlit

<p align="center">
  <a href="https://github.com/mirha55an/multimodal-rag-chatbot"><img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github&style=flat-square" alt="GitHub"></a>
</p>

---

<details>
<summary><b>Other repositories</b></summary>

<br>

- [ml-semester-assignment](https://github.com/mirha55an/ml-semester-assignment) — Machine learning semester coursework
- [video-chunks-generator](https://github.com/mirha55an/video-chunks-generator) — Split videos into small chunks
- [assignguard-vercel](https://github.com/mirha55an/assignguard-vercel) — Frontend deployment of AssignGuard

</details>

---

## Technical Skills

<table>
<tr>
<td><b>Generative AI &amp; LLMs</b></td>
<td>

![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![PEFT](https://img.shields.io/badge/PEFT-7C3AED?style=flat-square)
![QLoRA](https://img.shields.io/badge/QLoRA-6D28D9?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-2563EB?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-3B82F6?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B4A?style=flat-square)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)

</td>
</tr>
<tr>
<td><b>Machine Learning</b></td>
<td>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-FFFFFF?logo=matplotlib&logoColor=3572A5)

</td>
</tr>
<tr>
<td><b>Backend &amp; Deployment</b></td>
<td>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Starlette](https://img.shields.io/badge/Starlette-009688?style=flat-square)
![REST APIs](https://img.shields.io/badge/REST%20APIs-2563EB?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Hugging Face Spaces](https://img.shields.io/badge/Hugging%20Face%20Spaces-FFD21E?logo=huggingface&logoColor=black)

</td>
</tr>
<tr>
<td><b>Languages</b></td>
<td>

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)

</td>
</tr>
<tr>
<td><b>Developer Tools</b></td>
<td>

![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white)

</td>
</tr>
</table>

---

## Experience &amp; Education

**LLM Evaluation Engineer** · _Turing_ · Aug 2025 – Dec 2025 _(Remote)_

- Evaluated outputs from frontier LLMs — **Google Gemini, Anthropic Claude, DeepSeek** — for correctness, coding quality, and protocol adherence
- Authored ideal reference implementations and designed public/private test suites to benchmark model-generated code
- Built automated **pytest** suites with **90%+ line and branch coverage** across evaluation pipelines
- Documented evaluation methodologies, edge cases, and model failure patterns for cross-team benchmarking

**Bachelor of Computer Science (BCS)** · _Institute of Management Sciences, Peshawar_ · Oct 2022 – Jul 2026

---

<p align="center">
  <img src="https://img.shields.io/badge/Building%20with%20LLMs%20and%20RAG-7C3AED?style=for-the-badge" alt="Building with LLMs and RAG">
</p>
